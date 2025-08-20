---
title: 'Academic 博客系统的使用'
date: 2025-08-20
permalink: /posts/2025/08/how-to-use-Jekyll-Academic/
tags:
  - 网站
---

今天尝试用Jekyll博客系统，Academic主题制作一个个人博客。

目标：
1. 实现博客系统的github pages访问。
2. 实现windows下，本地博客系统的运行。
3. 制作这篇日志。

## 什么是Jekyll？
- **静态网站生成器**：将Markdown文件转换为HTML网站
- **GitHub Pages原生支持**：无需额外配置即可使用
- **主题丰富**：提供多种现成的主题和布局
- **插件系统**：扩展功能的插件生态系统


# 一、Academic博客系统的使用：
1、fork项目。
https://github.com/academicpages/academicpages.github.io

2、github中pages设置。

3、访问pages。

# 二、Jekyll Academic windows下的安装及运行
## 1、Jekyll 的安装
官方地址：https://jekyllrb.com/docs/installation/

Jekyll windows下的安装，其他安装方式参考上面官方地址。

windows安装：https://jekyllrb.com/docs/installation/windows/

```
# 安装Jekyll和Bundler
gem install jekyll bundler

# 检查 Jekyll 是否已正确安装：
jekyll -v

Successfully installed jekyll-4.4.1
Successfully installed bundler-2.7.1
2 gems installed
```

## 2、安装Ruby依赖：
```
bundle install
```
## 3、启动本地服务器：
```
jekyll serve -l -H localhost
# 启动失败是
bundle exec jekyll serve -l -H localhost
```