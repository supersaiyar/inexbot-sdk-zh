# Ubuntu 18.04 安装

本文详细说明 Ubuntu 18.04 的下载、通过 VMware Workstation 创建虚拟机、安装配置以及 VMware Tools 安装的全过程。

## 1. 下载 Ubuntu 18.04

从 Ubuntu 官方或国内镜像站下载 Ubuntu 18.04 LTS 的 iso 文件。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/nWUznSqnZxXndpG0MDYMzCsQs9jJkAzL1LikCjcAw-E.png)

安装好之后如下：

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/jWzpvxVfX7FMLwBpRda5YjgzDKK2Ez2TPUo2zrsvGoM.png)

## 2. 创建虚拟机

### VMware 配置步骤

1. 打开 VMware Workstation，点击 **创建新的虚拟机**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/3Hv9EBgFj194ZU8vY5PQ3hodVM_LIsCyHI09Juke6kI.png)

2. 选择 **自定义（高级）**，然后点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/qBeGYDBv7y8qhWl_FcKodbFupvmUgs3yZAJ9LG-qShE.png)

3. 根据安装的 VMware 的版本号，选择硬件兼容性，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/NWvtAcOxikQ0ErtJFCJGjS6vtZGLm7dj8ENpkgkCSpg.png)

4. 选择 **稍后安装操作系统**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/TzTwI4PlSOJSplTzxn24JQk4b5Dd6uZfBXnyAB5enig.png)

5. 选择 **Linux**，版本为 **Ubuntu 64位**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/t0XXfxuiuR5gHrED1Oro7XROK_JsqMDTXzvt8HMYv6g.png)

6. 自己命名，选择安装位置（最好不要安装在 C 盘）。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/e2ryUyEC73E0SA7RFbHAu__G3m7VKTzJtjDJqI0Ps0o.png)

7. 处理器数量选择 **1**，内核数量选择 **4**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/XUmZUXnqzMV6_s_L0HubTeRBxY9BXnpdh2S-BjQaBCk.png)

8. 内存选择 **8GB**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/kRzPc8embfid43i-QhuFXYHO8M4JpHDe4UeRaDNka9s.png)

9. 选择 **使用网络地址转换**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/CqO1ra2HfwusNpwpRaB6TztPfr0GXQB2DLRkerMoTT0.png)

10. 按默认推荐配置，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/8W5FT5Xsy8X5BPq4mEzxzVyLXKetOwkXk-gh2jpIJS4.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/l0M8MCk5yJcsH8ier7y3YqizA7fYWmQB30GNkf0acPw.png)

11. 选择 **创建新虚拟磁盘**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/GsllZ__Bjy7iaY2Xd0UCf-o8B7RbEc9Ul9sPnlju7aI.png)

12. 分配磁盘，推荐 **80GB**，可根据实际需求调整，选择 **将虚拟磁盘拆分为多个文件**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/d4uKlYmlTXyDiQxn0uOZEyzJoKMLZu64WUEY7ff8b-M.png)

13. 默认，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/D1SQGO4yv_VAmOXk5TszTatnzbAZBzX7a4oKQi6qy4w.png)

14. 点击 **自定义硬件**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/RqBxR4z2ygosgcqDAJwnTmvfhV_DPY6xu_fKPaO37FY.png)

15. 进入自定义硬件，使用 **ISO 映像文件**，选择一开始下载的 iso 文件，移除 **声卡** 和 **打印机**，然后点 **关闭**。因为用不上虚拟机的声卡和打印机，关闭以节省资源。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/2-06AbzdY9zpd0A4GL3Uh3-Wrb8dwRXRY0Z6vvryUqY.png)

16. 点击 **完成**，开始安装。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/lOZF5jqKMMzLzl9usaA_7i8A4BLuSPIIY84bJmhsUEc.png)

## 3. 安装 Ubuntu 18.04

1. 进入 Ubuntu 18.04，开启此虚拟机。选择 **中文（简体）**，点击 **安装 Ubuntu**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/sPUkp9UJX607H3bU0IW48plk2kbN31VhGyyztSfgA04.png)

2. 选择 **汉语**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/biKG5REg2Y3Ky5UP57ABlk7zSkTShgugxK9JiRQHryk.png)

3. 选择 **正常安装**，**安装 Ubuntu 时下载更新**，点击 **继续**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/-mssWiCUpKssGwYRhESgyCJ5TPZb_4dwEbC-_4dMPck.png)

4. 选择 **清除整个磁盘并安装 Ubuntu**，出现提醒选择 **继续**，最后点击 **现在安装**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/3yxq0NzNRSTEiufsnpLybufV1Zgzsfc4B2tGY_-Resc.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/XcF_VZro-QDAOw2lML1XWNPTKH6Gc12N1ft2CzcV9-Q.png)

5. 自己设定好用户名以及密码，地区可以随意填，等待 Ubuntu 自己安装即可。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/lyVaRPiv5LZqmzknWt_RtWNEkqT9I87OPX3_CKXNoRc.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/T3X-_U9btKmQEAcIXFO-Op2wOIuBMJPmaa9f65-nAgE.png)

## 4. 安装 VMware Tools

安装好 Ubuntu 后点击现在重启，进入 Ubuntu，安装 VMware Tools。

### 挂载 VMware Tools

1. 点击上方 **虚拟机**，点击 **安装 VMware Tools**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/2AEEj7wy7mnyAfZ_R2C1m6f-U7Q_NEgfX0_3epYJq9o.png)

下载完成如下：

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/E2aijBGePuNW_orQp0Qm2M_KFxu2eyl_X9xGi_nvbQA.png)

2. 在文件—VMware Tools 中找到这个文件夹，把文件夹移入主目录。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/2IruT2aPoRpt28HvmP1g0L_K-BSA0DDVyA6oR9_IPyM.png)

3. 在主目录中点击右键，点击 **在终端打开**，运行以下命令：

```bash
tar -zxvf VMwareTools-xxx.tar.gz
```

运行后即可发现文件夹已解压：

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/K3sJQPG5/resources/ffZP7q0RQIj4qrb02N4nRHRxKu99tcpUjmN_v7ZJ13E.png)

4. 运行以下两条命令：

```bash
cd vmware-tools-distrib
sudo ./vmware-install.pl
```

除了第一次停顿时输入 `yes`，其他停顿都按回车即可。

之后重启；至此，Ubuntu 18.04 安装完成。
