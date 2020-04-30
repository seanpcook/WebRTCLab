# WebRTCLab

Learning about WebRTC and experimenting with various use cases.

## How To

Run the following:

```bash
# Install 3rd party packages
npm install

# Start socket server
node index.js
```

Open your chrome browser at: <https://localhost:9000/>

## Resources

Tutorial found at:

<https://codelabs.developers.google.com/codelabs/webrtc-web>

## Goals
  •Confirm TURN server relay works when the stream cannot be delivered via UDP and learn about scaling this type of server.
  •Learn how to host from a production site and test capabilities.
  •Develop app that can setup projects and be used to cover live event. One user would be the producer, likely working from laptop/desktop, who recieves up to 3 video streams from users, using devices, at an event. Each stream can be selected and sent to a canvas to produce a single mixed output.
  •Develop an app that can create two teams of four users and faces them off in a game of "pictionary" using a whiteboard app and video streams using getUserMedia.
  •Develop a way to connect a "companion device" in a scenario where a local user may want to see the remote user on a larger screen but use their device's camera, and audio I/O.
