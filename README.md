# Smart_home
简介：串口接收数据，处理后发送服务器设备：正点原子imx6ull-mini开发板腾讯云服务器

main.c         客户端创建子进程 
fork_dispose.c 接收数据发送给父进程 
fork_receive.c 处理数据发送服务器（多线程） 
fork_usart.c    接收串口数据
server.c       服务器端接收数据
LCD_free.c     4.3寸LCD屏幕显示采集到的数据
