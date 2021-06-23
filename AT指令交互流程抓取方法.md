：请点击链接http://doc.openluat.com/article/642/0
### 准备工作

1. 2条3.3V TTL_USB数据线。
2. PC电脑。
3. 串口工具(如SSCOM等）。
4. 待测主板以及让主板工作的电源以及周边。

------

### 连接方法

使用2条TTL_USB的RX线分别连接通信串口的TX和RX，如下图
![img](http://doc.openluat.com/api/static/editormd/uploads/5_30339.png)

> 注意：TTL_USB的TX不要连接到待测主板的串口上，有可能会影响待测主板串口的正常通信

------

### 操作步骤

1. 在PC上打开两个串口工具窗口，分别连接不同的串口端口。
2. 串口波特率设置于待测主板的串口波特率相同
3. 待测主板上电开机
4. 就会分别在两个串口工具窗口上打印出串口发送或接收的AT指令，注意将串口工的时间戳打开。
   ![img](http://doc.openluat.com/api/static/editormd/uploads/5_15879.png)
5. 保存所要的日志就可以了。