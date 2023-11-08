### 特点
- **服务器可以主动向客户端推送信息，客户端也可以主动向服务器发送信息**
- 建立在 TCP 协议之上，服务器端的实现比较容易
- **数据格式比较轻量，性能开销小，通信高效**
- 可以发送文本，也可以发送二进制数据。
- **没有同源限制，客户端可以与任意服务器通信**
- 协议标识符是ws（如果加密，则为wss），服务器网址就是 URL。
```js
ws://example.com:80/some/path
```

### 客户端API
[参考MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket)

### 服务端实现
