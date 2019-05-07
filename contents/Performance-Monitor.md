# 阿里云应用实时监控服务 ARMS
## 前端监控
[阿里云前端监控官方文档](https://help.aliyun.com/document_detail/58652.html?spm=a2c4g.11186623.6.599.10842f4dAf47St)

## 监控范围
 - Web 端体验数据监控
 - 页面打开速度（测速）
 - 页面稳定性（JS Error）和外部服务调用成功率（API）

### 特点
ARMS 前端监控平台重点监控页面的加载过程和运行时状态，同时将**页面加载性能**、**运行时异常**以及**API调用状态**和**耗时等数据**，上报到日志服务器。之后借助阿里云中间件平台 ARMS 提供的海量实时日志分析和处理服务，对当前线上所有真实用户的访问情况进行监控。
![直观的报表](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/152257/155496244543325_zh-CN.png)

## 一键接入AMRS
[操作视频](https://cloud.video.taobao.com/play/u/2997715671/p/1/e/6/t/1/50018708973.mp4)
[创建一个应用站点](https://arms.console.aliyun.com/?spm=5176.6660585.774526198.1.9e686bf8wq3Ean#/retcode)
[支持针对 Web 场景、Weex 场景和小程序场景的监控](https://help.aliyun.com/document_detail/106086.html?spm=a2c4g.11186623.6.601.24cd4960pxCM9z)

# ARMS管理控制台
[登陆地址](https://arms.console.aliyun.com/?spm=a2c4g.11186623.2.13.3295186bhce0TD#/home)

## 控制台功能
### 页面访问速度
瀑布图按照页面加载的顺序，直观地展示了各阶段的耗时情况。**根据指定时间段内指定指标的平均值数据，采取针对性的优化性能方案。**
![页面加载瀑布图](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/152271/155496244943557_zh-CN.png)

### 慢会话追踪
提供页面加载过程中静态资源加载的性能瀑布图，帮助您**根据页面性能数据详细了解页面资源加载情况**，并**快速定位性能瓶颈**
**不同时间段页面完全加载的用时**
![访问速度](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/152272/155711204443617_zh-CN.png)
 通过**页面资源加载瀑布图**快速定位资源加载的性能瓶颈
![资源加载瀑布图](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/152272/155711204543621_zh-CN.png)

### 前端监控实时大屏
一次性查看被监控应用的所有关键实时监控数据
[展示流程](https://aliware-images.oss-cn-hangzhou.aliyuncs.com/walkthrough/arms-bm-dashboard.html?spm=a2c4g.11186623.2.13.53ba5362wajkeX#/)

### JS 错误统计

### JS 错误诊断
[操作流程](https://aliware-images.oss-cn-hangzhou.aliyuncs.com/walkthrough/arms-bm-js-error-diagnosis.html?spm=a2c4g.11186623.2.15.5fc86ae4Y08Gt1#/1)

### API 请求监控
### 自定义统计
### 前后端链路追踪

# 对比微软insight监控工具 （待进行）
### 功能对比
[微软insight监控工具](https://docs.microsoft.com/zh-cn/azure/azure-monitor/app/javascript)

### 费用对比

<!--
## 腾讯云前端性能监控
[简易入门](https://cloud.tencent.com/developer/news/301840)
-->
