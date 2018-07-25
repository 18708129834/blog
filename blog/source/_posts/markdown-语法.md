---
title: markdown 语法
date: 2018-07-24 09:59:44
tags:
---
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
# 字体特效
## 字体倾斜
### *字体倾斜效果*
## 字体加粗
### **字体加粗**
## 字体加粗倾斜
### ***字体加粗倾斜***
## 删除线
### ~~删除线效果~~
# 分割线
三个或以上英文减号
---
三个或以上英文星号
***
# 超链接
[点我](http://www.baidu.com)跳转到百度
[点我](http://localhost:4000/2018/07/23/post-traumatic/)进入post_traumatic
# 图片引用
![咸鱼](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1532411281651&di=4144184aa350ec15f5fc541b1b455906&imgtype=jpg&src=http%3A%2F%2Fimg4.imgtn.bdimg.com%2Fit%2Fu%3D3540610699%2C2945347374%26fm%3D214%26gp%3D0.jpg)
# 图片超链接
[![图片名称](图片地址)](超链接地址)
[![咸鱼](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1532411281651&di=4144184aa350ec15f5fc541b1b455906&imgtype=jpg&src=http%3A%2F%2Fimg4.imgtn.bdimg.com%2Fit%2Fu%3D3540610699%2C2945347374%26fm%3D214%26gp%3D0.jpg)](http://www.baidu.com)
# 列表
## 无序列表
语法:用-+*开头都可以
- 列表项1
- 列表项2
- 列表项3
## 有序列表
1. 列表项1
2. 列表项2
3. 列表项3
# 表格

姓名|技能|排行
-|-|-
刘备|哭|头儿
关羽|刀|二
张飞|叫|三儿

# 代码引入，语法高亮
```
def fun():
    print("hello world")
```
```
var a = 1;
function fun(){
    var b =2;
    return a + b;
}
```