# 💠 沈立然 · 个人简历 — 昆明学院

✨ 浅蓝色调 · CSS 3D 几何 · 玻璃拟态 · 分屏布局

## 👤 个人信息

- **姓名**：沈立然
- **学校**：昆明学院 · 信息工程学院
- **专业**：计算机科学与技术（本科 2023-2027）
- **所在地**：云南昆明

## 🎨 设计亮点

| 特性 | 说明 |
|------|------|
| 🔮 **玻璃拟态** | 全卡片 backdrop-filter 毛玻璃，高光条纹 + 反光斑 |
| 🎯 **3D 倾斜交互** | 鼠标悬停卡片实时追踪倾斜，景深变换 |
| 🧊 **3D 几何体** | 八面体、圆环、立方体旋转漂浮背景 |
| 🖥 **分屏布局** | 左侧固定面板（名片+联系）+ 右侧滚动内容 |
| 💫 **鼠标视差** | 背景几何体 + 光晕跟随鼠标产生深度视差 |
| 📊 **环形技能图** | SVG 圆环动画展示技能熟练度 |
| 🌀 **旋转光环** | 头像外围 conic-gradient 渐变光环 |
| 🌊 **流动渐变** | 浅蓝多色渐变背景缓慢流动 |

## 🚀 部署到 GitHub Pages

### 一键部署

1. GitHub 新建仓库 → 上传 `index.html` 到根目录
2. **Settings → Pages** → Source 选 `main` 分支 → Save
3. 访问 `https://你的用户名.github.io/仓库名/` 即可

### 命令行部署

```bash
cd resume
git init
git add index.html README.md
git commit -m "💠 沈立然 昆明学院 个人简历"
git branch -M main
git remote add origin https://github.com/你的用户名/resume.git
git push -u origin main
```

## 🛠 技术栈

纯原生 **HTML + CSS + JavaScript**，无依赖、无构建，打开即用。

## 📝 自定义

编辑 `index.html`：
- 技能百分比 → 修改 `skills` 数组中的 `pct` 值
- 项目经历 → 修改 `.timeline` 中的 `.tl-item` 块
- 项目作品 → 修改 `.projects-grid` 中的 `.project-tile`
- 联系方式 → 修改 `.contact-card` 中的链接和文字
- 配色 → 修改 `:root` 中的 CSS 变量

---

Made with 💙 by 沈立然 · 昆明学院 · 云南昆明
