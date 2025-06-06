# Shell命令防火墙

#### 一 、介绍
Shell命令防火墙用于发现和防御服务器所有的Shell命令调用，是业界独有创新产品，是对0day攻击的最有效防御。

#### 二、承诺和不承诺
承诺：为了保证服务器安全，除首次安装，任何时候绝不联网。

不承诺：无论任何原因引发的任何问题，都不负任何责任；请务必在测试环境完美演练后，再部署到生产环境。

注意：WEB管理9998端口禁止向公网开放，或者严格设置IP白名单访问权限。

#### 三 主要功能
    1、全程记录linux服务器所有的Shell命令运行。   
    2、用AI技术分析检测威胁Shell命令或者人工设置Shell白名单等，保障系统安全。
    3、可以对接第三方大模型如DeepSeek，用更高级的AI再次检测shell命令，给政府项目赋予更多的AI故事。

#### 四、安装步骤
要求内核版本大于5.10，推荐2022年以后的linux发行版本：

Debian 12+

RHEL 9.0+

Rocky Linux 9.0+

Fedora 36+

...

商业版集成到全流量防火墙防御系统OpenHFw中，支持Linux x86 64位系统（内核大于5.0），保证可以上网，以root权限运行下面命令：

    1、 wget http://101.42.31.94/openhfw
    2、 chmod +x ./openhfw
    3、 ./openhfw

首次安装下载大约半分钟，出现System is running.....代表安装成功，可以WEB管理口9998（防火墙允许）登录进去。

#### 五、运行停止卸载
启动运行:  ./openhfw         后台模式运行:   ./openhfw daemon

停止运行:  ./openhfw stop    卸载 :   rm  /openhfw/ -rf

默认没加开机启动，请自行把openhfw 加入开机启动程序。

#### 六、实战演示地址

实战地址 [http://39.106.251.213:9998/ok.html](http://39.106.251.213:9998/ok.html)

更多演示[http://39.106.251.213:9998/prochtml/open_source.html](http://39.106.251.213:9998/prochtml/open_source.html)

#### 七、付费演示地址

请用大屏电脑观看，首次加载大屏组件需要10秒：
集中管控大屏 [http://39.106.251.213/center.html](http://39.106.251.213/center.html)

#### 八、源码或技术白皮书请加微信号httpwaf

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/wechat.png)

#### 九、来一张首页图片

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/home.png)
