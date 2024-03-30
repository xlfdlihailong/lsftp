# lsftp
sftp tool easy to use;sftp传输工具
1.	lsftp产品
lsftp是一款专为解决与linux服务器sftp传输的工具,为用户sftp传输使用方便,安全,高性能为目标开发
1.1.	主要功能
目录文件自动刷新,高性能
上传/下载文件
上传/下载/目录(递归包含所有子目录)
会话组树节点展开状态保存
文件/目录拖动上传
支持中文以及空格目录
一键SSH登录
一键VNC登录
密码rc4加密,保证使用安全
上传文件异常 断线重传
上传目录/下载文件/下载目录异常 断点续传
文件/目录的本地/远程常用操作
1.2.	使用方式
1.2.1.	会话组/会话管理
 
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/18ae562a-adad-43e5-a7c5-3fa5e4bf381f)
![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/2e26f802-8539-4ff8-8d41-d3156c22bdc1)


软件左侧树目录管理会话组与会话,鼠标右键操作新建组,新建会话,编辑会话等
1.2.2.	连接服务器
完成会话后,双击会话即可连接,同时显示本地目录和远程目录,类似xftp:
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/26592622-9ce1-4812-8226-acdd447ce344)

左侧为本地目录,右侧为远程目录,有断线重连功能
1.2.3.	文件传输
双击左边文件直接上传到远端,双击右边文件直接下载到本地
 
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/026c1fbc-487a-49b0-9c5e-4f2f2d321076)
![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/e0abe359-9edb-42c7-8620-6fdfbdab1a0f)

1.2.4.	目录传输
目录传输需要右键目录—上传/下载:
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/8b699305-b2a3-478b-aac4-408f66856748)

 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/f384a784-15ec-4b8d-895d-a987e634f3ce)


1.3.	特色功能
1.3.1.	绑定putty客户端,实现一键登录
通过会话全自动一键登录putty客户端:解决了传输数据的同时需要执行命令的不便之处
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/c20eb551-cfc1-4c40-b265-8cffd56cc658)

1.3.2.	绑定vnc客户端,实现一键登录
通过会话全自动一键登录vnc(前提是服务器配好vncserver):
 ![image](https://github.com/xlfdlihailong/lsftp/assets/13100232/fbe9d202-c5d7-47bc-b3f4-d1f96c3262de)

1.3.3.	远端目录自动刷新,高性能
远端目录每秒自动刷新,高延迟服务器5秒刷新一次

