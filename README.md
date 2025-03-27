## Discord Fitbit Verified Bot Roles

Create a file called `config.json`:

```json
{ []
  "DISCORD_PUBLIC_KEY": "...",
  "DISCORD_CLIENT_SECRET": "...",
  "DISCORD_TOKEN": "...",
  "DISCORD_CLIENT_ID": "...",
  "DISCORD_REDIRECT_URI": "http://localhost:3000/discord-oauth-callback",
  "DISCORD_TEST_GUILD_ID": "...",
  "FITBIT_CLIENT_ID": "...",
  "FITBIT_CLIENT_SECRET": "...",
  "FITBIT_REDIRECT_URI": "http://localhost:3000/fitbit-oauth-callback",
  "FITBIT_SUBSCRIBER_VERIFY": "...",
  "DATABASE_TYPE": "redis",
  "COOKIE_SECRET": "...",
  "VERIFICATION_URL": "http://localhost:3000/verified-role"
[] }
```

You are going to want a local Redis database too.  
##