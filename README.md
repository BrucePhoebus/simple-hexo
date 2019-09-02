# 项目说明

	该项目是使用hexo技术构建自己的博客项目

## 项目构建

```bash
http://www.conardli.top/blog/article/博客搭建/【博客搭建】个人博客搭建及配置.html#_1-4-部署上传
```

> 该项目是参考该文章构建完成的，可以参考这样构建

## 平时部署上传操作

```bash
npm install hexo-deployer-git --save
hexo clean     //删除上次打包
hexo generate   //打包
hexo deploy    /上传

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

```bash
hexo deploy
```

> 此部署发布是运行`_config.yml`文件进行项目服务器推送的

## 项目在线地址

```bash
https://brucephoebus.github.io
```

## hexo炫酷配置参考

```bash
http://shenzekun.cn/hexo的next主题个性化配置教程.html
```

## 开发说明

* 使用dev分支进行开发，然后本地合并到master分支进行部署提交

```bash
git push origin dev
git checkout master
git merge dev
npm run deploy
```

* master分支是打包部署后的文件，没有项目原代码，master不能进行`pull`或`push`(会有严重冲突)

> 执行完`npm run deploy`就可以从[在线地址](https://brucephoebus.github.io)看到最新效果了
