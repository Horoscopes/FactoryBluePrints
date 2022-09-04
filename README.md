# 戴森球计划 工厂蓝图

## 简介

这是游戏[戴森球计划](https://store.steampowered.com/app/1366540/_/)中的蓝图仓库，用于储存与分享来自社区的工厂蓝图  

蓝图主要由**小马蓝图群**成员与**CIDT设科院**成员贡献。为了对来自社区的庞大数量的蓝图进行分类、管理、储存与分享，我们打算将蓝图上传到github作为交流群文件的备份，并且将来可能进一步建设成为蓝图网。

您可以加入交流群并将蓝图上传到群文件，我们将不定时将群文件中的蓝图分类上传到仓库中，如有遗漏可以在群里提醒我们。您也可以通过pull request的形式直接投稿，请根据蓝图功能投稿到最合适的文件夹。您可以通过这些方式联系我们：

```text
914523440（小马蓝图5群）
611954295（小马蓝图4群）
342139527（小马蓝图3群）
949098605（小马蓝图2群）

150369431（CIDT学院群）
```

---

## 蓝图仓库使用方法

视频使用教程：https://www.bilibili.com/video/bv1RK411Z7b2  

### 基础用法

您可以直接进入[蓝图仓库的网页](https://github.com/DSPBluePrints/FactoryBluePrints)，寻找并打开自己需要的蓝图文件，点击位于蓝图代码右上方的**全选复制**(Copy raw contents)。  
然后进入游戏，在蓝图页面依次点击**新建空蓝图**，**粘贴**，**保存更改**，就可以将蓝图代码保存到本地，像平常那样使用。
> 常见问题：  
> Q: 为什么蓝图仓库网页打开特别慢，我该怎么办？  
> A: 蓝图仓库被托管在github上，可以通过在[Watt Toolkit](https://steampp.net)(原名steam++)中开启github加速服务解决。~~或者魔法？~~

### 进阶用法

如果您有[Git](https://git-scm.com/)的使用基础，可以将整个蓝图仓库用`clone`命令拉取到游戏的蓝图文件夹内(约300mb)。这样您将以蓝图合集的形式将完整的蓝图仓库下载到本地，**并且可以在游戏内直接访问**，享受在线蓝图仓库与游戏无缝衔接的体验。  

```cmd
git clone https://github.com/DSPBluePrints/FactoryBluePrints.git
```

可以通过`pull`命令进行对本地蓝图文件夹进行更新。Git将自动检查上次更新以来发生变动的蓝图/蓝图合集，并以增量更新的形式更新本地仓库(约1-5mb)  
**或者直接双击仓库根目录下的"双击更新蓝图仓库.bat"**  

```cmd
git pull origin main
```

---

## 常用蓝图 (点击打开所在文件夹)

极地小太阳: [极密铺极地小太阳](./电力系统/极密铺极地小太阳)  
全球3.2w白糖：[4015白糖每分钟(八分之一球)](./原矿黑盒/白糖)  
全球270k增产剂：[13.5k增产剂mk3（二十分之一）修复](./原矿黑盒/增产剂mk3)  
全球432k太阳帆：[21.6k太阳帆（二十分之一）](./原矿黑盒/太阳帆生产)  
全球5600小火箭：[火箭281.3](./原矿黑盒/火箭生产)  
全球锅盖：[5806全球锅组合包](./射线接收/5806全球锅组合包)  
全球弹射器: [全球密铺电磁轨道炮4000炮](./造球打帆射火箭)  
全球火箭发射: [火箭发射1.88w](./造球打帆射火箭)  

仙术八重大矿机：[钛极八矿图](./采矿/钛极八矿图)  
