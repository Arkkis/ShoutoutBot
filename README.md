# ShoutoutBot

Requirement: https://download.microsoft.com/download/1/6/5/165255E7-1014-4D0A-B094-B6A430A6BFFC/vcredist_x86.exe

Download: https://github.com/Arkkis/ShoutoutBot/releases/latest

Add Shoutout layout to OBS BrowserSource with URL: http://localhost:5777/index.htm

Add Now Playing to OBS BrowserSource with URL: http://localhost:5777/np.htm

Logging is written to ```Documents\shoutoutbot_logs.log```:

Application settings are stored in ```Documents\shoutoutbot_settings.json```:
```
{
  "Twitch": {
    "Username": "arkkis",
    "ChatAccessToken": "öovny5ov32po5v73256on37632"
    "ClientId": "k6tali5k6bvilak43b6vl3aik64va"
  },
  "General": {
    "ShowLogging": true,
    "UseShoutoutLayout": true,
    "ShoutoutUserOnChat": true,
    "UseNpCommand": true
  }
}
```

Commands:
- !so username - Shouts out typed user
- !title titlemessage - Changes Twitch channel title
- !game gamename - Changes Twitch channel game
- !np - Tells which song is playing on broadcaster's Spotify
