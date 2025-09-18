## character-control(跑酷3D角色控制)

3D物理跑酷游戏，模拟角色真实的上坡、下坡遇到的技术问题，提供解决方法。

## 开发环境
- 引擎版本： Cocos Creator 3.6.2
- 编程语言： TypeScript
- 物理采用的是 bullet 引擎
- 角色选择的是胶囊碰撞体
- 地图道路模型使用网格碰撞体

## 游戏介绍
触摸屏幕，控制角色在跑道上左右移动

## 功能实现

演示场景技术要点

**convex-mesh-issue** 是解决采用凸包的方案平行道路和斜坡处容易产生一个很明显的接缝，人物会出现跳跃悬浮问题。

![](https://download.cocos.com/Cocos/CocosStore/ManualUp/2989/image/3.gif)


**pile-rigid-issue** 场景演示障碍物刚体堆叠的处理方案，当使用刚体的砖块堆叠后，因为砖块尺寸较小造成不受力时会出现移动掉落问题。

![](https://download.cocos.com/Cocos/CocosStore/ManualUp/2989/image/2.gif)

**static-mesh-issue** 场景针对使用静态网格时，bullet返回碰撞信息出错造成偏移和抖动的问题。

![](https://download.cocos.com/Cocos/CocosStore/ManualUp/2989/image/1.gif)

详细教程文档，请关注COCOS官方公众号。

## 联系作者

可在本商品页面下方留言回复

也可在 [Cocos论坛集中帖](https://forum.cocos.org/t/topic/116334)讨论

## 版权声明
本资源为 Cocos 引擎 Demo Team 组官方出品，您可以将工程中的代码、模型资源用于自己的项目或二次商用。