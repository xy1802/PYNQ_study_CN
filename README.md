# PYNQ_study_CN
This file may help your PYNQ connect to the Internet . Other options will be added later.  
这个教程会教你如何使PYNQ-z2联网，
# 让PYNQ-Z2 连接上网络的方法  
首先ping一下外网，看看PYNQ板是否能联网  
```sh
ping www.baidu.com
```
如果没有相应，右击屏幕右下方的网络，选择“打开网络和Internet设置”  
点击更改适配器选项  

![images](https://github.com/xy1802/PYNQ_study_CN/blob/master/open.png)
|:--:| 
|选择更改适配器选项|

选择你正在使用的网络  
点击属性，打开共享 
![images](https://github.com/xy1802/PYNQ_study_CN/blob/master/share.png)
|:--:| 
|共享后的显示|

勾选共享 并选择PYNQ的网络端口  
![images](https://github.com/xy1802/PYNQ_study_CN/blob/master/net.png)
|:--:| 
|共享后的显示|

最后，再ping 一下看看能否上外网 

![images](https://github.com/xy1802/PYNQ_study_CN/blob/master/success.png)
|:--:| 
|成功联网|

# 注意事项
你需要有双网卡，一般笔记本上都有，但是台式机可能没有，所以共享时会出问题。
