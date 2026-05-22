# 🎳 Three.js Bowling Game

A 3D bowling game built with Three.js and Cannon-es physics engine.

## 玩法

1. **瞄准** — 鼠标左右移动调整方向
2. **蓄力** — 按住鼠标左键向下拖拽（触摸设备上手指按住后下滑）
3. **投球** — 释放鼠标/手指，球沿瞄准方向飞出
4. **得分** — 10 局标准保龄球计分规则（全中 Strike / 补中 Spare）

## 开发

```bash
npm install
npm run dev     # 本地开发
npm run build   # 构建到 dist/
npm run preview # 预览构建结果
```

## 部署

推送到 GitHub 仓库的 `main` 分支后，GitHub Actions 会自动构建并部署到 GitHub Pages。

1. 创建仓库 `aprilssky/bowling-game`
2. 将代码推送到 `main` 分支
3. 在仓库 Settings → Pages 中确认 Source 为 **GitHub Actions**
4. 自动部署完成后访问 `https://aprilssky.github.io/bowling-game/`

## 技术栈

- [Three.js](https://threejs.org/) — 3D 渲染
- [Cannon-es](https://github.com/pmndrs/cannon-es) — 物理引擎
- [Vite](https://vitejs.dev/) — 构建工具
- [GitHub Pages](https://pages.github.com/) — 部署
