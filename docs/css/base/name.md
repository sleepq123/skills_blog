---
title: CSS 命名规范
---
### CSS的命名规范

####  1. id的命名

```
(1)页面结构

容器: container                                     页头：header

内容：content/container                      页面主体：main

页尾：footer                                        导航：nav

侧栏：sidebar                                      栏目：column

页面外围控制整体布局宽度：wrapper

左右中：left right center

(2).导航

导航：nav                                              主导航：mainnav

子导航：subnav                                     顶导航：topnav

边导航：sidebar                                     左导航：leftsidebar

右导航：rightsidebar                              菜单：menu

子菜单：submenu                                  标题: title

摘要: summary

(3).功能

标志：logo                                             广告：banner

登陆：login                                            登录条：loginbar

注册：regsiter                                       搜索：search

功能区：shop                                        标题：title

加入：joinus                                          状态：status

按钮：btn                                              滚动：scroll

标签页：tab                                          文章列表：list

提示信息：msg                                     当前的: current

小技巧：tips                                          图标: icon

注释：note                                            指南：guild

服务：service                                        热点：hot

新闻：news                                          下载：download

投票：vote                                           合作伙伴：partner

友情链接：link                                    版权：copyright
```

####  2. class的命名

```
(1)颜色:使用颜色的名称或者16进制代码,如

.red { color: red; }

.f60 { color: #f60; }

.ff8600 { color: #ff8600; }

(2)字体大小,直接使用"font+字体大小"作为名称,如

.font12px { font-size: 12px; }

.font9pt {font-size: 9pt; }

(3)对齐样式,使用对齐目标的英文名称,如

.left { float:left; }

.bottom { float:bottom; }

(4)标题栏样式,使用"类别+功能"的方式命名,如

.barnews { }

.barproduct { }

```
**注意事项**:
> 一律小写;尽量用英文;不加中杠和下划线;2个组合的单词不用中杠和下划线可以将第二个单词的首字母大写（eg:mainContent）;尽量不缩写，除非一看就明白的单词.

#### 3. 主要的站点css文件

```
主要的 master.css                                        模块 module.css

基本共用 base.css（root.css）                    布局，版面 layout.css

主题 themes.css                                          专栏 columns.css

文字 font.css                                               表单 forms.css

补丁 mend.css                                            打印 print.css
```