# 简易SignalR聊天室
支持.net framework 4.0的双向通讯组件 实现实时通信。
# 什么是实时通信的Web呢？
就是让客户端（Web页面）和服务器端可以互相通知消息及调用方法，当然这是实时操作的。
WebSockets是HTML5提供的新的API，可以在Web网页与服务器端间建立Socket连接，当WebSockets可用时（即浏览器支持Html5）SignalR使用WebSockets，当不支持时SignalR将使用其它技术来保证达到相同效果。 
SignalR当然也提供了非常简单易用的高阶API，使服务器端可以单个或批量调用客户端上的JavaScript函数，并且非常 方便地进行连接管理，例如客户端连接到服务器端，或断开连接，客户端分组，以及客户端授权，使用SignalR都非常容易实现。 