# Ubuntu 22.04 安装

本文介绍通过 VMware 安装 Ubuntu 22.04 虚拟机的完整步骤。使用清华大学开源镜像站下载镜像，安装时可省去手动换源的步骤。

## 下载镜像

从清华大学开源镜像站下载 Ubuntu 22.04 LTS 镜像：

https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/22.04/

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/FVHuHp2D_gFGvdRmefAEoa8EbsPl_CpLY9KllpVA7Jw.png)

## 创建虚拟机

### VMware 配置步骤

1. 打开 VMware，点击 **创建新的虚拟机**，开始配置虚拟机环境。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/F5tonq86wR6-IpOsMQGk0EZfAKQFL0cl7d6itmtBwX4.png)

2. 选择 **自定义（高级）**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/2HgpTVG5NjbqXJ3GR2IhCXz1qzv6AdWiLfRgBOvppcw.png)

3. 根据 VMware 版本选择硬件兼容性，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/Ig8vfMDuKoNYoqVC0ICwEagqi96Nfy1PuGWFh8Q9UVA.png)

4. 选择 **稍后安装操作系统**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/zJBdXmTNp5FhOxEkPIQJWKct1Qc5k_QkQiG3fVPQXkM.png)

5. 选择 **Linux**，版本选择 **Ubuntu 64位**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/G7Wf_5PsIHPSedePfujNwV2qVSdK_E3ed9ZB3jwh2iA.png)

6. 设置虚拟机名称和安装位置（建议不要放在 C 盘），点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/hWNKhkR4cTNORy1wviliKVdCuVtGAOBj7AoLij6wZWM.png)

7. 设置处理器数量和内核数量，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/475BRLYNRBFwiKxvn5Js0y8gTOsO15ywoNCk4vNx3Dw.png)

8. 配置内存（建议 4GB 以上），点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/IXG3tXiDP4m0cLgv_1xXoVqC7geX6uzDr-Ijd5sz4TA.png)

9. 选择 **使用网络地址转换（NAT）**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/zhsRV6mLp40VMAty41UzxzUSoSyMIwFbRifOG3vn7jY.png)

10. 按默认推荐配置，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/V53T3GKDzi2owpZCpPKeUZCZrEpN7RFqr-2txtqw3bA.png)

11. 选择 **SCSI（S）**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/HwWw941DVOJ-F8X4Tr1mhlQw5xZCEb_bYL_FsK0puxI.png)

12. 选择 **创建新虚拟磁盘**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/aOuKQj6NnspAS6WyJk55mf8oAbHj9zcd6s8wCdXzHSI.png)

13. 分配磁盘容量（推荐 80GB，可根据需要调整），选择 **将虚拟磁盘拆分为多个文件**，点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/-TNkU8cxC0ztG0_vUUQZlL4TQgnboAJeg5EYaOTp0Yk.png)

14. 点击 **下一步**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/E2gmJPuyeQkgyedLM1HWbeReQKuUns-RKNmNef0SrZQ.png)

15. 点击 **自定义硬件**，移除打印机（节省资源）。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/furon5YVAbtWot-Ags8H6kFOpTWCELFnxJFqgIJQweQ.png)

16. 选择 **新 CD/DVD (SATA)**，点击 **使用 ISO 映像文件**，浏览并选择下载好的 Ubuntu 镜像文件，然后点击 **关闭**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/vWBO0yjUz3vPfU3nEQQssycYcD0W7GcbWe1yn5_G_f8.png)

17. 点击 **完成**，然后点击 **开启此虚拟机**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/Yc03u55hQgU3oTXEJ8BvUTWRSNRthBiYuWVRo7nwpyk.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/DCkqmKS468MLy0ANdkrg59OBXKYK1j3yq2KXje4ig0U.png)

## 安装 Ubuntu 22.04

### 启动虚拟机

1. 选择 **Try or install ubuntu**，按回车。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/9M8ecjgPmn2rdaaHDY7DI_iecqZlLJTMYIP87IQGAT4.png)

2. 左边下拉选择 **中文（简体）**，点击 **安装 Ubuntu**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/HLkUFNuUBniThysXqGUjh7qJU0dAcPi-fs8LlWqrbng.png)

### 配置安装选项

1. 点击 **继续**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/FJ0dIWdwiJZ4NQ4xFElXzfHNGZ3daI3t1wPtk_3z3MU.png)

2. 选择 **正常安装** 或 **最小安装**，点击 **继续**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/0wI_MvwML6E6B_zd2-QO_2LYY0JQrkz-KcwzSB-Bxv8.png)

3. 选择 **清除整个磁盘并安装 Ubuntu**，点击 **现在安装**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/LkB7D9CCWnB0LbSLlHPd6Tc_pr9oEHDMLJDvX0-1EUA.png)

4. 点击 **继续**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/Id-1IYpRczhm7gBJnRuRd3vVqgsIDDGTDTTL-lqAp6A.png)

5. 点击 **继续**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/GUVAeasVEcteL8dDwO5HjPrzxiUaAcba9RNTPzU6LtE.png)

6. 设置用户名和密码，点击 **继续**，等待安装完成。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/c4T6EBvX_fjHrkumtPeXBH4XjTotvS2HW_2n030o4nU.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/8iXNRVw_1Z_a4VxhJQV0Mu9iVJTEVFJVJJhDXeQoGIA.png)

### 初始配置

1. 重启后点击 **跳过**。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/pI4cYG06gL80qnTwpuUvee8DfI_XAduavpgy1Xec6ac.png)

2. 后续几步根据提示点击前进，最后点击 **完成**。若弹出提示框，点击 **稍后提醒** 即可。

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/SXARKDd3OvBZC7CPdneZLt0EPYGOqSu9qq4a67PZjWo.png)

![](https://ones.inexbot.com/wiki/api/wiki/external-editor/RnqpQ1Yp/T3gJgLYw/resources/Ls4iWapgLLtE7jDjsV9yAVbqOD6AvgpLcz3pYV3Gyeg.png)
