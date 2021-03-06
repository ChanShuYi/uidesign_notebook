<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [切图的基本规范](#%E5%88%87%E5%9B%BE%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E8%8C%83)
  - [哪些内容需要切图](#%E5%93%AA%E4%BA%9B%E5%86%85%E5%AE%B9%E9%9C%80%E8%A6%81%E5%88%87%E5%9B%BE)
  - [切图要求](#%E5%88%87%E5%9B%BE%E8%A6%81%E6%B1%82)
  - [切图尺寸](#%E5%88%87%E5%9B%BE%E5%B0%BA%E5%AF%B8)
  - [快速切图方法 CUTTERMAN](#%E5%BF%AB%E9%80%9F%E5%88%87%E5%9B%BE%E6%96%B9%E6%B3%95-cutterman)
  - [切图命名规范](#%E5%88%87%E5%9B%BE%E5%91%BD%E5%90%8D%E8%A7%84%E8%8C%83)
  - [安卓.9.png](#%E5%AE%89%E5%8D%939png)
  - [切图的注意事项](#%E5%88%87%E5%9B%BE%E7%9A%84%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9)
    - [正切精确的命名](#%E6%AD%A3%E5%88%87%E7%B2%BE%E7%A1%AE%E7%9A%84%E5%91%BD%E5%90%8D)
    - [归纳切片类别](#%E5%BD%92%E7%BA%B3%E5%88%87%E7%89%87%E7%B1%BB%E5%88%AB)
    - [分包存储](#%E5%88%86%E5%8C%85%E5%AD%98%E5%82%A8)
    - [注意点击的区域](#%E6%B3%A8%E6%84%8F%E7%82%B9%E5%87%BB%E7%9A%84%E5%8C%BA%E5%9F%9F)
  - [切图攻略](#%E5%88%87%E5%9B%BE%E6%94%BB%E7%95%A5)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 切图的基本规范

切图是指开发在实现过程中，需要计算好每一个元素（包括文字、图片等）的位置，然后再调用我们切好的图进行填充。

## 哪些内容需要切图

- ICON
- 不规则图形

## 切图要求

一般切图保存为：PNG24

## 切图尺寸

- 320屏幕输出1X
- 640屏幕输出2X
- 960屏幕输出3X

![]()

## 快速切图方法 CUTTERMAN

Cutterman是一个Photoshop扩展功能切图插件。

![]()

## 切图命名规范

- 用英文命名，不用拼音
- 每一部分用下划线分隔
- 两倍图在名字最后要加@2X
- 三倍图在名字最后要加@3X

**LOFTER登陆页面命名规范**

![]()

**网易考拉海购页面**

![]()

**网易考拉海购——主菜单**

![]()

**w网易考拉海购——icon**

![]()

**网易考拉海购——主页面**

![]()

**网易考拉海购——列表页**

![]()

## 安卓.9.png

.9.png切图只有在安卓的设计中才会用到，iOS中是不需要用到的，它主要用于适应不同分辨率的屏幕，使空间可以任意拉伸。

![](../img/03/03_02_02_08_android9png.png)

拉伸之外的效果图：

![](../img/03/03_02_02_09_android9png.png)

修改画图大小，用黑色铅笔画黑点，保存为`.9.png`后缀即可。

- 最外围的一圈像素必须是纯黑色或者透明，一点点的半透明的像素都不可以有，比如99%的黑色或者1%的投影都不可以有。
- 文件的后缀名必须是`.9.png`，不能是.png或者是9.png.png，这样的命名都会导致编译失败。

## 切图的注意事项

### 正切精确的命名

- 开发在实现页面的时候，需要一张张找图，所以精准的命名能够让开发一目了然。

![](../img/03/03_02_02_10_prelice_name.png)

### 归纳切片类别

我们完成的页面会有几十个，每个页面会有零零散散地图标，这时候把他们一个个拿出来根据不同用途归纳到一起可以方便开发同学查找。比如我们可以新建一个toolbar的文件夹存放所有跟工具栏相关的icon。

![](../img/03/03_02_02_11_make_category.png)

### 分包存储

即使我们按照上面把切片分类别了，但零零碎碎地切图，不可能完全分类。于是剩下的一些，我们就需要按照一个页面一个文件包的方式来整理切图，这样不管是开发要拿，或者你要更新，都在这个统一的地方交接就行了。

### 注意点击的区域

![]()

## 切图攻略

![](../img/03/03_02_02_12_cut_idea.png)











