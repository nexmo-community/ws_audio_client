# Websocket Audio Client

Basic Test Page for sending Audio to a websocket server from the browser

This is a single HTML page that uses web audio and getUserMedia to create a client connection to a WebSocket server that sends and receives audio; it's useful for testing out WebSocket servers that are consuming the Nexmo WebSocket API without making the call from Nexmo.

## Using
You can host it anywhere eg localhost or you can use the hosted version at http://s3.sammachin.com/websocketaudio

## Testing
If you enter `wss://echo.websocket.org` in the URL box and click connect, you will connect to the demo WebSocket echo server, use the Talk button like a press-to-talk on a walkie-talkie to send the audio from your microphone, you should hear your own voice back.

## Limitations
* Currently it only supports 16khz PCM audio rate (TODO 8Khz)
* ~There is no support for sending the initial JSON message on connect (TODO)~
* There is no support for DTMF events (TODO)

