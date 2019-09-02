# react-todolist-master

## 简介

这可能只是在学习react过程当中随手的一个小demo，充其量就是一个hello world级别的小应用，但还是希望能给刚开始学习react的朋友一点小小的帮助

项目中使用的技术栈

<ul>
  <li>
    <a href="https://react.docschina.org/">
      <img alt="react" src="https://img.shields.io/badge/react-16.8.6-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/microsoft/TypeScript">
      <img alt="typescript" src="https://img.shields.io/badge/typescript-3.5.3-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/ReactTraining/react-router/">
      <img alt="react-router" src="https://img.shields.io/badge/react--router-5.0.1-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/reduxjs/redux">
      <img alt="redux" src="https://img.shields.io/badge/redux-4.0.4-brightgreen.svg">
    </a>
    <ul>
      <li>
        <a href="https://github.com/reduxjs/react-redux">
          <img alt="react-redux" src="https://img.shields.io/badge/react--redux-7.1.0-blue.svg">
        </a>
      </li>
      <li>
        <a href="https://github.com/reduxjs/redux-thunk">
          <img alt="redux-thunk" src="https://img.shields.io/badge/redux--thunk-2.3.0-blue.svg">
        </a>
      </li>
    </ul>
  </li>
  <li>
    <a href="https://github.com/axios/axios">
      <img alt="axios" src="https://img.shields.io/badge/axios-0.19.0-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/koajs/koa">
      <img alt="koa2" src="https://img.shields.io/badge/koa-2.7.0-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/ZijianHe/koa-router">
      <img alt="koa-router" src="https://img.shields.io/badge/koa--router-7.4.0-brightgreen.svg">
    </a>
  </li>
  <li>
    <a href="https://github.com/Automattic/mongoose">
      <img alt="mongoose" src="https://img.shields.io/badge/mongoose-5.6.9-brightgreen.svg">
    </a>
  </li>
</ul>

前端部分使用react全家桶，axios作为前后端交互，服务端使用koa2+mongoose作为数据支撑

项目实现了三个版本的todoList，分别是纯组件版本，reudx版本和结合服务端的异步redux版本

## 启动

```shell
[# 克隆项目
git clone https://github.com/ZhuCunLong/react-todolist-master

# 进入项目目录
cd react-todolist-master

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动前端
npm run start

# 启动服务端
# 在启动服务端之前，确保安装了mongoDb并打开相关服务
npm run server
```

## 采坑合集

记录了在开发过程中碰到的大大小小采过得坑吧，也算是一个小小的总结

[请移步](https://blog.csdn.net/bye_cherry/article/details/100320320)

