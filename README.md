# Nokia 经典手机（Three.js）

一个使用 Three.js 制作的 Nokia 经典款手机示例：
- 鼠标拖拽可旋转查看模型（OrbitControls）
- 点击手机键盘按钮输入数字
- 屏幕与左上角 HUD 实时显示输入值

## 本地运行

直接启动静态服务器：

```bash
python3 -m http.server 4173
```

然后访问 `http://localhost:4173`。

## GitHub Pages 部署

仓库已包含 `.github/workflows/deploy.yml`，推送到 `main` 分支后会自动部署到 GitHub Pages。

> 注意：本示例通过 CDN 加载 Three.js，不需要本地安装依赖。
