# goldenkey-windows

# User Documentation

## Windows version requirements
To install GoldenKey(VPNET), you need Windows versions:
*	Windows 7 with Service Pack 1 (SP1)
*	Windows 8.1
*	Windows 10
*	Windows Server 2008
*	Windows Sever 2012

##	Windows 7 with Service Pack 1 (SP1) 、 Windows 8.1
Please download and install the latest .NET Framework 4.7.2 from the Microsoft website.  
Download Url:   
https://dotnet.microsoft.com/download/dotnet-framework-runtime/net472  
If not install .net Framework 4.7.2, Uninstall the old .NET Framework from programs and functions in the control panel, Redownload and install .net Framework 4.7.2 from the Microsoft website, Windows 8 and Windows 10 come with no installation required

##	Question & Answer
###	Q: Can't connect to the Internet ?
A: Close Windows Defender

###	Q: Windows7 with Service Pack 1(SP1) open vpnet, Alert Configure window ?
A: Step1: Copy fonts file VPNET-win-X.X.X\consola.ttf to C:\Windows\Fonts\
Step2: Reopen VPENT

###	Q: Uses VPNET, Google Chrom/FireFox not connection internet ? 
A: 
Google Chrome:
Step1: Open chrome -> Settings -> System -> Open proxy settings
Step2: Click [LAN settings]
Step3: Choice [Use autoMatic configuration script]
Address：https://127.0.0.1:8123/proxy.pac

FireFox :
Step1: Open firefox -> Options -> Settings - > User system proxy settings

###	Q: Browser access network: 500 internal server error ?
A1: Maybe some software or browser plug-in using the proxy, Such as [Proxy SwitchySharp] plugin in chrome or other plugins with Proxy functionality. Please shutdown such plug-ins and software, restart VPNET to try again.
A2: Or try this: Double click VPNET-win-X.X.X\恢复网络（右击管理员权限运行）.bat

## Support
Send email to vpnlantern@gmail.com

