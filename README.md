# ShoutoutBot

Download: https://github.com/Arkkis/ShoutoutBot/releases/latest

Requirements:
- Hosting Bundle https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime

Add OBS BrowserSource with URL: http://localhost:5777/index.htm

Fill your Twitch credentials to file appsettings.json:
- Twitch username
- Access Token and Client ID must be get from here: https://twitchtokengenerator.com/quick/B9C46R4wmJ

Example:
```
{
  "Twitch": {
    "Username": "arkkis",
    "ChatAccessToken": "öovny5ov32po5v73256on37632"
  }
}
```

Commands:
- !so username - Shouts out typed user
- !title titlemessage - Changes Twitch channel title
- !game gamename - Changes Twitch channel game
