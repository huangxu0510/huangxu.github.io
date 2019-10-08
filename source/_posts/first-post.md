---
title: hexo博客markdown书写语法
date: 2019-09-30 16:57:52
tags:
---

# hexo博客markdown书写语法
---

## 标题
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
注：#和文字之间建议保留一个字符的空格，这是最标准的Markdown写法

## 列表
```
- 文本1
- 文本2
- 文本3

1. 文本1
2. 文本2
3. 文本3
```

## 插入代码
在代码钱使用四个空格或者一个制表符（tap）或者用反引号裹住代码
\`\`\`
	print "hello world"
\`\`\`
```
    print "hello world"
```

## 链接和图片
```
1. 链接
[显示文本](链接地址)
2. 插入图片
![alt text](图片链接地址)
```

[百度](https://www.baidu.com)
![土豆](https://i.loli.net/2019/10/08/51ylhKWdCTx2zUG.png)

## 引用
在我们写作的时候经常需要引用他人的文字，这个时候引用这个格式就很有必要了，在 Markdown 中，你只需要在你希望引用的文字前面加上 > 就好了
```
> 一盏灯， 一片昏黄； 一简书， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。
```

> 一盏灯， 一片昏黄； 一简书， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。

## 粗体和斜体
Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。
```
*一盏灯*， 一片昏黄；**一简书**， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。
```
*一盏灯*， 一片昏黄；**一简书**， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。

## 插入音乐
比如网易云音乐，找到喜欢的歌曲，点击分享按钮，把里面的代码复制下来，直接粘贴到博文中即可。
```
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 
    src="http://music.163.com/outchain/player?type=2&id=25706282&auto=0&height=66">
</iframe>
```

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 
    src="http://music.163.com/outchain/player?type=2&id=25706282&auto=0&height=66">
</iframe>


## 插入视频
```
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 
    src="http://music.163.com/outchain/player?type=2&id=25706282&auto=0&height=66">
</iframe>
```


<iframe
    height=498 width=510
    src="http://player.youku.com/embed/XNjcyMDU4Njg0"
    frameborder=0 allowfullscreen>
</iframe>