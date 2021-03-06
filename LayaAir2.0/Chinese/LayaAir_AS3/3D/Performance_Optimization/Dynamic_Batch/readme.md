# 动态合并

###### *version :2.2.0beta   Update:2019-8-28*

动态合并分为 **实例合并** 与 **顶点合并** 两种。这两种优化都无需开发者进行任何设置，而且物体可动态移动，不受限制。但是合并原则相对严格。以下是两种合并最基本条件。

**实例合并:**

​	需要同Mesh和同材质双条件满足。在三维场景中同Mesh同材质的模型还是可能大量存在的，在这时实例合并有不小的发挥空间。

**顶点合并:**

​	需要同材质且模型顶点小于10个。顶点合并目前在一些假阴影和特效模型上有发挥空间。

**注意：**半透明的物体需要连续渲染才能动态合并，所以半透明物体的动态合并几率低。