---
title: "自定义监控"
description: test
draft: false
---

自定义监控的功能支持，可满足青云已有用户、非青云用户对基础资源的指标监控需求，可与CloudSAT服务内的其他功能结合使用，形成完整的立体化监控告警服务。

## 自定义监控操作步骤
如果您需要使用自定义相关功能，请按照下述步骤进行。

1. 上报监控数据

登陆控制台，点击「自定义监控」导航入口，进入自定义监控页面创建自定义监控。按照初始页面的提示，进行数据上报工作，上报数据请参照[自定义监控上报数据规范](../upload_monitor_data)
进行上传。

创建自定义监控如下图所示：

![](../_images/创建自定义监控_20201102102144.png)

在界面上，按照弹框内的提示进行信息填写，创建成功后即可，如下图：

![](../_images/创建自定义详情_20201102102405.png)

创建成功提示

![](../_images/自定义监控创建成功_20201102102644.png)


2. 统一管理自定义上报数据

自定义监控界面会汇总所有用户自主创建过的命名空间，各个命名空间之间相互独立，但可以在一个界面上统一管理，如下图所示：

![](../_images/统一管理自定义上报数据_20201102102921.png)

3. 管理各组空间内的自定义指标
除了统一管理之外，也可进入到某一个具体的空间内，对该空间内的、自主上报的指标进行统一的管理。若还未上报数据，则可看到如下空白页面：

![](../_images/各组空间内的自定义指标.png)

若用户已经完成上报了来自其他平台的基础监控数据，则会在指定的空间详情页面内展示出来，这些指标的各类关键信息，如下图所示：

![](../_images/自定义命名空间详情.png)

在上表内，可以对异常的监控指标进行直观的显示，如下图所示：

![](../_images/自定义监控异常指标显示.png)

4. 细查异常监控数据
 (1)若需要对异常情况进行下钻与细查，可以点击指标所在列，进入该这指标的监控详情视图页面，如下所示：
 
![](../_images/自定义指标监控详情.png)

（2）平台也支持对自定义监控数据的配置修改，可按照实际业务需求灵活调整统计方式、命名等信息，如下图所示：

![](../_images/自定义监控数据的配置修改.png)

5. 查看告警信息
除了对监控数据的展示之外，该功能页面也支持对「告警规则」的统一汇总与查询，如下图所示：

![](../_images/查看告警信息.png)