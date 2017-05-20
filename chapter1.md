<h1 id="envir" style="color:#00bcd4;margin: 0">环境</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>质感设计是一个含括光，材质和投影的三维环境</p>
</blockquote>

![](/assets/what_is_material_environment.png)

所有材质（material）对象都具有X,Y,Z三种维度

所有材质对象拥有唯一的Z轴位置

主光源产生平行光长投影，环境光创造出软阴影（柔和阴影)

每个质感对象的厚度为1dp

阴影是由相互重叠的材质间的高差产生的

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p><a href="#3d">3D世界</a></p>
<p><a href="#lshadow">光与影</a></p>
</blockquote>

<h2 id="3d" style="color: #00bcd4">3D世界</h2>

![](/assets/whatismaterial_environment_3d.png)

材质（material）对象所处的环境是一个3D空间，这意味着所有对象都具有x，y，z三个维度。z轴与显示平面相垂直，并向用户视角延伸。每个材质元素在z轴上占据一个位置且厚度为1dp。

在网页中，z轴被用来进行层次的表达而非透视关系的表述。我们通过对y轴的操作来模拟3D世界。

<h2 id="lshadow" style="color: #00bcd4">光与影</h2>

在材质（material）环境中，虚拟光线照射整个场景使对象投射阴影。主光源创造平行光长投影，而环境光源从各个角度创造出连贯且柔和的投影。

材质l环境中的所有阴影都是由这两种光源产生的。在Andriod中，当沿着z轴的各个位置的光源被材质片层阻挡时，就会产生阴影。在网页应用中，仅通过操作y轴来描绘阴影。

![](/assets/whatismaterial_environment_shadow1.png)

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">主光源阴影</blockquote>

![](/assets/whatismaterial_environment_shadow2.png)

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">环境光阴影</blockquote>

![](/assets/whatismaterial_environment_shadow3.png)

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">混合阴影</blockquote>

<h5><a href="#envir" style="position:fixed;right:120px;bottom:30px">回到顶部</a></h5>


