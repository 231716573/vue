# vue
  vue学习

# vue-cli搭建

1、安装nodejs

2、使用淘宝定制的 cnpm (gzip 压缩支持) 命令行工具代替默认的 npm:
```
   npm install -g cnpm --registry=https://registry.npm.taobao.org
```	 

   使用 cnpm 命令来安装模块：
```	 
   cnpm install [name]
```	 

3、安装vue-cli

  3.1、 node -v               //查看node版本，需要4以上

  3.2、 cnpm install -g vue-cli   //安装vue-cli

  3.3、 vue                   //运行查看vue是否正常安装完毕

  3.4、 vue list              // 查看可以使用vue什么模板

  3.5、 vue init webpack sell    //安装webpack模板，项目名字为"sell"

            Project name sell    //项目名字，默认

            Project description (A vue.js project)     //项目描述

            Author               //项目作者

            Install vue-router?  (Y/n)    Y

            User ESLint to lint your code？ (Y/n)  Y    //es6代码风格检查器

            Setup unit tests with Karma + Mocha? (Y/n)  n   //单元测试

            Setup e2e tests with Nightwatch?(Y/n)  n

  3.6、 cd sell

  3.7、 cnpm install   //安装依赖

  3.8、 cnpm run dev   //让代码监听8080端口在本地调试



meta：<br />
    ```<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">```<br />
    ```<meta http-equiv="Cache-Control" content="no-siteapp"/>```<br />
    ```<meta name="renderer" content="webkit"> <!-- 启用360浏览器的极速模式(webkit) -->```<br />
    ```<meta http-equiv="X-UA-Compatible" content="IE=edge"> <!-- 避免IE使用兼容模式 -->```<br />
    ```<meta name="screen-orientation" content="portrait">```<br />
    ```<meta name="x5-orientation" content="portrait">```<br />
    ```<meta name="full-screen" content="yes">```<br />
    ```<meta name="x5-fullscreen" content="true">```<br />
    ```<meta name="x5-page-mode" content="app">```<br />
    ```<meta name="browsermode" content="application">```<br />
    ```<meta name="msapplication-tap-highlight" content="no">```<br />
    ```<meta name="copyright" content="hzzly">```<br />
    ```<meta name="keywords" content="html5,css3,vue,axios,vuex"> <!-- 关键词 -->```<br />
    ```<meta name="description" content="hzzly,xyy-vue"> <!-- 网站内容描述 -->```<br />
    ```<meta name="author" content="hzzly,hjingren@aliyun.com"> <!-- 作者 -->```
