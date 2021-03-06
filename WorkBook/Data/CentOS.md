# CentOS

## 1.简介

> CentOS(Community Enterprise Operating System，中文意思是:社区企业操作系统)是Linux发行版之一，它是来自于Red Hat Enterprise Linux依照[开放源代码](https://baike.so.com/doc/6270840-6484264.html)规定释出的源代码所编译而成。由于出自同样的源代码，因此有些要求高度稳定性的[服务器](https://baike.so.com/doc/4487696-4696885.html)以CentOS替代商业版的[Red Hat](https://baike.so.com/doc/5499561-5736997.html) Enterprise Linux使用。两者的不同，在于CentOS并不包含封闭源代码软件。

## 2.基本信息

| *中文名称：* | *社区企业操作系统* | *最新版本：* | *CentOS 7.4.1708* |
| ------------ | ------------------ | ------------ | ----------------- |
| *外文名称：* | *CentOS*           | *价格：*     | *免费*            |
| *类型：*     | *操作系统*         | *发布日期：* | *2004年05月14日*  |

## 3.最新版本

最新版本为 CentOS 7。上个版本是2013-12-01的6.5。

CentOS 7于2014年7月7号正式发布，这是一个企业级的Linux发行版本，基于Red Hat红帽免费公开的源代码。

CentOS 7首个正式版的版本号为7.0.1406，主要更新内容如下:

- 内核更新至 3.10.0

- 支持 Linux 容器

- Open VMware Tools 及 3D 图像能即装即用

- OpenJDK-7作为缺省 JDK

- 原地升级 6.5 至 7.0

- ext4 及 XFS 的 LVM 快照

- 转用 systemd、firewalld 及GRUB2

- XFS 作为缺省文件系统

- 内核空间内的 iSCSI及FCoE

- 支持PTPv2

- 支持40G以太网络卡

上游RHEL 7主要改进:

内核更新至3.10.0;支持Linux容器，OpenVMwareTools及3D图像能即装即用，OpenJDK7作为缺省JDK，ext4及XFS的LVM快照，转用systemd、firewalld及GRUB2，XFS作为缺省文件系统，内核空间内的iSCSI及FCoE，支持PTPv2，支持40G网卡等。

CentOS 是一个基于Red Hat Linux 提供的可自由使用源代码的企业级Linux发行版本。每个版本的 CentOS都会获得十年的支持(通过安全更新方式)。新版本的 CentOS 大约每两年发行一次，而每个版本的 CentOS 会定期(大概每六个月)更新一次，以便支持新的硬件。这样，建立一个安全、低维护、稳定、高预测性、高重复性的 Linux 环境。CentOS是Community Enterprise Operating System的缩写。

CentOS 是[RHEL](https://baike.so.com/doc/4813482-5029950.html)([Red Hat Enterprise Linux](https://baike.so.com/doc/707395-748786.html))源代码再编译的产物，而且在[RHEL](https://baike.so.com/doc/4813482-5029950.html)的基础上修正了不少已知的 Bug ，相对于其他 Linux 发行版，其稳定性值得信赖。

CentOS在2014初，宣布加入Red Hat。

**CentOS 加入红帽后不变的是:**

1. CentOS 继续不收费
2. 保持赞助内容驱动的网络中心不变
3. Bug、Issue 和紧急事件处理策略不变
4. Red Hat Enterprise Linux 和 CentOS 防火墙也依然存在

**变化的是:**

1. 我们是为红帽工作，不是为 RHEL
2. 红帽提供构建系统和初始内容分发资源的赞助
3. 一些开发的资源包括源码的获取将更加容易
4. 避免了原来和红帽上一些法律的问题

## 4.特点

1. 可以把CentOS理解为Red Hat AS系列!它完全就是对Red Hat AS进行改进后发布的!各种操作、使用和RED HAT没有区别!

2. CentOS完全免费，不存在RED HAT AS4需要序列号的问题。

3. CentOS独有的yum命令支持在线升级，可以即时更新系统，不像RED HAT那样需要花钱购买支持服务!

4. CentOS修正了许多RED HAT AS的BUG!

5. CentOS版本说明:CentOS3.1 等同于 RED HAT AS3 Update1 CentOS3.4 等同于 RED HAT AS3 Update4 CentOS4.0 等同于 RED HAT AS4

## 5.与 [RHEL](https://baike.so.com/doc/4813482-5029950.html)的关系

RHEL 在发行的时候，有两种方式。一种是[二进制](https://baike.so.com/doc/1420585-1501617.html)的发行方式，另外一种是源代码的发行方式。无论是哪一种发行方式，你都可以免费获得(例如从网上下载)，并再次发布。但如果你使用了他们的在线升级(包括补丁)或咨询服务，就必须要付费。RHEL 一直都提供源代码的发行方式，CentOS 就是将 RHEL 发行的源代码重新编译一次，形成一个可使用的二进制版本。由于 LINUX 的源代码是 [GNU](https://baike.so.com/doc/5534915-5754984.html)，所以从获得 RHEL 的源代码到编译成新的二进制，都是合法。只是 REDHAT 是商标，所以必须在新的发行版里将 REDHAT 的商标去掉。REDHAT 对这种发行版的态度是:"我们其实并不反对这种发行版，真正向我们付费的用户，他们重视的并不是系统本身，而是我们所提供的商业服务。" 所以，CentOS 可以得到 RHEL 的所有功能，甚至是更好的软件。但 CentOS 并不向用户提供商业支持，当然也不负上任何商业责任。如果你要将你的 RHEL 转到 CentOS 上，因为你不希望为 RHEL 升级而付费。当然，你必须有丰富 linux 使用经验，因此 RHEL 的商业技术支持对你来说并不重要。但如果你是单纯的业务型企业，那么还是建议你选购 RHEL 软件并购买相应服务。这样可以节省你的 IT 管理费用，并可得到专业服务。一句话，选用 CentOS 还是 RHEL，取决于你所在公司是否拥有相应的技术力量。

## 6.版本列表

|      版本       |                           平台                            | RHEL 版本 |   发布日期   | RHEL 发布日期 |
| :-------------: | :-------------------------------------------------------: | :-------: | :----------: | :-----------: |
|        2        |                           i386                            |    2.1    |  2004.05.14  |  2002.05.17   |
|       3.1       |                i386,x86_64,ia64,s390,s390x                |     3     |  2004.03.19  |  2003.10.23   |
| 3.4 - Server CD |                i386,x86_64,ia64,s390,s390x                |    3.4    |  2005.01.23  |       -       |
|       3.7       |                i386,x86_64,ia64,s390,s390x                |    3.7    |  2006.04.11  |       -       |
|       3.8       |                        i386,x86_64                        |    3.8    |  2006.08.25  |  2006.07.20   |
|       3.9       |                i386,x86_64,ia64,s390,s390x                |    3.9    |  2007.07.26  |  2007.06.15   |
|        4        |                    i386,x86_64,various                    |     4     |  2005.03.09  |  2005.02.14   |
|       4.6       | i386,x86_64,ia64,alpha,s390,s390x,ppc (beta),sparc (beta) |    4.6    |  2007.12.16  |  2007.11.16   |
|       4.7       |             i386,x86_64,ia64,alpha,s390,s390x             |    4.7    |  2008.09.13  |  2008.07.24   |
| 4.7 - Server CD |             i386,x86_64,ia64,alpha,s390,s390x             |    4.7    |  2008.10.17  |       -       |
|       4.8       |             i386,x86-64,ia64,alpha,s390,s390x             |    4.8    |  2009.08-21  |  2009.05.18   |
|       4.9       |             i386,x86-64,ia64,alpha,s390,s390x             |    4.9    |  2011.03.02  |  2011.02.16   |
|        5        |                        i386,x86_64                        |     5     |  2007.04.12  |  2007.03.14   |
|       5.1       |                        i386,x86_64                        |    5.1    |  2007.12.02  |  2007.11.07   |
|  5.1 - LiveCD   |                           i386                            |    5.1    |  2008.02.18  |       -       |
|       5.2       |                        i386,x86_64                        |    5.2    |  2008.06.24  |  2008.05.21   |
|  5.2 - LiveCD   |                           i386                            |    5.2    |  2008.07.17  |       -       |
|       5.3       |                        i386,x86_64                        |    5.3    |  2009.03.31  |  2009.01.20   |
|  5.3 - Live CD  |                           i386                            |    5.3    |  2009.05.27  |       -       |
|       5.4       |                        i386,x86_64                        |    5.4    |  2009.10.21  |  2009.09.02   |
|       5.5       |                        i386,x86_64                        |    5.5    |  2010.05.14  |  2010.03.31   |
|  5.5 - LiveCD   |                        i386,x86-64                        |    5.5    |  2010.05.14  |       -       |
|       5.6       |                        i386,x86-64                        |    5.6    |  2011.04.07  |  2011.01.13   |
|       5.7       |                        i386,x86-64                        |    5.7    |  2011.09.14  |       -       |
|       5.8       |                        i386,x86-64                        |    5.8    |  2012.03.07  |               |
|       5.9       |                        i386,x86-64                        |    5.9    |   2013.01    |       -       |
|      5.10       |                        i386,x86-64                        |   5.10    |  2013.10.19  |  2013.10.01   |
|        6        |                        i386,x86-64                        |     6     |  2011.07.04  |  2010.11.10   |
|       6.1       |                        i386,x86-64                        |    6.1    |  2011.12.10  |  2011.05.19   |
|       6.2       |                        i386,x86-64                        |    6.2    |  2011.12.20  |   版本更新    |
|       6.3       |                        i386,x86-64                        |    6.3    |  2012.7.10   |   2012.6.0    |
|       6.4       |                        i386,x86-64                        |    6.4    | *2013-03-08* | *2013.02.21*  |
|       6.5       |                        i386,x86_64                        |    6.5    |  2013.12.01  |  2013.11.21   |
|       6.6       |                        i386,x86_64                        |    6.6    |  2014.10.27  |       -       |
|       7.0       |                          x86_64                           |    7.0    |   2014.7.7   |   2014.6.11   |
|       7.1       |                          x86_64                           |    7.1    |   2015.4.3   |       -       |

## 7.结构

CentOS，也叫做社区企业操作系统，是企业Linux发行版领头羊Red Hat Enterprise Linux(以下称之为RHEL)的再编译版本。RHEL是很多企业采用的Linux发行版本，但是如果想得到RedHat的服务与技术支持，用户必须向Red Hat付费才可以。CentOS的开发者们使用Red Hat Linux的源代码创造了一个和RHEL近乎相同的Linux。但是一切和RedHat有关的商标都被去除了，因为RedHat不允许他们这样做。CentOS是免费的，你可以使用它像使用RHEL一样去构筑企业级的Linux系统环境，但不需要向RedHat付任何的费用。CentOS的技术支持主要通过社区的官方[邮件列表](https://baike.so.com/doc/5567785-5782934.html)、论坛和聊天室。

## 8.安装方式

### **8.1.DVD安装**

1.把刻录好的光盘放到[服务器](https://baike.so.com/doc/4487696-4696885.html)[CD-ROM](https://baike.so.com/doc/5421893-5660084.html).以CD-ROM启动.就会看到如下CentOS欢迎画面，按回车继续安装.

2.接着系统会问是否测试安装光盘，一般按"Skip"即可.

3.等一会，进入图形安装界面，直接按"Next".4.选择语言，选简体中文.按"Next".

5.键盘配置，默认即可.

6.鼠标配置，默认.

7.安装类型,选择"[服务器](https://baike.so.com/doc/4487696-4696885.html)"

8.[磁盘分区](https://baike.so.com/doc/912860-964899.html)设置，建议选择"自动分区".如有需要可以选择手工分区.手工分区方法，"用Disk Druid手动分区",新建分区，系统类型为"swap",大小设置为256(一般为内存的两倍),"固定大小",确定;再新建分区，挂载点"/",文件系统类型"ext3","使用全部可用空间".

9.选择删除系统内的所有分区.

10.磁盘设置，默认.期间可能会警告提示，按确定继续.

11.引导装载程序配置，默认.

12.网络配置. 点击"编辑",会弹出"编辑端口eth0"，不选择"使用DHCP进行配置",按实际情况填写IP和掩码.点击"确定".回到"网络配置"界面，选择"手动设置"，"其他设置"的"网关"和DNS按实际情况填写.

13.防火墙配置，选择"无防火墙".

14.语言支持和时区选择，都默认设置就可以了.(如果选择中文，可能有部分地方会出现[乱码](https://baike.so.com/doc/5132835-5362281.html),所以还是建议大家用英文)

15.设置口令.输入一个不少于六位的口令.并在"确认"那里重新输入一次.记下你的口令，以后登陆系统要用到该口令.

16.选择软件包组，默认设置或者选择"最小安装"都可以.建议选择开发工具前两项.以后使用的时候就方便一些，安装一些软件要用到.

17.设置完毕，可以开始安装了.安装过程为30-60分钟.

### **8.2.uEFI安装**

当硬盘容量超过2TB的时候(大容量硬盘或者Raid)，MBR引导将无法识别多余的容量，此时必须将硬盘转换成GPT引导模式;在GPT格式下安装CentOS需要[主板](https://baike.so.com/doc/292335-309477.html)支持uEFI，一般[智能主板](https://baike.so.com/doc/7899596-8173691.html)均支持。CentOS暂不支持在uEFI上安装(官方 #0004969:DVD ISO 不能自动安装在 uEFI 系统上)。

将磁盘转成GPT格式步骤:首先在启动项那里选中第一项，然后Tab键进入编辑，加上"text"(不带引号，空格text)，回车进入文本安装界面，然后在语言选择后，按Ctrl+Alt+F2进入shell，输入命令/usr/sbin/parted -s /dev/sda mklabel gpt将磁盘转成GPT。

### **8.3.U盘安装**

下面来简单说下使用U盘安装CentOS系统，这里以centos-6.2 i386 minimal为例安装。

**使用到的材料:**

- centos-6.2 i386 minimal
- UltraISO
- U盘一个

**开始安装:**

1、打开UltraISO，依次点击"文件">>"打开"，选择"CentOS-6.2-i386-minimal.iso"文件。

2、"启动">>写入硬盘映像"，在"硬盘驱动器选择u盘"，[写入方式](https://baike.so.com/doc/4546440-4756850.html)默认即可，点击"格式化"格式u盘，最后"写入"即可完成。

3、完成写入后，只保留"images"和"isolinux"两个文件夹，其余的全部删除，然后复制CentOS-6.2-i386-minimal.iso到u盘根目录。

4、重启以[u盘启动](https://baike.so.com/doc/787517-833215.html),选"Install or upgrade an existing system"回车，语言选择"Chinese(Simplified)"回车，选择键盘模式，默认，然后回车。在下一步"Installation Method"选择"Hard drive"，然后选择u盘所在的分区(不确定的可以一个个尝试)。下面就是常规的系统安装了。

### **8.4.硬盘安装**

**必备工具**

- CentOS 6.2 ISO文件
- Paragon-Partition-Manager:用于在xp下ext2或ext3的分区
- grub4dos:用于引导linux系统
- Ext2Fsd:用于windows下能读写ext2或ext3分区

安装步骤

**1、ext3分区**

使用Paragon-Partition-Manager分出一个ext3的分区，这个分区是用来存在iso文件的，大小根据iso文件确定，分区之后，硬盘还必须有未分区的空间，因为需要给安装CentOS留下。分区的时候顺便分配盘符。

使用Ext2Fsd访问ext3分区

安装打开ext2fsd软件，在刚才分好的ext3分区上右键，选择"配置文件系统"，点击"启用"，之后"更改并退出"。这时后就可以打开[我的电脑](https://baike.so.com/doc/686748-726866.html)，并看见已经多了一个[磁盘分区](https://baike.so.com/doc/912860-964899.html)，比如F。接着把iso文件复制到F分区的根目录，

**2、用grub4dos**软件制作引导菜单

打开[我的电脑](https://baike.so.com/doc/686748-726866.html)C盘，工具–[文件夹选项](https://baike.so.com/doc/6676853-6890722.html)–查看，在"隐藏受保护的操作系统文件(推荐)"前面的勾去掉，并选中"显示所有文件和文件夹"，再把"隐藏已经文件类型的扩展名"前面的勾去掉，最后点击应用，确定。

右键单击C盘根目录下的boot.ini，选择"属性"，把"只读"前面的勾去掉。接着，用记事本打开boot.ini文件，在最后一行添加如下内容:

**C:\GRLDR="Grub"**

解压grub4dos-0.4.4,把文件夹里面的GRLDR复制到C盘根目录。然后在C盘根目录新建boot文件夹，在boot文件夹中再建grub文件夹，把grub4dos-0.4.4文件夹里面的menu.lst复制到C:\boot\grub下。

然后解压挂载或解压iso文件，把里面的isolinux文件夹复制到F盘的根目录下面。

**3、引导CentOS启动**

重启电脑，进入引导界面，选择Grub，按下"C"键进入命令行模式。

输入"root (hd0,"(双引号不用输)，这时按下"Tab"键，会在下面出现整个硬盘的所有分区,假如我们看到 "5"对应之前的ext3分区，那就继续输入"5)"，完整的命令是:root (hd0,5)。

按下[回车键](https://baike.so.com/doc/5383749-5620150.html)，继续输入kernel /isolinux/vmlinuz，再按下回车，输入initrd /isolinux/initrd.img,按下回车，继续输入boot，按下回车，这时grub已经能够引导centos进入安装界面。

**4、**

这里不多说，需要注意的有几点:

1、在要求选择CentOS image文件所在的分区时，一般选择最后一个分区。

2、这步一定要小心，不然会导致windows系统丢失。在提示"您要进行哪种类型的安装"时，选择"创建自定义布局"进行自定义分区，然后在未分区的空间上新建ext4分区，也可以使用LVM管理分区，不过boot必须是主物理分区。