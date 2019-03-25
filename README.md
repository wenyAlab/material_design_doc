# 《Material Design 简介》

Material Design是一种视觉语言(设计规范)，遵循纸片与墨水的视觉设计，并将物理运动带入到UI设计中，它将优秀设计的经典原则与技术和科学的创新相结合。

Material Design是google在2014年推出的一套设计规范，主要包括设计的布局、动画、过渡、填充、光线、阴影等。旨在为不同展示平台提供一致的设计语言。

Material Design的灵感来自物理世界及其纹理，包括它们如何反射光线和投射阴影。材料表面重新构想纸张和墨水的介质。

Material Design在设计过程中对排版，网格，空间，比例，颜色和图像创造层次和焦点，让其有一定的存在意义。



Material Design字面翻译的版本有很多。其中‘质感设计’“原质化设计”更为贴切。因为Material Design本是一种考虑事物本质的设计，将电子屏幕里的UI元素看成是一种不存在于现实世界的新的材质，并赋予它类似纸片与墨水的物理特性。因此Material Design并不是去拟物化的设计。许多人会将把扁平化与拟物化对立起来，其实两者并不是对立关系。扁平化其实也有纸片设计的元素，只不过缺少物理世界的立体感。

### Material Design英文官网（ https://material.io/ ）
### Material Design中文翻译文档（ https://www.mdui.org/design/# ）
### Material Design中文指南GitHub（ https://github.com/zdhxiong/Material-Design-Chinese ）


## 目的

旨在为不同展示平台提供一致的设计语言和设计系统。

## 原则

质感，真实体验
鲜明，突出核心
有意义的动画效果

## 环境

所有材料位于一个三维环境中（维度， 阴影， 层级）， 进行模拟光线照射给材料添加阴影，创造层次感

Material环境是基于三维立体空间，每一个处于界面显示的UI对象都有一个三维坐标(x,y,z)，一般来说在手机平面显示的位置相对于用户来讲只有平面xOy，但是有了z轴的加入，用户视角就变得更加立体，每个Material 元素在 z 轴上占据一定的位置并且厚度默认只有1dp，厚度是其次，最重要的z轴是用来分层，进而实现更加有序或者更为复杂的交互设计。


```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.25.2/install.sh | bash
```

nvm 的全称是 **Node Version Manager**，之所以需要这个工具，是因为 Node.js 的各种特性都没有稳定下来，所以我们经常由于老项目或尝新的原因，需要切换各种版本。

安装完成后，你的 shell 里面应该就有个 nvm 命令了，调用它试试

```
$ nvm
```

当看到有输出时，则 nvm 安装成功。

### 安装 Node.js

使用 nvm 的命令安装 Node.js 最新稳定版，现在是 `v0.12.3`。

```
$ nvm install 0.12
```

安装完成后，查看一下

```
$ nvm ls
```

这时候可以看到自己安装的所有 Node.js 版本，输出应如下：

![](https://raw.githubusercontent.com/alsotang/node-lessons/master/lesson0/1.png)

（图1）

那个绿色小箭头的意思就是现在正在使用的版本，我这里是 `v0.10.29`。我还安装了 `v0.11.14`，但它并非我当前使用的版本。

如果你那里没有出现绿色小箭头的话，告诉 nvm 你要使用 `0.12.x` 版本

```
$ nvm use 0.12
```

然后再次查看，这时候小箭头应该出现了。

OK，我们在终端中输入

```
$ node
```

REPL(read–eval–print loop) 应该就出来了，那我们就成功了。

随便敲两行命令玩玩吧。

比如 `> while (true) {}`，这时你的 CPU 应该会飚高。

### 完善安装

