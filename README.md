![](http://www.thinkphp.cn/Uploads/editor/2016-06-23/576b4732a6e04.png) 

ThinkPHP 5.2
===============

[![Build Status](https://travis-ci.org/top-think/framework.svg?branch=master)](https://travis-ci.org/top-think/framework)
[![Total Downloads](https://poser.pugx.org/topthink/framework/downloads)](https://packagist.org/packages/topthink/framework)
[![Latest Stable Version](https://poser.pugx.org/topthink/framework/v/stable)](https://packagist.org/packages/topthink/framework)
[![License](https://poser.pugx.org/topthink/framework/license)](https://packagist.org/packages/topthink/framework)

ThinkPHP5.2底层架构采用PHP7.1改写和进一步优化。

### 计划实现的核心主要特性：

 + 采用PHP7强类型特性
 + 支持PSR-7
 + 多应用支持
 + Hook和行为改为事件系统
 + 模板引擎重构
 + IDE助手


### 计划废除的核心功能：

 + 多模块功能
 + 路由的数组定义
 + 路由行为
 + 核心Facade类的别名

> ThinkPHP5.2的运行环境要求PHP7.1+。

## 安装

~~~
composer create-project topthink/think tp5 5.2.*-dev
~~~

启动服务

~~~
cd tp5
php think run
~~~

然后就可以在浏览器中访问

~~~
http://localhost:8000
~~~

如果需要更新框架使用
~~~
composer update topthink/framework
~~~

## 命名规范

`ThinkPHP5`遵循PSR-2命名规范和PSR-4自动加载规范。

## 参与开发

请参阅 [ThinkPHP5 核心框架包](https://github.com/top-think/framework)。

## 版权信息

ThinkPHP遵循Apache2开源协议发布，并提供免费使用。

本项目包含的第三方源码和二进制文件之版权信息另行标注。

版权所有Copyright © 2006-2018 by ThinkPHP (http://thinkphp.cn)

All rights reserved。

ThinkPHP® 商标和著作权所有者为上海顶想信息科技有限公司。

更多细节参阅 [LICENSE.txt](LICENSE.txt)
