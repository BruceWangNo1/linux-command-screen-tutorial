# Screen Tutorial

If you find yourself being bugged by broken ssh connections from time to time, then you have come to the right place. 

Screen is a terminal multiplexer. For detailed information on screen. Please refer to these three great posts.

1. [How To Use Linux Screen](https://linuxize.com/post/how-to-use-linux-screen/)
2. [linux screen 命令详解](https://www.cnblogs.com/mchina/archive/2013/01/30/2880680.html)
3. [screen使用问题，重新attach失败](https://blog.csdn.net/GW569453350game/article/details/46533319)

## Quick Start

If you don't like to read through the three listed web pages above, these five commands will get you well started (enough for me). 

```bash
screen -S sessionName # New a session called sessionName
screen -ls -> List all sessions
screen -r sessionName -> Resume to session sessionName
screen -d sessionName -> Detach from sessionName
Ctrl + a + d # or
screen -d -r sessionName -> Detach from current session and resume to sessionName
```
