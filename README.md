# FEZMOCK
让前端工程师独立于后端进行开发。增加单元测试的真实性，通过随机数据，模拟各种数据场景。

## FEZMOCK使用背景

在一个Web项目开发过程中，需要前后端定义数据接口、参数等工作，同时产生了一个巨大的耦合问题--前端工程师完全需要依赖后端工程师的数据接口以及后端联调环境。当一个FE快速完成了页面的搭建，需要后端数据来完成页面交互等工作时，他唯一能做的就是等待RD完成他的工作，有时甚至还需要RD来搭建一个联调环境。


## 开始使用
- FEZMOCK需要与 【[FEZ前端模块化工程开发框架](https://github.com/furic-zhao/fez)】配合使用，通过模块化注入机制，可以模拟研发、上线后的数据环境，方便给业务方、或领导演示使用。

- NPM安装

````bash
npm install fezmock --save
````


