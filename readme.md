https://yq.aliyun.com/articles/577887

测试. 打开chrome浏览器，访问web应用主页或者打开空白页”about:blank" ，然后F12在console输入：
new WebSocket("ws://localhost:8080/ws/websocket")
显示：WebSocket {} 则表示连接成功