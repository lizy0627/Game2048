# 2048 Game - Console Version

这是一个基于 C 语言的控制台版 2048 游戏，支持 Windows 平台。

## 功能特性
- 完整的 2048 游戏逻辑（合并、移动、计分）
- 方向键控制移动（上下左右）
- 彩色数字显示
- 游戏胜利/失败判定
- 重新开始和退出选项
- 游戏规则和操作说明

## 项目结构
- `main.c` - 程序入口和主函数
- `game_functions.c` / `game_functions.h` - 游戏逻辑函数
- `ui_functions.c` / `ui_functions.h` - 界面绘制和菜单函数
- `keyboard.c` / `keyboard.h` - 键盘输入处理
- `Makefile` / `CMakeLists.txt` - 编译配置文件

## 编译与运行

### 使用 GCC 编译：
```bash
gcc main.c -o 2048.exe -lwinmm
