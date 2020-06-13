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

ps：

​	1，图片使用相对路径即可正常。  
​    2，国内线路，github图片浏览目前需要设置hosts。  
​    3，所以，建议使用图床。

​	hosts修改配置：

​	https://www.jianshu.com/p/1a2013b38730



图床设置：

[https://jackson0714.github.io/PassJava-Learning/#/99.tools/%E5%9B%BE%E5%BA%8A%E7%A5%9E%E5%99%A8%E9%85%8D%E7%BD%AE](https://jackson0714.github.io/PassJava-Learning/#/99.tools/图床神器配置)



自动显示md文件中目录

https://my.oschina.net/mianshenglee/blog/3073303 



自动添加markdown的换行（两个空格）

https://www.jianshu.com/p/a8570bd5b15e 



markdown教程

http://xianbai.me/learn-md/article/about/readme.html 

