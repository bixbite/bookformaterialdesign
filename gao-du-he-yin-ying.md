<h1 id="envir" style="color:#00bcd4;margin: 0">高度与阴影</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>material design中的对象具有和现实世界中相同的特质</p>
</blockquote>

在现实世界中，不同对象可以相互堆叠或粘贴，但不能相互贯穿。对象可以投射阴影同时也可反射光线。

Material Design 通过创造一个用户熟悉的空间模型来展示这些特性，并始终如一地应用于移动应用当中。

<h4 style="color:#00bcd4">高度</h4>

高度是指表面之间的距离和其阴影的深度,它衡量的是一个材质的上表面与另一个材质的上表面之间的垂直距离。

<div style="width:60%"><img src="assets/what_is_material_elevation_and_shadows.png" alt=""></div>

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

<div style="width:80%"><img src="assets/whatismaterial_3d_elevation1.png" alt=""></div>

该图反映了两个材质间的多倍高度

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<h4 style="color:#00bcd4">静态高度</h4>

所有材质对象不论大小都具有一个静态高度，或者称之为“默认高度”。静态高度不会发生改变。当材质对象高度发生改变，应该尽快恢复到原先的静态高度。

<div class="module">
	<table class="s-tag-table">
		<tbody>
		<tr><td colspan="1" rowspan="1"><p>Elevation (dp)</p></td><td colspan="1" rowspan="1"><p>Component</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>24</p></td><td colspan="1" rowspan="1"><p>Dialog</p><p>Picker</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>16</p></td><td colspan="1" rowspan="1"><p>Nav drawer </p><p>Right drawer</p><p>Modal bottom Sheet</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>12</p></td><td colspan="1" rowspan="1"><p>Floating action button (FAB - pressed)</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>9</p></td><td colspan="1" rowspan="1"><p>Sub menu (+1dp for each sub menu)</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>8</p></td><td colspan="1" rowspan="1"><p>Bottom navigation bar</p><p>Menu</p><p>Card (when picked up) </p><p>Raised button (pressed state)</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>6</p></td><td colspan="1" rowspan="1"><p>Floating action button (FAB - resting elevation)</p><p>Snackbar</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>4</p></td><td colspan="1" rowspan="1"><p>App Bar</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>3</p></td><td colspan="1" rowspan="1"><p>Refresh indicator</p><p>Quick entry / Search bar (scrolled state)</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>2</p></td><td colspan="1" rowspan="1"><p>Card (resting elevation) *</p><p>Raised button (resting elevation)*</p><p>Quick entry / Search bar (resting elevation)</p></td></tr>
		<tr><td colspan="1" rowspan="1"><p>1</p></td><td colspan="1" rowspan="1"><p>Switch</p></td></tr>
		</tbody>
	</table>
</div>

<h4 style="color:#00bcd4">组件高度</h4>

一种组件的静态高度在同一平台的所有app中保持一致。例如，在不同应用中浮动操作按钮的高度是不会发生改变的。

组件可能在不同平台中会有不同的静态高度，这取决于所处环境的深度。例如，电视比台式电脑的深度更深是由于电视拥有更大的屏幕并且它是从更远的距离进行观看。同理，电视和台式机的深度也要大于手机。

<h4 style="color:#00bcd4">响应高度和动态高度偏移</h4>

有些组件也具有响应高度，这意味着它们会响应用户输入（默认状态，获取焦点，按压操作）或系统事件而改变其高度。这类高度的改变始终通过动态高度偏移来实现。

动态高度偏移是组件相对于静止状态移动的目标高度。动态高度偏移确保了当组件行为和类型发生改变时高度变化能保持一致。例如, 所有组件被按压后升起时应保持相同的高度变化相对其静态时的高度。

当输入事件完成或被取消时，组件应该恢复到它的静态高度。

<h4 style="color:#00bcd4">避免高度间相互干扰</h4>

具有响应高度的组件可能会在其静止高度和动态高度偏移之间移动时遇到其它组件。由于材质间不可相互穿越，因此不论是在基于单个组件还是使用整个应用的布局时应该避免任何形式的干扰。

在组件层面上，组件可以在其导致干扰之间移动或移除。例如，一个浮动操作按钮可以在用户选择一个卡片时消失或移除屏幕，或是移动到snackbar上。

在整体布局层面上，在设计应用时应该尽量减少干扰的机会。例如将浮动操作按钮放置在一连串卡片的一侧，这样的话当用户选择一张卡片时，按钮就不会受到干扰。

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<h4 style="color:#00bcd4">组件高度对比</h4>

下图展示了组件静态高度和动态高度偏移

<div style="margin-bottom: 30px;"><img src="assets/whatismaterial_3d_elevation2.png" alt=""></div>

该图显示了一个拥有卡片和浮动操作按钮的应用布局，以及沿其z轴的组件高度的横截面

<div style="margin-bottom: 30px;"><img src="assets/whatismaterial_3d_elevation3.png" alt=""></div>

该图显示了一个具有抽屉导航的应用布局，以及沿其z轴的组件高度横截面

<div style="margin-bottom: 30px;"><img src="assets/whatismaterial_3d_elevation4.png" alt=""></div>

<hr style="height:1px;"></hr>

<h2 id="shadow" style="color:#00bcd4;">阴影</h2>

