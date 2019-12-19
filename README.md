# websocks

[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/abersheeran/websocks?style=flat-square)](https://hub.docker.com/r/abersheeran/websocks)

基于隧道与拟态流量混淆的匿名通信系统。

可对传输层的流量数据进行加密混淆，保护用户上网时的信息、隐私安全。

TCP: 使用隧道流量混淆技术，将需要传递的数据放在 WebSocket 的有效载荷中，作为二进制帧传递。

UDP: 使用拟态流量混淆技术，将需要传递的数据进行随机数字亦或加密并填充任意长度的无效数据后，再传递与服务器。

关于本项目使用方法、详细设计介绍以及其他内容请访问 [`websocks:wiki`](https://github.com/abersheeran/websocks/wiki)
