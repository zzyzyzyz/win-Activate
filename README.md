项目摘抄自https://zhuanlan.zhihu.com/p/6823352707

安全提示：激活方法来源于网络，属于github上的MAS开源项目，谨慎激活。安全问题请自行斟酌，注重安全的小伙伴们请购买正版。

MAS作为一个开源免费的激活工具，以其安全性、易用性和强大的功能受到了用户的青睐。它不仅提供了多种激活方式，还考虑到了用户的不同需求，如永久激活和临时激活。此外，MAS的开源特性也让用户可以更加放心地使用，因为源代码的透明度可以确保没有隐藏的安全风险。

项目网址：

https://massgrave.dev/

注意：

PowerShell 中的 IRM 命令从指定的 URL 下载脚本，然后 IEX 命令执行该脚本。
在执行命令之前，请务必仔细检查 URL，如果手动下载文件，请验证来源。
请谨慎，因为有些应用程序通过在 IRM 命令中使用不同的 URL 来传播伪装成 MAS 的恶意软件。

一.PowerShell激活：
打开 PowerShell (不是 CMD). 搜索框输入PowerShell,然后打开

复制一下代码到命令行，按回车键

irm https://get.activated.win | iex


3.你会看到激活选项。选择[1] HWID 用于 Windows 激活。选择[2] Ohook 用于 Office 激活

二、离线激活方法：

1、下载下面链接的文件

https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip

2、解压文件

3、在文件夹中找到名字为All-In-One-Version-KL的文件夹

4、右键，以管理员运行 MAS_AIO.cmd文件

5、会看到激活选项，和上面的在线激活界面一样了


