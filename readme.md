- create an app in slack (from scratch)
- basic info -> App Creds -> signing Secret
- oAuth -> install app to get token -> bot user OAuth Token 
- oAuth -> Scopes -> Bot Token Scopes
    - chat:write
- Event Subs => Enable -> Request URL /slack/events
- Event Subs => Sub to bot events 'message:im'
- App Home -> Allow user to send slash commands and ...