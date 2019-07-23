# 金鑰匙（VPNET）- Windows
## 支持系統版本
* Windows 7 with Service Pack 1 (SP1)
* Windows 8.1
* Windows 10
* Windows Server 2008
* Windows Sever 2012
## 注意事項
### Windows 7 with Service Pack 1 (SP1) 、 Windows 8.1的用户，请从微软官方网站下载安装最新的.NET Framework 4.7.2框架（无法安装.NET Framework 4.7.2的用户请到控制面板内的【程序与功能】卸载旧的.NET Framework，重新下载安装，Windows 8和Windows 10自带情况下不需要安装）
下載地址：https://dotnet.microsoft.com/download/dotnet-framework-runtime/net472

### 关闭防火墙
Windows 10用户进入Windows Defender，把应用和浏览器控制里面的选项关闭，其他系统用户可在控制面板找到防火墙相关设置项进行关闭。

## Q & A
### 
* Windows 10用户打开VPNET，提示【Windows已保护您的电脑】
1.点击这个提示的【更多信息】选择【仍要运行】即可。
2.打开Windows Defender安全中心，选择【应用与浏览器控制】，将【检测应用和文件】和【适用于Microsoft Edge的SmartScreen】设置为“关闭”。

* 打开VPNET，Microsoft SmartScreen阻止运行
1. 关闭当前提示，右击VPNET，选择以管理员身份运行

* 杀毒程序提示有程序修改IE连接设置风险
1.当弹出风险提示，请选择【允许程序所有操作】即可，否则会导致金钥匙无法正常工作。

* Windows 7 with Service Pack 1 (SP1)打开VPNET，弹出配置窗口
1. A.把压缩包内的consola.ttf字体文件复制到C:\Windows\Fonts目录下，重新打开金钥匙即可。

* Google Chrome浏览器/Firefox浏览器无法正常使用VPNET
1.




## 如有问题
请通过vpnlantern@gmail.com反馈

