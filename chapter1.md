# 环境

> 质感设计是一个含括光，材质和投影的三维环境

![](/assets/what_is_material_environment.png)

所有材质（material）对象都具有X,Y,Z三种维度

所有材质对象拥有唯一的Z轴位置

主光源产生平行光长投影，环境光创造出软阴影（柔和阴影\)

每个质感对象的厚度为1dp

阴影是由相互重叠的材质间的高差产生的

> 3D世界
>
> 光与影

## 3D世界

![](/assets/whatismaterial_environment_3d.png)

材质（Material）对象所处的环境是一个3D空间，这意味着所有对象都具有x，y，z三个维度。z轴与显示平面相垂直，并向用户视角延伸。每个材质元素在z轴上占据一个位置且厚度为1dp。

在网页中，z轴被用来进行层次的表达而非透视关系的表述。我们通过对y轴的操作来模拟3D世界。

## 光与影

在材质（Material）环境中，虚拟光线照射整个场景使对象投射阴影。主光源创造平行光长投影，而环境光源从各个角度创造出连贯且柔和的投影。

材质l环境中的所有阴影都是由这两种光源产生的。在Andriod中，当沿着z轴的各个位置的光源被材质片层阻挡时，就会产生阴影。在网页应用中，仅通过操作y轴来描绘阴影。

![](/assets/whatismaterial_environment_shadow1.png)

> 主光源阴影

![](/assets/whatismaterial_environment_shadow2.png)

> 环境光阴影

![](/assets/whatismaterial_environment_shadow3.png)

> 混合阴影


