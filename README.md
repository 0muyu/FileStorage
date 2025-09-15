# 演示视频
- 仓库 preview.mp4


----

# 子模块 server

服务器源码

----

# 子模块 client

客户端项目源码


# 简介

## 技术栈：Qt、MySQL、MD5、SQLite、Linux、Nginx、FFmpeg、SDL、OpenGL

## 功能描述：注册、登录、文件与文件夹的上传下载、断点续传、秒传、路径跳转、限时文件分享、视频文件可在线边转码边播放、跳转。

## 服务器：在WSL的Ubuntu系统上部署；采用 epoll+线程池模型搭建服务器；数据库使用MySQL，使用Nginx(反向代理)+RTMP 流媒体服务器，增加HLS模块以实现视频预览。


## 客户端：Windows系统Qt Creator开发，文件内容使用MD5摘要，SQLite保存上传下载任务实现断点续传；通过FFmpeg库对音视频数据进行解码，使用SDL对解码的音频数据进行播放；OpenGL对视频进行渲染播放。