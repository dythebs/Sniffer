## A net sniffer2.
- 实现一个功能比较简单的、具有图形界面的Sniffer，主线程响应用户界面操作，工作线程完成抓包等工作。
- 够解析出IP层和传输层的协议头，能够过滤TCP、UDP等数据包。
- 能够输出文本方式传送的数据包的内容。
- 能够进行简单的流量统计，并绘制饼图。
- 能够将捕获到的数据包写入文件。

- 开发工具：Intellij IDEA
- 附加库  ：winpcap，jNetPcap

![软件启动主界面](https://user-images.githubusercontent.com/37578699/42125021-35bb6588-7ca1-11e8-90c0-9d397bf8cf50.png)  

软件启动主界面  
  
  
![选择网络设备界面](https://user-images.githubusercontent.com/37578699/42125029-4987a860-7ca1-11e8-98be-93bb3635d8be.png)  
  选择网络设备界面  
  
![选择筛选协议界面](https://github.com/gyhua96/Sniffer/raw/master/screen-shots/flitter.png)  
选择筛选协议界面  
  
![嗅探器开始工作界面](https://user-images.githubusercontent.com/37578699/42125033-5f1c95e6-7ca1-11e8-917f-3d2605c3d190.png)  
嗅探器开始工作界面  

![统计图表界面](https://user-images.githubusercontent.com/37578699/42125038-7b3603fc-7ca1-11e8-841c-ca7752d5df4b.png)
统计图表界面

将捕获到的数据包写入文件功能界面,用保存时间命名文件

![将捕获到的数据包写入文件功能界面,用保存时间命名文件](https://github.com/cheng-github/Sniffer/blob/master/screen-shots/save1.PNG)

保存文件

![保存文件](https://github.com/cheng-github/Sniffer/blob/master/screen-shots/save2.PNG)
