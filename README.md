# 外星人小游戏

这只是是一个简单好玩的外星人小游戏

## 环境要求

√ Python3及以上

√ pygame最新版
```bash
pip3 install pygame
```

√ pynput最新版（非强制，可不装）
```bash
pip3 install pynput
```

## 使用方法

启动游戏：

```bash
python alien_invasion.py
```
游戏控制：

← → 方向键：控制飞船移动

空格键：发射子弹

P 键：开始/重新开始游戏

ESC 键：退出游戏

在游戏中可按`pause`键暂停或恢复

按`p`开始/重新开始

按`esc`退出

游戏特色
经典的太空射击玩法

智能的外星人行为

保护盾牌系统

外星人也会反击射击

持久化最高分记录

可调整的游戏难度

游戏规则
控制飞船躲避外星人和子弹

发射子弹消灭外星人获得分数

每关难度会逐渐增加

初始有3条生命，耗尽游戏结束

能量系统支持特殊攻击功能

**Q**：出现如下报错
```bash
Traceback (most recent call last):
  File "alien_invasion.py", line 1, in <module>
    import pygame
ModuleNotFoundError: No module named 'pygame'
```

> **A**:pygame未安装，请尝试如下命令
> ```bash
> pip3 install pygame
> ```
> 
文件说明
核心文件
alien_invasion.py - 主游戏文件

settings.py - 游戏设置

ship.py - 飞船类（含能量系统）

alien.py - 外星人类

bullet.py - 子弹类

新增优化文件
particles.py - 粒子效果系统

background.py - 星空背景系统

shield.py - 能量盾牌系统

alien_bullet.py - 外星人子弹

scoreboard.py - 计分系统（含能量条显示）

自定义设置
可以通过修改 settings.py 文件调整游戏难度：

飞船移动速度

外星人移动速度

子弹发射频率

屏幕尺寸等