阴影提供了关于物体深度和运动方向的重要视觉线索。它们是表明对象表面之间的间距值的唯一视觉线索。一个对象的高度决定了其阴影如何呈现。

<section style="margin-bottom: 30px">
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow1.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>如果没有阴影，就无法表明浮动操作按钮是与背景表面相分离的</p>
	</figcaption>
</figure>
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow2.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>清晰且生硬的阴影表面按钮与蓝色色块是相分离的元素。但是，它们的阴影过于接近以至于会认为按钮和色块处于同一的高度。</p>
	</figcaption>
</figure>
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow3.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>柔和且较大的阴影表明浮动按钮比蓝色色块具有更高的高度</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

在运动中，阴影也提供了关于对象运动方向的有用线索，同时能反映出物体表面间的距离是增加或是减少。

<section style="margin-bottom: 30px">
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow4.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>没有阴影表示高度，我们无法获知当前矩形是大小尺寸增加还是高度增加。</p>
	</figcaption>
</figure>
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow5.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>当物体的高度增加时其阴影会变得更大更柔和，反之阴影将会变小且清晰生硬。</p>
	</figcaption>
</figure>
<figure style="width: 30%;float: left;margin-right: 20px;">
	<div><img src="assets/whatismaterial_3d_elevation_shadow6.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>在这种情况下，一致的阴影帮助用户了解当前对象是形状发生变化而非高度改变。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">元素阴影参考</h4>
<!-- app bar-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>应用bar</strong></p>
	<p>4dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component06.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- Raised button-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>浮雕按钮</strong></p>
	<p>静态：2dp</p>
	<p>点击：8dp</p>
	<p>对于桌面程序</p>
	<p>静态：0dp</p>
	<p>点击：2dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component02.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- FAB-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>浮动操作按钮 </strong></p>
	<p>静态：6dp</p>
	<p>点击：12dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component08.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- card-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>卡片组件</strong></p>
	<p>静态：2dp</p>
	<p>点击：8dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component03.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- menu-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>菜单和子菜单</strong></p>
	<p>菜单：8dp</p>
	<p>子菜单：9dp （每增加一级子菜单，增加1dp的阴影）</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component09.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- dialog-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>对话框</strong></p>
	<p>24dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component12.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- nav drawer-->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>抽屉导航和右侧抽屉导航</strong></p>
	<p>16dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component10.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- Modal bottom sheet -->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>Modal bottom sheet</strong></p>
	<p>16dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component11.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- Refresh -->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>刷新按钮</strong></p>
	<p>3dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component05.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- search -->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>快速查询／搜索条</strong></p>
	<p>静态：2dp</p>
	<p>滚动：3dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component04.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- snackbar -->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>Snack bar</strong></p>
	<p>6dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component07.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<!-- Switch -->
<section style="margin-bottom: 30px">
<div style="width: 20%;float: left;margin-right: 20px;">
	<p><strong>切换按钮</strong></p>
	<p>1dp</p>
</div>
<figure style="width: 75%;float: left;">
	<div><img src="assets/whatismaterial_3d_elevation_component01.png" alt=""></div>
</figure>
<div style="clear: both;"></div>
</section>
<hr style="height:1px; margin-bottom: 50px;"></hr>
<h2 id="OBrelationship" style="color:#00bcd4;">对象关系</h2>
<h4 style="color:#00bcd4">对象层级关系</h4>

在app中如何组织和集合对象决定着对象间如何相对运动。对象可以独立于其它独立运动，也可被层级更高的对象所约束。

所有的对象都是根据父子关系所描述的层级结构的一部分。子级指的该元素附属于其父元素。对象可以同时是系统或其它对象的字元素。

父子关系说明：
* 每个对象只能有一个父级元素
* 每个对象可以有多个子元素
* 子元素从它的父元素继承了与形状相关的属性，例如位置，旋转，大小和高度
* 兄弟关系是指处于同一层级间的对象关系

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsbHQ3X1ZoVXY3NjQ/WhatIsMaterial_ObjectsIn3DSpace_ObjectRelationships_01_RaisedChildButton_001.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQscFRYQjBFSm9jRGM/WhatIsMaterial_ObjectsIn3DSpace_ObjectRelationships_01_RaisedChildButton_001.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<h4 style="color:#00bcd4">例外</h4>

对象如果父级元素是根元素的话，如主UI元素，它将独立于其它元素自主运动。例如，浮动操作按钮就不会随着内容滚动而滚动。此类元素还包括：
* 抽屉导航
* 行动条
* 对话框

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQscnNBNFlpaTIxNnM/WhatIsMaterial_ObjectsIn3DSpace_ObjectRelationships_02_FAB_001.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsUDJVcWVVWlMzNWc/WhatIsMaterial_ObjectsIn3DSpace_ObjectRelationships_02_FAB_001.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

<h4 style="color:#00bcd4">交互</h4>

一个对象如何与其他对象交互取决于其在父子层级间的位置

例如：
* 子元素于其父元素的间距最小，其它元素无法插入其间
* 在一个滚动的卡片集合中，所有的卡片都是同级的兄弟元素，因此它们都同时一起移动。卡片集合对象作为它们的父级元素，控制着它们的运动。

<h4 style="color:#00bcd4">高度</h4>

如何决定对象的高度（它们在z轴上的位置）依赖于你想传达的内容的层级，以及该对象是否需要独立于其它对象进行移动。








