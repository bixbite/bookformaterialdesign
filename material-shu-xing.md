<h1 id="envir" style="color:#00bcd4;margin: 0">Material 属性</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>材质(material)具有一些不变的特性和固有的行为</p>
</blockquote>

<div style="width: 70%"><img src="assets/what_is_material_material_properties.png" alt=""></div>

了解这些材质的特性将有助你以符合material design所倡导的方式熟练的使用材质

<h4 style="color:#00bcd4">材质(material)特性包括：</h4>

* 固体（立体）
* 单独占用空间
* 不可穿透
* 形状变化
* 根据其所在平面尺寸改变大小
* 不可弯曲
* 材质间可相互连接
* 可相互隔离，分开，复原
* 可被创建或销毁
* 延任意轴移动

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p style="color:#757575">内容</p>
<h4><a href="#physics">物理特性</a></h4>
<h4><a href="#transform">材质的变化</a></h4>
<h4><a href="#motion">材质的运动</a></h4>
</blockquote>

<hr style="height:1px; background-color: #fff; margin-bottom: 50px;"></hr>

<h2 id="physics" style="color: #00bcd4">物理特性</h2>

材质拥有不同的x，y轴(宽高)尺寸及均匀的厚度（单位为1dp）

<section style="margin-bottom: 30px">
<figure style="width: 43%;display: inline-block;margin-right: 30px;">
	<div><img src="assets/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>材质的宽高可以不同</p>
	</figcaption>
</figure>
<figure style="width: 43%;display: inline-block;">
	<div><img src="assets/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>材质厚度永远是1dp</p>
	</figcaption>
</figure>
</section>

材质会投射阴影

阴影由材质间相对高度自然产生

<figure style="width: 90%；margin-bottom:30px">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSE9IaUpqYzlpSW8/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWJfTERvdnM1bGc/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>不同的阴影形态描绘了材质间的相对高度的变化</p>
	</figcaption>
</figure>

<figure style="width: 90%; margin-bottom:30px">
	<div>
<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007" width="100%" height="100%" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWYU5lQ1VXQjA3NnM/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWM0xqQms4LWRkMVE/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.mp4" type="video/mp4">
</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>当材质发生变化（高度），阴影绝不会保持相似</p>
	</figcaption>
</figure>



