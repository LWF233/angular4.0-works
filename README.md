# NgStation

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.1.0.
 
## 项目简介:

`本项目是由`angular-cli`脚手架工具搭建的一个博客类的项目,主要是各个组件之间的传参和对于angular4.0 的使用,主旨在与使用angular4.0和typescript语法;介绍一些跨组件的传参;和数据的结构分析与使用下面是一些环境配置说明.`

## 整合了网易云音乐的歌单和播放:
首先感谢`https://github.com/Binaryify/NeteaseCloudMusicApi提供的nodejs的api`,才让我能实现这一功能,目前只是可以播放我的歌单里的音乐,由于api不是很稳定,所以有些格式和播放器以及图片的格式没有调整,只是实现了最简单的功能,利用了angular4.0中的父子组件之间的通信,传递当前歌曲的ID以获取对应的url,实现播放功能;
 
![image](https://github.com/mr-xkk/angular4.0-works/src/assets/musicplay.png);

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

=======

 
>>>>>>> 54c7ff3ae01fc85996def6732c066b91612b63e3
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
