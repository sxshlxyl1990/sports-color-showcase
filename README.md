# 跟着运动学色彩｜4 组高级感运动配色

这是一个展示运动色彩搭配的在线页面，内容来自小红书 @AI 设计工作流。

## 📱 查看页面

**在线链接**: [待部署到 GitHub Pages 后更新]

## 🎨 内容包含

- 4 组运动色彩搭配方案
- 每组配色的色彩分析
- 色彩心理学应用
- 搭配技巧总结

## 🚀 部署到 GitHub Pages

### 方法 1: 使用 GitHub CLI

```bash
# 1. 创建 GitHub 仓库
gh repo create sports-color-showcase --public --source=. --remote=origin

# 2. 启用 GitHub Pages
gh api repos/YOUR_USERNAME/sports-color-showcase/pages -X POST -H "Content-Type: application/json" -d '{"source":{"branch":"master","path":"/"}}'
```

### 方法 2: 手动部署

1. 在 GitHub 创建新仓库 `sports-color-showcase`
2. 推送代码：
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/sports-color-showcase.git
   git branch -M master
   git push -u origin master
   ```
3. 在 GitHub 仓库 Settings → Pages 中：
   - Source: Deploy from a branch
   - Branch: master
   - Folder: / (root)
4. 等待 1-2 分钟，页面将发布到：
   `https://YOUR_USERNAME.github.io/sports-color-showcase/`

## 📦 文件结构

```
sports-color-showcase/
├── index.html          # 主页面
├── cards/              # 卡片图片
│   ├── card_02.png    # 粉色网球×绿色场地
│   ├── card_03.png    # 紫色×绿色场地
│   ├── card_04.png    # 粉色网球×蓝白背景
│   └── card_05.png    # 红土场地×白色线条
└── README.md          # 说明文档
```

## 🎯 使用场景

- 分享给客户看配色方案
- 放在作品集里展示
- 社交媒体分享
- 团队内部参考

## 📝 原文案

**标题**: 跟着运动学色彩｜这 4 组配色太高级了！🎾

**标签**: #色彩搭配 #设计灵感 #配色分享 #运动色彩 #色彩心理学

---

Created by AI 设计工作流 | 小红书 @AI 设计工作流
