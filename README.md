# My Tech Blog

一个基于Hexo和Butterfly主题的技术博客

## 本地开发

```bash
# 安装依赖
npm install

# 启动本地服务器
npx hexo server

# 生成静态文件
npx hexo generate

# 部署到GitHub Pages
npx hexo clean && npx hexo deploy
```

## 在线编辑

1. 访问 GitHub仓库
2. 点击要编辑的文件
3. 点击编辑按钮（铅笔图标）
4. 修改内容后点击 "Commit changes"
5. GitHub Actions会自动部署

## 目录结构

```
├── _config.yml          # Hexo配置
├── _config.butterfly.yml # Butterfly主题配置
├── source/
│   ├── _posts/          # 博客文章
│   ├── about/           # 关于页面
│   ├── categories/      # 分类页面
│   └── tags/            # 标签页面
└── themes/
    └── butterfly/       # Butterfly主题
```