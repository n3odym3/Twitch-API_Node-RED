# Twitch-API_Node-RED
The Demo flow allows to use the Twitch API with Node-RED and is able to :
- Generate a Bearer token
- Use the Twitch HTTP API
- Analyze the response and extract informations about a Twitch channel

This demo provides exemples to get the :
- Stream state, lang, title and game
- Viewer count
- Last follower username
- Followers count
- Channel ID and thumbnail

[For more endpoints](https://dev.twitch.tv/docs/api/reference)

## Requirements
[Create your app](https://dev.twitch.tv/console/apps)
- API Client ID
- API Cient Secret

## Setup
- [Import the flow](https://nodered.org/docs/user-guide/editor/workspace/import-export)
- Double clic on the "change" node
- Add your Client ID
- Add your Client Secret
- Add the channel to "analyze"
- Clic on "get bearer token" to generate and save the authentication token
- Clic on "get channel ID" (the channel ID will be used for some requests)



