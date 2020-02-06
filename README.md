# Hello-New-World
## Github 常用命令练习
Let's make a big difference.

-feature-A

-feature-B

---
## Markdown 练习
## 标题
# 标题一
## 标题二
### 标题三

## 文字
*这会是 斜体 的文字*
_这会是 斜体 的文字_

**这会是 粗体 的文字**
__这会是 粗体 的文字__

_你也 **组合** 这些符号_

~~这个文字将会被横线删除~~
## 列表
- Item 1
- Item 2
  - Item 2a
  - Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b  

## 引用框
正如 Kanye West 所说：

> We're living the future so
> the present is our past.

## 代码高亮
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```


```javascript {.line-numbers}
function add(x, y) {
  return x + y
}
```
## 表格
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## 标注

30<sup>th</sup>
H<sub>2</sub>O

## 表情
:smile::blush: 
[Emoji](http://www.emoji-cheat-sheet.com)支持页面

## 图片
引用方法 | 图片
-------|-------
使用七牛云作为图床 | ![text](http://q59qahcgi.bkt.clouddn.com/logo.jpg?e=1580976835&token=HD5V3YuzhZC8rfF6gg7jukkSUibZ2WIcaruYBL2t:5VAS1BWDEdsVT3CSMReRaZzBFbA=)
使用本地图片 | ![text](logo.jpg)
