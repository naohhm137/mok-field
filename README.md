# Mok Field

单文件 WebAR 粒子手势场，使用 Three.js + MediaPipe Hands。

- 16,000 颗青色流体粒子
- 五种手势形态：球体、文字、圆环、星形、爱心
- 速度 + 加速度弹簧物理，爆炸重组、挥手风暴、深度推拉
- Apple 风格响应式 HUD，支持桌面、平板与手机

## 本地预览

```bash
npx serve .
# 打开 http://localhost:3000
```

摄像头需要 `localhost` 或 HTTPS 环境。首次加载会从 unpkg 获取 Three.js 与 MediaPipe Hands 资源。

## 部署到 Render

仓库根目录包含 `render.yaml`。在 Render 中选择 **New → Blueprint**，连接本仓库即可创建静态站点。

也可以直接访问：

```text
https://render.com/deploy?repo=https://github.com/naohhm137/mok-field
```

Render 会提供 HTTPS 域名，适合手机直接打开并授权摄像头。
