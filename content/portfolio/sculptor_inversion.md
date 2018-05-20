+++
showonlyimage = false
draft = false
image = "img/portfolio/sculptor_inversion_title.png"
date = "2018-05-16T23:29:39+09:00"
title = "雕刻家：反转"
weight = 5
+++

智力解谜游戏（制作中）
<!--more-->

**平台：**iOS,Android<br>
**技术：**Unity

玩家将扮演一个雕刻家，在每一关会得到一个草图(2D)，还有一堆方块(3D)。玩家通过消除方块，
并改变角度，使这些方块在某个角度看起来是草图的样子（玩家的视角可以在2D和3D之间切换）。
另外，这些方块拥有称为“反转”的特性，增加游戏的复杂度，同时也增加了游戏乐趣。

基本玩法：

![base](/img/portfolio/base.gif)

规则1:【视觉反转】

某些方块在3D和2D下的颜色是补色。

![3D2D_inverse](/img/portfolio/3D2D_inverse.gif)

规则2:【生死反转】

某些方块被消除后会产生补色的方块。

![child_inverse](/img/portfolio/child_inverse.gif)

规则3:【区域反转】

某些方块被消除后会使相邻的方块变成原来颜色的补色。

![field_inverse](/img/portfolio/field_inverse.gif)