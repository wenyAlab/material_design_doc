# Material Design 环境

所有材料位于一个三维环境中（维度， 阴影， 层级）， 进行模拟光线照射给材料添加阴影，创造层次感。

在物理世界中，物体可以堆叠或彼此连接，但不能相互穿过。他们投下阴影并反射光线。

Material环境是基于三维立体空间，每一个处于界面显示的UI对象或者控件都有一个三维坐标(x,y,z)，一般来说在手机平面显示的位置相对于用户来讲只有平面x-y，但是有了z轴的加入，用户视角就变得更加立体，每个Material 元素在 z 轴上占据一定的位置并且厚度默认只有1dp，厚度是其次，最重要的z轴是用来分层，进而实现更加有序或者更为复杂的交互设计。

![](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-ZUJfcjFIdEVNN28%2Fwhatismaterial-environment-3d.png)

## 原则

### material 具有不同的x和y尺寸（以dp测量）和均匀的厚度（1dp）

![](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-eEJlcFFMUzJXSlE%2Fwhatismaterial-materialproperties-physicalproperties-thickness-01-yes.png)
![](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-UXUtRnFHcEVKeVU%2Fwhatismaterial-materialproperties-physicalproperties-thickness-02-no.png)




