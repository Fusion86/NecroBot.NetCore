# NecroBot.NetCore

Migrated RocketAPI and other packages to .NET Core so that they can be used on linux/mac/windows etc.

## Requirements:
- [.NET CORE](https://www.microsoft.com/net/core)

## Setup
Use this simple script to clone and build this repository in currentDirectory/NecroBot.NetCore
```
curl -s https://gist.githubusercontent.com/WouterVisser/ef0f683b3c4174e162cd7a0a938bf543/raw/31326406492ac4c2839fe8d05c91e4b8cca86b21/necrobot-cli-netcore-install.sh | bash -s
```
or copy and paste the code below
```
git clone https://github.com/woutervisser/NecroBot.NetCore.git --recursive
cd NecroBot.NetCore
dotnet restore
# now is a good time to edit the config files
# after the config files are setup correctly you can run the bot
cd NecroBot.CLI.NetCore
dotnet run
```

## Config
Edit auth.json and config.json in PoGo.NecroBot.CLI.NetCore/Config. Remember to add quotes!

## Run
```
cd NecroBot.NetCore/PoGo.NecroBot.CLI.NetCore
dotnet run
```

## Update
It's recommended to check for package updates after you updated your repository (by using git pull)
```
cd NecroBot.NetCore
dotnet restore
```

## Credits
- Cormaltes for porting this to .NET Core
- Insensitivity for PogoProtos
- ForexRev for Pokemon-Go-Rocket-API
- NECRBOTIO and NoxxDev for NecroBot
