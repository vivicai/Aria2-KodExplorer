# 1、Aria2-KodExplorer

Aria2+AriaNG+KodExplorer for CentOS7一键安装脚本

转自原作者https://lala.im/(在原作者基础上更新了软件地址和默认端口)

**脚本仅支持CentOS7X64，且系统必须是纯净的。安装请使用ROOT用户执行下面的命令：**

wget https://raw.githubusercontent.com/hi-KK/Aria2-KodExplorer/master/Aria2%2BAriaNG%2BKodExplorer_Install.sh

chmod +x Aria2+AriaNG+KodExplorer_Install.sh

./Aria2+AriaNG+KodExplorer_Install.sh

### 脚本会帮你安装如下软件
（均是目前的最新版本）
Nginx 1.14/PHP 7.2.9/Aria2 1.34.0/AriaNG 0.5.0/KodExplorer 4.36

安装完成后回显内容：

AriaNG管理地址：http://你的VPS公网IP:11585

KodExplorer管理地址：http://你的VPS公网IP:11586

默认的Aria2 RPC密码：lala.im

### Aria2管理命令：

systemctl start aria2

systemctl stop aria2

systemctl restart aria2

systemctl status aria2

### 使用注意：

1.aria2配置文件在如下路径：
/etc/aria2/aria2.conf

在脚本安装成功之后建议立即编辑这个配置文件，修改RPC的默认密码，确保系统安全。修改RPC密码的配置选项是：
rpc-secret=填写一个你的密码

修改完成之后需要重启一次Aria2：
systemctl restart aria2

2.在脚本安装成功之后，建议立即打开KodExplorer设置管理员密码，并删除demo和guest用户，确保系统安全

---

# 2、Aria2_auto_install.sh
Aria2 for CentOS 6+ / Debian 6+ / Ubuntu 14.04 + 一键安装脚本
（转自逗比大神https://doub.io）
***推荐 Debian 8 x64，这个是我一直使用的系统，我的脚本在这个系统上面出错率最低。***
### 安装步骤
执行下面的代码下载并运行脚本。
> wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/aria2.sh && chmod +x aria2.sh && bash aria2.sh

运行脚本后会出现脚本操作菜单，选择并输入 1 就会开始安装。

### 使用说明
进入下载脚本的目录并运行脚本：
> ./aria2.sh

然后选择你要执行的选项即可。


