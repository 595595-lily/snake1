# 🐍 贪吃蛇 Snake

Vibe Coding 部署课小作业：一个纯前端贪吃蛇小游戏（单文件 HTML，零依赖）。

## 功能
- 🎵 背景音乐（Web Audio 实时合成，无需任何音频文件）
- ⏸ 暂停 / 继续（按钮或空格键）
- 🐢🚶🐰 慢 / 中 / 快 三档速度，游戏中随时切换
- ❤❤❤ 三条命（撞墙或咬到自己扣一条，三条用完 Game Over）
- 📱 键盘（方向键 / WASD）与手机滑动双控制
- 🏆 最高分本地保存（localStorage）

## 本地运行
直接用浏览器打开 `index.html` 即可。

## 部署（GitHub + Vercel，零成本）
1. 推到 GitHub：
   ```bash
   git init
   git add .
   git commit -m "snake"
   git remote add origin https://github.com/<你的用户名>/snake.git
   git push -u origin main
   ```
2. 打开 vercel.com → Import 该仓库 → **Framework Preset 选 "Other"** → Deploy
3. 拿到 `xxx.vercel.app`，发到手机微信点开验收
