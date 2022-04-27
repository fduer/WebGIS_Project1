# WebGIS_Project
## 项目背景
> todo
## 项目描述
### 概述
*待命名*（下称本应用）是一个完全在线的GIS系统，用户可用其来收集、组织、管理、分析和发布地理信息。本应用可在任何地点通过桌面端 web 浏览器使用。本应用可以发布地理信息，以供所有人访问和使用。
#### 功能
 - 用户可以上传地理信息数据，或访问在线资源库以获取公开数据，或提供URL以访问位于其他服务器上的数据。
> 注1：一般来说用户系统（即账号体系）需要数据库的相关知识。如果不考虑安全性，也可以不使用数据库，只使用文件系统。有人租了服务器最好，没有也可以申请一些限时的服务器。或者谁的空闲电脑可以24小时开机……
 - 用户可以组织、管理所有拥有访问权限的地理信息数据，也可以指定格式导出到本地。
 - 用户可以对数据进行在线的处理、分析、查看。
 - 用户可以发布地图数据，以URL的形式分享或嵌入到自己创建的网页应用中
### 架构
本应用由三个模块组成。
1. 前端；
2. 数据存储，即上面提及的三类数据；
> 注2：即使不使用数据库，也不使用账号，也需要设计数据存储形式。
3. 数据分析处理。
> 注3：这部分发挥比较自由，毕竟是demo性质的项目，看别人库里有什么工具调用就行。
## 项目实现
### 前端
#### 界面
参考Outlook web端：  
![Outlook](https://github.com/OrkWard/WebGIS_Project/blob/main/assets/image/Outlook.png)  
出色的办公web应用，标准的导航栏-工具栏-复合工作区组合，是web应用的优秀范本；  
参看ArcGIS Online：  
![ArcGIS Online](https://github.com/OrkWard/WebGIS_Project/blob/main/assets/image/ArcGIS%20Online.png)  
通过下拉按钮在功能间切换，尽可能把更多的空间让给地图展示，也是一种很好的展现形式；  
参考Google Earch Engine：  
![gee](https://github.com/OrkWard/WebGIS_Project/blob/main/assets/image/Google%20Earch%20Engine.png)  
屏幕长宽比过大时视觉效果非常糟糕，导航栏还格外宽…… 长宽比较小时尚可接受
![ArcGIS Online](https://github.com/OrkWard/WebGIS_Project/blob/main/assets/image/Google%20Earch%20Engine_2.png)  
> 注4：这个三行三列的UI设计并不推荐。

> todo
#### 功能
> todo
#### 数据可视化
> todo
### 后端
#### 数据存储
> todo
#### 数据导入/格式转换/导出
> todo
#### 矢量数据处理
> todo
#### 栅格数据处理
> todo
## 开发环境
浏览器：Chrome 88+ / Edge 88+ / Firefox 86+
> 注：待议。Firefox内核非Chromium，如果增加支持每次需要在至少两个浏览器上测试通过，Chrome和Edge以完全相同看待。由于不是所有人都有Mac，所以不对Safari进行支持。

> todo

> todo...
