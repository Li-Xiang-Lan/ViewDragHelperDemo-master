# ViewDragHelperDemo
利用ViewDragHelper 打造一个可拖拽下拉关闭/左右切换的页面。

博客地址： [ViewDragHelper （三）- 打造仿陌陌视频播放页（深入篇） ](http://blog.csdn.net/qq_22393017/article/details/78472492)

#### QZone QQ空间的效果：

![QZone](https://github.com/xiaosong520/ViewDragHelperDemo/blob/master/Gif/QZone.gif)

#### MoMo播放页的效果：
![Momo.gif](https://github.com/xiaosong520/ViewDragHelperDemo/blob/master/Gif/Momo.gif)

#### demo实现的拖拽效果：

![效果图一](https://github.com/xiaosong520/ViewDragHelperDemo/blob/master/Gif/dragview_horizontal.gif)

#### demo真机演示效果：

![效果图二](https://github.com/xiaosong520/ViewDragHelperDemo/blob/master/Gif/dragview_vertical.gif)

### 主要的功能点有如下几个：
1. 滑动方向判定。
2. 单个方向的拖拽限制。
3. 事件分发以及拦截。
4. 平移动画处理。
5. 下拉时缩放及背景透明处理。
6. 背景高斯图片替换处理。
7. 嵌套ScrollView / RecyclerView事件冲突处理。
8. 多点触控 Invalid pointerId 问题解决。
