# 金鑰匙（VPNET）- Windows
## 支持系統版本
* Windows 7 with Service Pack 1 (SP1)
* Windows 8.1
* Windows 10
* Windows Server 2008
* Windows Sever 2012
## 注意事項
### Windows 7 with Service Pack 1 (SP1)、Windows 8.1用户
请从微软官方网站下载安装最新的.NET Framework 4.7.2  
下載地址：https://dotnet.microsoft.com/download/dotnet-framework-runtime/net472  
如果无法安装.NET Framework 4.7.2的用户请到控制面板内的【程序与功能】卸载旧的.NET Framework，重新下载安装，Windows 8和Windows 10自带情况下不需要安装

### 关闭防火墙
Windows 10用户进入Windows Defender，把应用和浏览器控制里面的选项关闭，其他系统用户可在控制面板找到防火墙相关设置项进行关闭。

## 問題及解決方法
### Windows 10用户打开VPNET，提示【Windows已保护您的电脑】
1. 点击这个提示的【更多信息】选择【仍要运行】即可。 
2. 打开Windows Defender安全中心，选择【应用与浏览器控制】，将【检测应用和文件】和【适用于Microsoft Edge的SmartScreen】设置为“关闭”。

### 打开VPNET，Microsoft SmartScreen阻止运行
1. 关闭当前提示，右击VPNET，选择以管理员身份运行

### 杀毒程序提示有程序修改IE连接设置风险
1. 当弹出风险提示，请选择【允许程序所有操作】即可，否则会导致金钥匙无法正常工作。

### Windows 7 with Service Pack 1 (SP1)打开VPNET，弹出配置窗口
1. A.把压缩包内的consola.ttf字体文件复制到C:\Windows\Fonts目录下，重新打开金钥匙即可   

### Google Chrome浏览器/Firefox浏览器无法正常使用VPNET
浏览器的设置方法类似，一般都在浏览器设置有关的Internet选项里面   
A. Google Chrome浏览器的设置方法  
打开Chrome浏览器-设置-系统-打开代理设置-局域网设置，勾选使用自动配置脚本   
B. FireFox浏览器设置   
打开FireFox浏览器 -> 选项 -> 高级 -> 网络 -> 设置 -> 配置访问国际互联网的代理，选择使用系统代理设置   

### 重要！！
Q.360等常用浏览器进行网络访问时提示500 internal server error   
A.遇到该问题是由于系统存在某些软件或浏览器插件强行占用代理所致，例如chrome浏览器中的Proxy SwitchySharp插件或同类型带有代理功能插件影响。可以试着把这类插件和软件停用关闭任务进程后重新启动VPNET重试，如还是不行请使用包内【恢复网络（右击管理员权限运行）.bat】进行尝试恢复。

## 如有问题
请通过vpnlantern@gmail.com反馈

