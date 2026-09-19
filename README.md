# haozhexing_introduction

郝哲兴（Haozhe Xing）个人主页 —— 静态站点，由 GitHub Pages 托管。

- 在线地址：https://haozhe-xing.github.io/haozhexing_introduction/
- 入口文件：`index.html`
- 简历：`简历.pdf`

## 目录结构

```
index.html          个人主页（单页，含简介 / 项目 / 书籍 / 荣誉 / 出版物）
简历.html           简历网页版
简历.pdf            简历 PDF
img.png             头像
books/              书籍封面与预览图
news/               动态/新闻配图
```

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

推送到 `main` 分支后，GitHub Pages 会自动发布（Pages 来源：main 分支根目录）。
