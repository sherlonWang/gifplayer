### [中文文档](https://github.com/sherlonWang/gifplayer)|[English Document](https://github.com/sherlonWang/gifplayer/blob/master/README_EN.md)

# GIF play&pause

> This project is based on the Gifplayer project by Ruben Torres
>
> <https://github.com/rubentd/gifplayer>

### 1.Introduction

### We often wish to control GIF's playing when we browse some GIFs with logical steps, because maybe we need some time to think about it on some steps.

### Otherwise it would look something like this:

![](https://cdn.jsdelivr.net/gh/sherlonWang/imgbed/picgo20200807144109.gif)

### WTF! Wait!! Slow down!!! Too fast!! I haven’t even figured out what the last step is doing.

### But if we can control the GIF's playing like this, it will be cool!

![](https://cdn.jsdelivr.net/gh/sherlonWang/imgbed/picgo20200807144846.gif)

### Somebody may have a  question. Why don't we use video? In my opinion, it is not necessary to use video to explain such issue. what do you think?

### 2.Usage

#### import css file

```html
<link href="css/gifplayer.min.css" rel="stylesheet" />
```

#### import javascript file

```html
 <script src="js/gifplayer.min.js" type="text/javascript"></script>
```

#### use GIF with *data-src* attribute

```html
<img data-src="images/2.gif"/>
```

#### <font color = red>Tips：The file path depends on your actual project path</font>

### 3.Demo

#### It will appear a playing icon in the top center of the GIF. We can click it to play or pause the GIF like this:

![](https://cdn.jsdelivr.net/gh/sherlonWang/imgbed/picgo20200807145127.gif)

#### Hope it helps you!