# Libary Used in This Repo
- "react-native": "0.50.3"
- "react-native-webrtc": "^1.58.3"

# Functionality
- Janus WebRTC Gateway Video Room Implementation
- Mobile Users can send teh audio and video msg to other paritciapnts up to 6 max (can configure in janus)

# TODO
- [x] iOS works
- [ ] Android works
- [x] Local camera
- [x] Remote view
- [ ] Audio mute
- [ ] Video mute
- [ ] Unpublish and publish their own video
- [ ] Switch front and back camera
- [ ] Refactor index.js and janus.mobile.js
- [ ] Any Requst? Could you make the issue in this repo?

# Setup
- Set up the janus with wss configured following by https://github.com/atyenoria/janus-webrtc-gateway-docker
- Change config.example.js to config.js and edit the content as you configured about Janus
- Code Signing for building on real device
- change the node path for you env, Build Phases -> Bundle React Native code and images ("export NODE_BINARY=/Users/jima/.nodebrew/current/bin/node")
- Build the iOS project

# License
- MIT