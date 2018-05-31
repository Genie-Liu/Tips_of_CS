### irssi using tips
---

常用的服务器连接命令： /NETWORK /CONNECT /SERVER

* /NETWORK  # show the current avaiable network

* /connect chat.freenode.net # connect to the specific network

* /server server_name # change to the server, shortcut Ctrl+x


切换窗口用Alt+数字，Mac有个问题是Option不会发送一个escape信息，需要在终端设置一下把Option作为Meta健，这样才可以使用快捷键


    Choose “Preferences” from the Terminal.app menu
    In the “Settings” group, choose your profile.
    Go to the “Keyboard” tab
    Check “Use option as meta key”

Query Window

/q <nick_name> 单独开启一个私聊窗口 等价于/query

/alias命令查看一些命令的简写模式

设置参数/set, 设置后用/save命令保存

/set timestamp_format %H:%M:%S

配置文件在这： ~/.irssi/config

Perl Scripts

download the perl scripts to your ~/.irssi/scripts directory, and then type:

	/run <scriptname>

Put the scripts (or symbolic links to them) in ~/.irssi/scripts/autorun to make them load automatically when Irssi starts