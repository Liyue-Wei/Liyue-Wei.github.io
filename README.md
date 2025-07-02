# Liyue Wei - 个人主页

这是一个现代、响应式的个人主页，使用GitHub Pages托管。

## 🌟 特性

- **现代设计**: 采用渐变色彩和玻璃效果的现代UI设计
- **完全响应式**: 在所有设备上都能完美显示
- **流畅动画**: 包含滚动动画、打字机效果和计数动画
- **交互式导航**: 平滑滚动和移动端汉堡菜单
- **联系表单**: 包含表单验证的联系方式
- **性能优化**: 快速加载和流畅的用户体验

## 📁 文件结构

```
├── index.html      # 主页面文件
├── styles.css      # 样式文件
├── script.js       # JavaScript交互功能
└── README.md       # 项目说明文档
```

## 🚀 快速开始

1. **克隆仓库**
   ```bash
   git clone https://github.com/Liyue-Wei/Liyue-Wei.github.io.git
   cd Liyue-Wei.github.io
   ```

2. **在本地预览**
   - 直接在浏览器中打开 `index.html` 文件
   - 或使用本地服务器（推荐）：
     ```bash
     # 使用Python
     python -m http.server 8000
     
     # 使用Node.js
     npx serve .
     ```

3. **访问网站**
   - 本地: `http://localhost:8000`
   - 线上: `https://liyue-wei.github.io`

## 🎨 自定义

### 修改个人信息

编辑 `index.html` 文件中的以下部分：

1. **基本信息**
   ```html
   <title>您的姓名 - 个人主页</title>
   <h2>您的姓名</h2>
   <span class="name">您的姓名</span>
   ```

2. **个人描述**
   ```html
   <p class="hero-description">
       您的个人介绍文字...
   </p>
   ```

3. **联系方式**
   ```html
   <span>your.email@example.com</span>
   <span>github.com/your-username</span>
   <span>linkedin.com/in/your-profile</span>
   ```

### 修改项目展示

在 `index.html` 的项目部分添加您的真实项目：

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>项目名称</h3>
    <p>项目描述...</p>
    <div class="project-tech">
        <span>技术1</span>
        <span>技术2</span>
    </div>
</div>
```

### 修改配色方案

在 `styles.css` 中修改主要颜色：

```css
/* 主要渐变色 */
background: linear-gradient(135deg, #您的颜色1 0%, #您的颜色2 100%);

/* 强调色 */
color: #您的强调色;
```

### 添加更多技能

在技能标签部分添加您的技能：

```html
<div class="skill-tags">
    <span class="skill-tag">您的技能</span>
    <!-- 添加更多技能 -->
</div>
```

## 🛠️ 技术栈

- **HTML5**: 语义化标记
- **CSS3**: Flexbox、Grid、动画、渐变
- **JavaScript (ES6+)**: 现代JavaScript特性
- **Font Awesome**: 图标库
- **Google Fonts**: Inter字体

## 📱 响应式设计

网站在以下设备上经过测试：

- 桌面端 (1200px+)
- 平板端 (768px - 1199px)
- 移动端 (< 768px)

## 🔧 浏览器支持

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📈 性能优化

- 使用CDN加载外部资源
- CSS和JavaScript文件压缩
- 图像优化
- 延迟加载和动画优化

## 🚀 部署到GitHub Pages

1. **推送代码到GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **启用GitHub Pages**
   - 进入仓库设置
   - 找到"Pages"部分
   - 选择"Deploy from a branch"
   - 选择"main"分支
   - 点击"Save"

3. **访问您的网站**
   - 网站将在 `https://your-username.github.io` 可用

## 🤝 贡献

欢迎提交问题和改进建议！

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 📞 联系方式

如果您有任何问题或建议，请通过以下方式联系我：

- 邮箱: your.email@example.com
- GitHub: [@Liyue-Wei](https://github.com/Liyue-Wei)
- LinkedIn: [Liyue Wei](https://linkedin.com/in/liyue-wei)

---

⭐ 如果这个项目对您有帮助，请给它一个星星！
