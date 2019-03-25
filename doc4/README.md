# Material Design 颜色

Material design重视动画效果，它反复强调一点：动画不只是装饰，它有含义，能表达元素、界面之间的关系，具备功能上的作用。

### easing

![](https://image.uisdc.com/wp-content/uploads/2014/12/b-2.gif)

动画要贴近真实世界，就要重视easing。物理世界中的运动和变化都是有加速和减速过程的，忽然开始、忽然停止的匀速动画显得机械而不真实。考虑动画的easing，要先考虑它在现实世界中的运动规律。

### 水波反馈

![](https://image.uisdc.com/wp-content/uploads/2014/12/b-3.gif)
![](https://image.uisdc.com/wp-content/uploads/2014/12/b-4.gif)
![](https://image.uisdc.com/wp-content/uploads/2014/12/b-5.gif)

所有可点击的元素，都应该有这样的反馈效果。通过这个动画，将点击的位置与所操作的元素关联起来，体现了Material design动画的功能性。

### 出入场动画

![](https://image.uisdc.com/wp-content/uploads/2014/12/b-6.gif)

通过过渡动画，表达界面之间的空间与层级关系，并且跨界面传递信息。



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

