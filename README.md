# Zoom Video SDK minimum sample
This is a smallest sample that describes how to use the Zoom Video SDK.
For details, please visit [Zoom Video SDK for web](https://developers.zoom.us/docs/video-sdk/web/).

# How to use
1. You will need to populate the Video SDK client Key and secret in `.env` file. For details, visit [Get Video SDK credentials](https://developers.zoom.us/docs/video-sdk/auth/#generate-a-video-sdk-jwt](https://developers.zoom.us/docs/video-sdk/developer-accounts/#get-video-sdk-credentials)https://developers.zoom.us/docs/video-sdk/developer-accounts/#get-video-sdk-credentials).
1. Then, run ```npm install``` to install required package.
2. ```node index.js``` to start.

## Notes
You will need to run this on a SSL certified web server. If you run locally, you might need to use a CORS test Chrome extensions such as [Allow CORS: Access-Control-Allow-origin](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf/) before start.
