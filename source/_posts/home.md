---
title: 项目首页
---

该项目是使用hexo技术构建自己的博客项目

## 项目构建

* 该项目是参考该文章构建完成的，可以参考这样构建

```bash
http://www.conardli.top/blog/article/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA/%E3%80%90%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E3%80%91%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E5%8F%8A%E9%85%8D%E7%BD%AE.html#_1-1-%E6%9C%AC%E5%9C%B0%E5%AE%89%E8%A3%85hexo
```

## 平时部署上传操作

```bash
npm install hexo-deployer-git --save    # 本地安装上传工具
hexo clean      # 删除上次打包
hexo generate   # 打包
hexo deploy     # 上传

# 集成部署
npm run deploy
```

## 本地服务运行

```bash
hexo server
```

## 生产静态文件

```bash
hexo generate
```

## 部署发布

* 此部署发布是运行`_config.yml`文件进行项目服务器推送的

```bash
hexo deploy
```
