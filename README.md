## webrtc-demo

- [demo1](./demo1/index.html): 调用本地摄像头和音频
- [demo2](./demo2/index.html): 创建本地点对点通信，即 A 获取音频，B 呼叫 A， B 获得 A 的音频并播放
- [demo3](./demo3/index.html): 使用 `RTCDataChannel` 通信，发送文本信息
- [demo4](./demo4): 通过网络传输 实现点对点服务 注意 `navigator.getUserMedia`只有在 `localhost` 或者 `https` 等安全环境下才可以用
- [demo5](./demo5): 使用 [peerjs](https://github.com/peers/peerjs) 实现直接点对点通信
- [demo5](./demo6): 使用 [peerjs](https://github.com/peers/peerjs) 实现直接点对点视频通信

## 参考链接

- [阮一峰 WebRTC](http://www.w3cbus.com/htmlapi/webrtc.html)
