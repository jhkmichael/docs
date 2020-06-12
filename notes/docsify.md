windows安装docsify步骤：
1，下载程序，安装nodejs语言环境和npm包管理工具。

```
http://nodejs.cn/download/
```

2，下载npm仓库中的docsify-cli软件

```
npm i docsify-cli -g
//i=install
//g=global 全局安装
```

3，初始化docsify项目

```
docsify init
/*
	docsify项目最基本的三个文件：
	index.html; 用于定制CSS和修改script脚本的网页。
	README.md; 介绍文件。
	_sidebar.md; 目录文件。
*/
```

4，本地发布浏览docsify项目

```
docsify serve
//localhost:3000 为默认浏览入口
```