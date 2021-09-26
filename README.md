# Conference Call
A conference call implementation using WebRTC, Socket.io and Node.js. This demo is ideal for not more than 4 devices. 
Add Danmaku feature for research study use.

Original repo https://github.com/amirsanni/Video-Call-App-NodeJS from amirsanni

Danmaku engine repo https://github.com/weizhenye/Danmaku from weizhenye

See https://github.com/CapLock-OCTO/WebRTC-withoutDanmaku for the Danmaku disabled version (Porject research purpose only)


# Getting Started
- Run `npm ci`
- `npm start`


# Features
- Multi-participants
- Toggling of video stream
- Toggling of audio stream (mute & unmute)
- Screen sharing
- Text chat
- Mute individual participant
- Expand participants' stream
- Screen Recording
- Video Recording
- Danmaku Feature (New!)

# Nice to have feature (todo-list)
- On/off switch of Danmaku display (should be very easy by show/hide the danmaku container `dm-container`)
- Danmaku Font Styling customization (now hard written in the createComment callback func.)
- When someone sharing screen, make his screen looks bigger (First priority)
- Customize window size of other users (tricky but doable with jQuery)

 
# Deploy version
Application hosted at Heroku: https://webrtc-danmaku.herokuapp.com/.
