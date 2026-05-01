# personal-homepage
Pure HTML5/CSS3/JS single-page portfolio. Features: Three.js 3D icosahedron with physical material &amp; halo particles; custom WebGL shaders for flowing gradient backgrounds; Canvas 2D particle system with mouse repulsion; dark/light theme with localStorage; IntersectionObserver scroll animations; SVG progress indicator; print-optimized resume export.
# 个人主页 · 王乃勋

> 香港城市大学 计算机科学与技术 大二 · 全栈开发方向

基于原生前端技术构建的个人展示主页，集成 3D 可视化、WebGL 着色器编程、Canvas 粒子系统等多项图形学技术。

---

## 使用方法

### 直接打开

用浏览器打开 `index.html` 即可运行，无需任何构建工具或服务器。

```
index.html
```

### 本地开发（推荐用 Live Server）

使用 VS Code 的 **Live Server** 插件或任何静态文件服务器，以获得最佳体验（Three.js 通过 CDN 加载）：

```bash
# Python
python -m http.server 8080

# Node.js (npx)
npx serve .
```

然后在浏览器访问 `http://localhost:8080`。

---

## 功能特性

| 功能 | 说明 |
|------|------|
| 3D 科技核心 | Three.js 细分二十面体 + 物理材质 + 光环粒子系统 |
| WebGL 着色器背景 | GLSL 片段着色器实现流动有机渐变（浅色模式） |
| Canvas 粒子系统 | 130 粒子鼠标交互 + 动态连线 |
| 深色/浅色主题 | CSS 变量双主题切换，localStorage 持久化 |
| 技能滚动动画 | IntersectionObserver 驱动淡入 + 逐点填充 |
| 回到顶部按钮 | SVG 环形进度指示器 |
| 简历 PDF | 浏览器打印 API 一键生成 |
| 响应式布局 | 适配桌面 / 平板 / 手机 |

---

## 技术栈

- **HTML5 / CSS3 / JavaScript** — 纯原生，零框架依赖
- **Three.js** — 3D 场景构建与渲染
- **WebGL / GLSL** — 自定义着色器编程
- **Canvas 2D** — 粒子系统与交互
- **CSS 自定义属性** — 主题系统
- **IntersectionObserver** — 滚动驱动动画
- **SVG** — 进度指示器
- **localStorage** — 主题持久化

---

## 项目结构

```
index.html    — 单文件应用（HTML + CSS + JavaScript）
README.md     — 项目说明
```

---
