####0net：简单的Windows远程控制后门

#####简介：

0net是一个简单的Windows远程控制类后门程序。客户端使用c++编写，服务端使用python编写，目前正在开发中...
项目详细说明：http://www.s0nnet.com/0net


#####功能：

- 支持反向连接（IP和域名）到指定服务器
- 实现常见的远程指令：关机、重启、取消关机、弹窗、锁屏、重置光标、冻结鼠标和键盘
- 支持截取目标主机屏幕并传回服务端
- 支持开机自启动
- 支持通过管道实现远程CMD并传回服务端
- 支持文件上传、下载 --开发中
- 支持键盘记录（实时记录和离线记录）--开发中
- 支持摄像头截屏并发回服务端 --开发中
