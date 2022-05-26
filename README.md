# ro-single-client

> 仙境RO传说-单机版-客户端（登录补丁）
<br/>配套服务端仓库：[https://github.com/lyy289065406/ro-single-server](https://github.com/lyy289065406/ro-single-server)

------

## 运行环境

　![](https://img.shields.io/badge/Platform-Windows%207%2f8%2f10%20x64-brightgreen.svg) ![](https://img.shields.io/badge/Platform-Windows%20Server%202003%2f2012%20x64-brightgreen.svg) 


## 安装说明

> 韩服客户端（三转复兴后）下载：Ragnarok_KRO_20190306_Lite 【[百度网盘(dgui)](https://pan.baidu.com/s/1vrh-9wE29tfZvDiS10wkxw)】【[韩国官网](http://ro.gnjoy.com/pds/down/)】~【[99Max:收费](http://www.99max.me/thread-485-1-1.html)】~

- 下载韩服客户端（版本必须是 Ragnarok_KRO_20190306_Lite）
- 解压客户端到任意位置（<b>路径不要有中文</b>）
- 下载本仓库（客户端补丁）：`git clone git@github.com:lyy289065406/ro-single-client.git`
- 把客户端补丁中的 `data_ch.7z` 解压为 `data_ch.grf`
- 覆盖客户端补丁到韩服客户端根目录
- 双击运行 `RO仙境传说_Setup_Plus.exe` 修改配置
- 双击运行 `RO仙境传说_v4.3_Data.exe` 即可进入游戏


## 关于多人联机

默认情况下客户端是单机模式游戏的，指向服务端的 IP 是 127.0.0.1 。

假如服务端搭建时使用了联网模式，那么客户端要对应修改所连接的服务器 IP。

配置文件为 `data/sclientinfo.xml`，修改其中的 `<address>` 即可。

> 详见服务端 [联机模式的搭建教程](https://github.com/lyy289065406/ro-single-server#0x06-%E6%80%8E%E6%A0%B7%E6%90%AD%E5%BB%BA%E8%81%94%E6%9C%BA%E6%9C%8D%E5%8A%A1%E5%99%A8)


## 关于乱码

客户端内的某些目录、文件，以及在游戏内看见的乱码（如【导航】、【Tips Box】等），其实都是韩文。

主要因为我们在中文系统上用韩服客户端就会出现这种情况，不过并不影响游戏。

而且这种情况，也有部分原因是翻译组的锅，没有完全翻译导致的。

> `data_ch.grf` 就是语言包，配置文件为 `DATA.INI`


## RO 资料站

- Nemo: [Github](https://github.com/Neo-Mind/NEMO) [Gitlab](https://gitlab.com/4144/Nemo) [Web](http://nemo.herc.ws/) （Kro 历年客户端、补丁等下载）
- iRO: [https://irowiki.org/wiki/Main_Page](https://irowiki.org/wiki/Main_Page)
- ROWiki: [https://rowiki.net/Main_Page](https://rowiki.net/Main_Page)
- RO321: [http://ro321.com](http://ro321.com)
- 17RO: [http://www.17ro.com/](http://www.17ro.com/)
- 幻想厅: [https://rd.fharr.com](https://rd.fharr.com)
- 巴哈姆特（需梯子）: 
<br/>　[https://acg.gamer.com.tw/acgDetail.php?s=4708](https://acg.gamer.com.tw/acgDetail.php?s=4708)
<br/>　[https://forum.gamer.com.tw/A.php?bsn=4212](https://forum.gamer.com.tw/A.php?bsn=4212)


------
## 版权声明

　[![Copyright (C) 2016-2020 By EXP](https://img.shields.io/badge/Copyright%20(C)-2016~2019%20By%20EXP-blue.svg)](http://exp-blog.com)　[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
  

- Site: [http://exp-blog.com](http://exp-blog.com) 
- Mail: <a href="mailto:289065406@qq.com?subject=[EXP's Github]%20Your%20Question%20（请写下您的疑问）&amp;body=What%20can%20I%20help%20you?%20（需要我提供什么帮助吗？）">289065406@qq.com</a>


------
