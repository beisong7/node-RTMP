- visit https://www.npmjs.com/package/node-media-server or https://morioh.com/a/e5bcc1c6e05d/a-nodejs-implementation-of-rtmphttp-flvws-flvhlsdash-media-server for more robust implementation

## NODE RTMP SERVER
- Installation
```
npm install
```

- Start
```
node app.js
```

- Ideas to consider
    - stream each video using a unique key
    - capture each key on the logs and send via api to notify app (subscribers) that a new video has started
    - use api for monitoring