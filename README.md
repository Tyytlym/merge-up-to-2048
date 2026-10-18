# 2048 无限流 / 2048 Endless

一个支持无限合成、阶段性成就与合成音效的 2048 网页小游戏。  
An endless 2048 web game with milestone achievements and synthesized sound effects.

## 特性 / Features

- ♾️ **无限模式**：不止步于 2048，可一路合成 4096、8192、65536……  
  **Endless mode**: keep merging beyond 2048 — 4096, 8192, 65536…
- 🏅 **17 个阶段性成就**：数字里程碑、分数里程碑、操作成就，分三级提示  
  **17 milestone achievements** in three tiers
- 🔊 **实时合成音效**：移动、合并、成就、结束均有声音，可静音  
  **Real-time synthesized audio**, with mute toggle
- 🎮 **多端操作**：方向键 / WASD / 触摸滑动  
  **Keyboard, WASD, and touch swipe** support
- 💾 **最高分本地保存**  
  **Best score saved locally**

## 运行 / Run

无需构建，直接用浏览器打开 `index.html` 即可。  
No build step. Just open `index.html` in a browser.
or
https://tyytlym.github.io/merge-up-to-2048/

## 操作 / Controls

| 操作 / Action | 键位 / Keys |
| --- | --- |
| 移动 / Move | 方向键 ↑↓←→ / WASD |
| 触屏 / Touch | 在棋盘上滑动 / Swipe on board |
| 新游戏 / New game | 点击“新游戏”按钮 / "新游戏" button |

## 自定义 / Customize

| 想改什么 / What | 位置 / Where |
| --- | --- |
| 棋盘大小 / Board size | 脚本中的 `SIZE` 常量 / `SIZE` constant |
| 成就列表 / Achievements | `ACHIEVEMENTS` 数组 / `ACHIEVEMENTS` array |
| 音效音量 / Volume | `master.gain.value` |
| 方块配色 / Tile colors | CSS 中 `.v2` 至 `.vsuper` / `.v2`–`.vsuper` in CSS |

## 许可证 / License

DeepSeek
