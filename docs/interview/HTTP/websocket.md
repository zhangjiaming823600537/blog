## WebSocket 
HTTP协议通信只能由客户端发送，实现想消息通知的这种，我们只能使用“轮询”：每隔一段时间，就发出一个后端请求，询问有没有新的消息更新。

WebSocket 和 HTTP 一样，同属于应用层协议。它最重要的用途是实现了客户端与服务端之间的全双工通信，当服务端数据变化时，可以第一时间通知到客户端。

除此之外，它与http协议不同的地方还有：
- http只能由客户端发起，而webSocket是双向的。
- webSocket传输的数据包相对于http而言很小，很适合移动端使用
- 没有同源限制，可以跨域共享资源

[WebSocket 教程](http://www.ruanyifeng.com/blog/2017/05/websocket.html)