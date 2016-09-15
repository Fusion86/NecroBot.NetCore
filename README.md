# NecroBot.NetCore

Migrated RocketAPI and other packages to .NET Core so that they can be used on linux/mac/windows etc.

## Requirements:
- [.NET CORE](https://www.microsoft.com/net/core)

## Setup
```
git clone https://github.com/Fusion86/NecroBot.NetCore.git --recursive
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
