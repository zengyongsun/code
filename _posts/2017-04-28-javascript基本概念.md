# 语法
ECMAScript 的语法大量借鉴了 C 及其他类 C 语言（如 Java 和 Perl）
#### 区分大小写
一切（变量、函数名和操作符）都区分大小写
#### 标识符
标识符：就是指变量、函数、属性的名字，或者函数的参数。可以是按照下列格式规则组合起来的一或多个字符：
- 第一个字符必须是一个字母、下划线（_）或一个美元符号（$）；
- 其他字符可以是字母、下划线、美元符号或**数字**

按照惯例，标识符采用驼峰大小写格式，也就是第一个字母小写，剩下的每个单词的首字母大写。
>不能把关键字、保留字、ture、false 和 null用作标识符

#### 注释
---
layout: post
title:  "JavaSctipt基本概念"
date:   2017-04-28 13:19:48 +0800
categories: javascript
---
使用 C 风格的注释，
- 行注释
`//行注释`
- 块注释
```
/**
*块注释
*这是一个多行注释
*/
```


#### 严格模式（strict mode）
严格模式是为 javascript 定义了一中不同的解释和执行模型。作用：ECMAscript 中的一些不确定的行为将得到处理，而且对某些不安全的操作也会抛出错误。
整个脚本中启用严格模式，在顶部代码中添加`"use strict"`。也可以指定单个函数在严格模式下执行。
#### 语句
ECMAScript 中的语句以一个分号结尾；如果省略分号，则由解析器确定语句的结尾。（可以不写分号，但是不推荐）
#### 关键字和保留字
- 关键字：

|   |   |   |   |
| ------------ | ------------ | ------------ | ------------ |
| break |do   | instanceof   |typeof |
| case        | else | new  | var  |
| catch  | finally  | return  | void  |
| continue  | for  | switch  | while  |
| debugger  | function  | this  | with  |
| default  | if  | throw  | delete  |
| in  | try  |
- 保留字

|   |   |   |   |
| ------------ | ------------ | ------------ | ------------ |
|  abstract | enum  | int  |  short |
|  boolean | export  | interface  |  static |
| byte  | extends  | long  | super  |
|  char | final  | native  | synchronized  |
|  class | float  | package  | throws  |
|  const | goto  | private  | transient  |
| debugger  | implements  | protected  | volatile  |
| double | import | pulic |
