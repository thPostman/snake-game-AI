# Python贪吃蛇游戏

这是一个使用 Python 和 Pygame 库开发的经典贪吃蛇游戏。

## 游戏特性

- 使用方向键控制蛇的移动
- 吃到食物会增加蛇的长度和分数
- 碰撞检测：撞到自己会重置游戏
- 无边界：蛇可以穿过屏幕边界
- 实时分数显示

## 安装说明

1. 确保已安装 Python 3
2. 安装依赖：
```bash
python3 -m pip install -r requirements.txt
```

## 运行游戏

```bash
python3 snake_game.py
```

## 游戏控制

- ↑ 向上移动
- ↓ 向下移动
- ← 向左移动
- → 向右移动

## 游戏设置

可以在 `snake_game.py` 中修改以下参数来自定义游戏：
- `WINDOW_WIDTH` 和 `WINDOW_HEIGHT`：窗口大小
- `GRID_SIZE`：网格大小
- `SNAKE_SPEED`：蛇的移动速度

## 文件结构

- `snake_game.py`: 主游戏文件
- `requirements.txt`: 项目依赖文件
