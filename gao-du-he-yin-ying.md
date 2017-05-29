<h1 id="envir" style="color:#00bcd4;margin: 0">高度与阴影</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>material design中的对象具有和现实世界中相同的特质</p>
</blockquote>

在现实世界中，不同对象可以相互堆叠或粘贴，但不能相互贯穿。对象可以投射阴影同时也可反射光线。

Material Design 通过创造一个用户熟悉的空间模型来展示这些特性，并始终如一地应用于移动应用当中。

<h4 style="color:#00bcd4">高度</h4>

高度是指表面之间的距离和其阴影的深度,它衡量的是一个材质的上表面与另一个材质的上表面之间的垂直距离。

<div style="width: 60%"><img src="assets/what_is_material_elevation_and_shadows.png" alt=""></div>

<h4 style="color:#00bcd4">静态高度</h4>

所有材质都具有静态高度（未具交互状态时的初始高度）。尽管组件在程序之间有着相同的静态高度，然而不同设备和平台间可能具有不同的静态高度。

<h4 style="color:#00bcd4">动态高度偏移</h4>

动态高度偏移是组件相对于静态状态移动的目标高度。

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p style="color:#757575">内容</p>
<h4><a href="#elevation">高度</a></h4>
<h4><a href="#shadow">阴影</a></h4>
<h4><a href="#OBrelationship">对象关系</a></h4>
</blockquote>

<h2 id="elevation" style="color:#00bcd4;">高度</h2>

高度是指材质间的相对纵深，即沿z轴方向两表面间的距离

<h4 style="color:#00bcd4">说明：</h4>

* 高度是以与x轴，y轴相同单位进行测量的，通常是指density independent pixels(密度独立像素)。因为所有材质元素的厚度为1dp，而高度是指从一个材质的上表面到另一个材质上表面的距离。

* 一个子对象的高度和其父对象的高度相关

<div style="width: 70%"><img src="assets/whatismaterial_3d_elevation1.png" alt=""></div>

该图反映了两个材质间的多倍高度

<h4 style="color:#00bcd4">静态高度</h4>

所有材质对象不论大小都具有一个静态高度，或者称之为“默认高度”。静态高度不会发生改变。当材质对象高度发生改变，应该尽快恢复到原先的静态高度。








