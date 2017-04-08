---
layout: default
---

# 测试文章
2017.04.08

## 文章编写
+ 首先按照markdown格式编写文件，不如本文件为test.md
+ 将写好后的文件放在某一目录下，比如本文件放在 2017 目录下，如果需要新的目录，直接在根目录下新建再将写好的文件放在新目录下
+ markdown文件写好后，需要在根目录下的README.md文件中添加文件链接，比如本文件添加的链接为如下：

```
[A Test blog](./2017/test.html)
```

+ 其中A Test blog为文章的名字，括号中的内容是文章的路径。注意**路径最后的名字必须和markdown的文件名相同，这里都为test，且必须以后缀.html结尾**。
  * 比如如果文件是python.md，放在目录program下，则相应的链接应为：

```
[链接的名字可以随便写](./program/python.html)
```

## 说明

* 目录
  + 2017:放置2017年的文章
  + assets:网页需要的css文件
  + images:目前没有使用，暂定为放置图片的目录
  + _layouts:存放网页布局文件，可以新建其它的布局文件，使用新的布局文件只需要在markdown文件的最前面将layout的值修改即可
* 文件
  + CNAME:公有域名
  + _config.yml:网页头部显示的信息
  + LICENSE
  + README.md:首页



