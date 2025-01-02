# HyperNav - AI Navigation Hub

![](https://cdn.jsdelivr.net/gh/pusvsimg/img@main/Image/20250102103602915.png)

[English](#english) | [中文](#chinese)

## English

A modern, beautiful navigation website with AI-style design and smooth user experience.

### Features

- 🎨 Modern UI Design
- 🌙 Dark Theme
- ✨ Neon Light Effects
- 🌟 Glassmorphism Design
- 📱 Fully Responsive
- 🎯 Smart Icon Matching
- ♿ Accessibility Support

### How to Add or Modify Links

#### 1. Basic Structure

All website links are in the `categories-container` section of `index.html`. Each category follows this structure:

```html
<div class="category">
  <h2 class="category-title">Category Name</h2>
  <div class="nav-grid">
    <a href="url" class="nav-item"><span>Display Name</span></a>
    <!-- More links -->
  </div>
</div>
```

#### 2. Adding New Links

To add a new link, insert a new link item in the appropriate category's `nav-grid`:

```html
<a href="https://example.com" class="nav-item"><span>Website Name</span></a>
```

#### 3. Adding New Categories

To add a new category, copy and paste this template into the `categories-container`:

```html
<div class="category">
  <h2 class="category-title">New Category Name</h2>
  <div class="nav-grid">
    <a href="https://example1.com" class="nav-item"><span>Site 1</span></a>
    <a href="https://example2.com" class="nav-item"><span>Site 2</span></a>
  </div>
</div>
```

#### 4. Icon System

The website uses Font Awesome 5 icon library with automatic matching. Matching rules:

1. Predefined icon matching: Based on URL or name
2. Keyword matching: Based on common keywords
3. URL structure matching: Based on domain name
4. Default icons: Smart fallback if no match is found

To customize icons, add new mappings to `iconMap`:

```javascript
// Add new mappings to iconMap
['website-keyword', 'fas fa-icon-name'],  // Using Font Awesome free icons
['brand-name', 'fab fa-brand-icon'],      // Using brand icons
```

#### 5. Important Notes

- Ensure all links include `https://` or `http://`
- Maintain HTML structure integrity
- Don't remove class attributes
- Keep all links within `<span>` tags

### Development

#### Local Development

1. Clone repository:
```bash
git clone [repository-url]
```

2. Open `index.html` in your browser

#### Customizing Styles

- Color variables are defined in CSS `:root` selector
- Responsive breakpoints can be adjusted in media queries
- Animations can be modified in respective CSS classes

### Contributing

Pull Requests are welcome to improve the project.

### License

This project is licensed under GNU GPL v3.

### Contact

For issues or suggestions, please submit an Issue or contact the maintainer.

---

## Chinese

一个美观、现代的导航网站，具有 AI 风格的设计和流畅的用户体验。

## 特点

- 🎨 现代化 UI 设计
- 🌙 深色主题
- ✨ 霓虹灯效果
- 🌟 磨砂玻璃效果
- 📱 完全响应式设计
- 🎯 智能图标匹配
- ♿ 无障碍支持

## 如何添加或修改网址链接

### 1. 基本结构

网站链接都在 `index.html` 文件中的 `categories-container` 部分。每个分类都遵循以下结构：

```html
<div class="category">
  <h2 class="category-title">分类名称</h2>
  <div class="nav-grid">
    <a href="网址" class="nav-item"><span>显示名称</span></a>
    <!-- 更多链接 -->
  </div>
</div>
```

### 2. 添加新链接

要添加新链接，只需在相应分类的 `nav-grid` 中添加新的链接项：

```html
<a href="https://example.com" class="nav-item"><span>网站名称</span></a>
```

### 3. 添加新分类

要添加新的分类，复制以下模板并粘贴到 `categories-container` 中：

```html
<div class="category">
  <h2 class="category-title">新分类名称</h2>
  <div class="nav-grid">
    <a href="https://example1.com" class="nav-item"><span>网站1</span></a>
    <a href="https://example2.com" class="nav-item"><span>网站2</span></a>
  </div>
</div>
```

### 4. 图标系统

网站使用 Font Awesome 5 图标库，图标会自动匹配。匹配规则如下：

1. 预定义图标匹配：根据网址或名称自动匹配
2. 关键词匹配：基于常见关键词匹配相应图标
3. URL 结构匹配：基于域名智能匹配
4. 默认图标：如果无法匹配，将使用智能默认图标

如果要自定义图标，可以在 `iconMap` 中添加新的映射：

```javascript
// 在 iconMap 中添加新的映射
['网站关键词', 'fas fa-图标名称'],  // 使用 Font Awesome 免费图标
['品牌名称', 'fab fa-品牌图标'],    // 使用品牌图标
```

### 5. 注意事项

- 确保所有链接都包含 `https://` 或 `http://`
- 保持 HTML 结构的完整性
- 不要删除 class 属性
- 确保每个链接都在 `<span>` 标签内

## 开发相关

### 本地开发

1. 克隆仓库：
```bash
git clone [仓库地址]
```

2. 在浏览器中打开 `index.html` 文件

### 自定义样式

- 颜色变量在 CSS `:root` 选择器中定义
- 响应式断点可在媒体查询中调整
- 动画效果可在相应的 CSS 类中修改

## 贡献

欢迎提交 Pull Requests 来改进项目。

## 许可证

本项目采用 GNU GPL v3 许可证。

## 联系方式

如有问题或建议，请提交 Issue 或联系维护者。


