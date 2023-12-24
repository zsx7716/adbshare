# adbshare
Share Android phone with others online
Online adb debug tool usage 
一、	Open adbshare.com
 
Click  
二、	Connect your Android device
	1. Connect device to computer
	2. Select "File Transfer" mode
	3. Enable "Android Debug" mode (help?)
	4. Click here to bind device
 
Click  
三、	Select device
 
四、	Create link
 
Click  
 
 
Waiting for the status to switch to "Ready"
五、	Enable sharing
 
Check the link and click  
六、	Share link
 
七、	Device certification
Others click on the link you shared and enter the verification code
 
Click  
八、	Remote debug
Method 1：
Execute the following command through the local adb program
 
 Method 2：
Click on the link to remotely connect to your phone online for debugging
 
 
 


Additional explanation:

1. Please shut down the local adb kill server before binding the device on the web page, otherwise conflicts may arise

2. When connecting to devices shared by others through local adb software, please first disable the local TCP protocol proxy

3. The usage time of the testing link is limited to 8 minutes and the speed is limited to 50KBps, for learning and research purposes only

4. Online mobile debugging tool modified from Github: yume chan/ya webadb. Welcome to follow the source author


# adbshare
在线adb调试工具使用指导
一、	打开adbshare.com
 点击 
二、	连接手机
	将手机连接到计算机
	选择“文件传输”模式
	启用“安卓调试”模式（帮助？）
	点击此处绑定到手机
 
点击 
三、	选择设备
 
四、	新建链路
 
点击 
 
 
等待状态切换为“可以使用”
五、	开启共享
 
勾选链路，然后点击 
六、	分享链接
 
七、	设备认证
他人点击你分享的链接，输入验证码
 
点击 
八、	远程调试
方式一：
通过本地adb程序执行以下命令
 
 
方式二：
点击链接，在线远程连接手机调试
 
 
 


补充说明：
1、	在网页端绑定设备之前请关闭本地adb服务（adb kill-server），否则会产生冲突
2、	在通过本地adb软件连接他人分享的设备时候，请先关闭本地的TCP协议代理
3、	测试链路的使用时间限定为8分钟、速度限定为50KBps，仅供学习和研究使用
4、	在线连接手机调试工具修改自github: yume-chan/ya-webadb，欢迎关注源作者
