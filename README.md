# TreasureHunt ![License](https://img.shields.io/github/license/mashape/apistatus.svg)
　　一个类似扫雷的数字解密游戏。
　　
## Cover
![](https://github.com/Sandigle/TreasureHunt/raw/master/image/cover_1.jpg)![](https://github.com/Sandigle/TreasureHunt/raw/master/image/cover_2.jpg)  

## Background Story
　　伟大的海贼王罗伊帕·凡·蒙特里安一生荣华富贵，他死后将所有财宝都藏在了一片深邃的大海中，并设下重重机关。落迫冒险家皮特·罗莉安为了振兴家族，穷尽毕生资源购置了搜寻装备，来到了这片不归地。究竟是海贼王的荣耀永存，还是冒险家的事业腾飞，就看玩家的选择。

## Points
- 目标：在有限的生命内找到地图上所有`宝藏`。
- 关键：处于左边和上边的冒险家装备显然不够格，它只能显示每行/列的`宝藏`分布情况。从左往右或自上而下，数字的值表示有几个`宝藏`连续排列，数字的个数表示有几段`宝藏`不连续排列。如“2 3 3”，表示该行分布了3段`宝藏`，从左往右分别是2/3/3个`宝藏`连续排列，每段`宝藏`之间至少有一个`炸弹`。
- 难度：在中低难度，几乎所有`宝藏`都可由提示唯一确定。而在高难度，`宝藏`一定无法由提示唯一确定。所幸冒险家福大命大，一次爆炸伤不到他的性命，他有足够的机会重新爬起。
- 评价：使用Logistic模型，目前只根据通关时间作为唯一标准进行评价。总体越快评价越高。

## Dependencies
- 运行程序至少装有Java Version 8 Update 101。
- 编译程序额外需要JMF 2.1.1e。

## Unresolved Issues
　　以下问题难以解决，请求高人指点。
- 点击不够灵敏。
- 地图难以填充整个中心区域。
- 切换难度时需要点击2次，且有杂质图像残留。

## References
- 所用贴图来自《win7扫雷》。
- 所用音效来自《洛奇mabinogi》。
