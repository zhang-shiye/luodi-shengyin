# 《落地生银》银发经济创业实战社群 — 官方网站

银发经济创业实战社群官方网站，包含四大核心板块：

- **社群首页** (`index.html`) — 社群总览、四大成员角色与核心权益
- **长护险B端服务** (`service.html`) — 落地生银首次大航海计划
- **线下实操营** (`camp.html`) — 24天全闭环线下跟岗实操营
- **标杆联营开店** (`joint.html`) — 安徽社家长护险服务站联营计划

## 技术栈

- Tailwind CSS (Play CDN)
- Font Awesome 6.4
- Google Fonts (Noto Sans SC)
- 原生 JavaScript (IntersectionObserver 滚动动画)

## 项目结构

```
/
├── index.html              # 社群首页
├── service.html            # 长护险B端服务
├── camp.html               # 线下实操营
├── joint.html              # 标杆联营开店
├── assets/
│   ├── css/
│   │   └── common.css      # 共享样式（设计令牌、动画、组件）
│   └── js/
│       └── common.js       # 共享脚本（滚动揭示、移动端菜单、返回顶部）
└── README.md
```

## 本地预览

直接用浏览器打开 `index.html`，或启动本地服务器：

```bash
npx serve .
```

## 部署

已部署至 GitHub Pages。

---

&copy; 2026 《落地生银》银发经济创业实战社群. All Rights Reserved.
