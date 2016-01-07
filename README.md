
# [Intermediate Meteor Introduction](https://www.youtube.com/watch?v=BI8IslJHSag&list=PLLnpHn493BHFYZUSK62aVycgcAouqBt7V)

## 1 - Project Introduction

提前预览一下本project完成时的功能和样子.

## 2 - Package

解释如何添加和使用包,同时也把项目里面需要使用的package提前都加进去了.

## 3 - Project Structure

单项目创建的目录结构.

## 4 - Basic Layout

MainLayout和HomeLayout编写

## 5 - Basic Routing with Layout in Meteor

'/'路径的路由显示

## 6 - Defining A Schema in Meteor

详细讲解Schema的写法

## 7 - Easy Forms with AutoForm in 

通过quickForm添加数据

## 8 - Insert Permissions, Publishing & Meteor Toys

先使用如下包, 然后在运行的chrome界面里面安CTRL-M就可以在web页面看相关信息了

```
meteortoys:allthings
```

## 9 - Sub-documents & Array Fields

定义数组形式的子段并通过autoform添加

## 10 - Private & Public Settings and Google Analytics

通过settins.json文件添加private和public的setting, 其中private的仅在server可见,public的在client也可见

## 11 - Create Partials and Adding Styles

通过styl格式添加了一些样式,在webstorm里面编辑styl有比较好的用户体验

另外,视频中也展示了一些html输入的技巧,比如

```
  ul>li*3>a 
```

按tab以后可以生成如下内容

```html
  <ul>
    <li><a href=""></a></li>
    <li><a href=""></a></li>
    <li><a href=""></a></li>
  </ul>
```

## 12 - Building Our Recipes List

通过templete添加列表

## 13 - Template Level Subscriptions