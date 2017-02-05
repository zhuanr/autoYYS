# autoYYS
阴阳师副本自动化研究

## 安全性
完全模拟手势，无任何数据包处理、不修改应用。对于用户角色非常安全。

## 前提条件
1. 开启Android模拟器，如BlueStack、BigNox
2. 启动阴阳师，将画面切换到探索场景（大地图）
3. 目标剧情以解锁（普通或困难）
4. 设置剧情菜单位置
5. 勾选锁定出战式神
6. 队伍实力可以稳定通关
7. 剩余体力充足

## 难点
1. 无法获取当前的场景和状态，只能通过有限的手势操作，实现副本自动化。
2. 当手势操作和当前场景不匹配时，可能进入并且卡在未知的状态。

## 自动化基本思路
通过模拟手势操作，进入副本，攻击怪物，离开副本，再进入副本，以此循环。

1. 在探索副本大地图中，点击目标剧情副本
2. 在弹出对话框中，点击确认，进入剧情副本
3. 主角自由移动，或者拖动场景
4. 寻找并点击怪物图标，攻击怪物
5. 自动战斗
6. 胜利后，画面显示当前人物经验
7. 点击后，红色素材显示，并提示点击屏幕继续
8. 再次点击，显示获取的物品
9. 继续点击屏幕，切换到副本场景
10. 如果地图上还剩余怪物（包括BOSS），跳转到步骤3
11. 副本的BOSS打完后，小纸人呈上若干宝物
12. 点击图标，拾取所有宝物
13. 画面自动回到探索副本大地图
14. 跳转回步骤1


## 场景分析

场景宽度

地平线

剧情菜单

确认对话框

