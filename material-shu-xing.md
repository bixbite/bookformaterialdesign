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
<figure style="width: 43%;float: left;margin-right: 30px;">
	<div><img src="assets/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>材质的宽高可以不同</p>
	</figcaption>
</figure>
<figure style="width: 43%;float: left;">
	<div><img src="assets/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>材质厚度永远是1dp</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

材质会投射阴影

阴影由材质间相对高度自然产生

<section>
<figure style="width: 90%;margin-bottom: 30px">
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
<figure style="width: 90%;margin-bottom: 30px">
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
</section>

内容以不同的形状和颜色显示在材质上，而不会额外增加材质的厚度

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005" width="100%" height="100%" controls="">
	    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWTG41Rk9fT19qUXc/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.webm" type="video/webm">
	    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSGQycHdwcTdyRk0/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>材质可以展示任何形式和色彩</p>
	</figcaption>
</figure>
</section>

内容可以独立于材质进行展示，但必须在材质范围内

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005" width="100%" height="100%" controls="">
	    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeVBlbExGYjlTeEE/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.webm" type="video/webm">
	    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeVBlbExGYjlTeEE/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>内容的行为可以独立于材质的行为</p>
	</figcaption>
</figure>
</section>

材质是实心的

输入事件不能穿过材质传递到下面一层

<section style="margin-bottom: 30px">
<figure style="width: 43%;float: left;margin-right: 30px;">
	<div><img src="assets/whatismaterial_properties_physical3.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>输入事件只能影响上面一层（foreground）的材质</p>
	</figcaption>
</figure>
<figure style="width: 43%;float: left;">
	<div><img src="assets/wrong_through_material.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>输入事件不能穿过材质</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

多个材质元素不能同时占据空间上的同一点（x,y,z值相同）

<section style="margin-bottom: 30px">
<figure style="width: 43%;float: left;margin-right: 30px;">
	<div><img src="assets/whatismaterial_properties_physical3.png" alt=""></div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>为了防止多个材质元素占据空间上同一点，我们使用不同高度加以区分</p>
	</figcaption>
</figure>
<figure style="width: 43%;float: left;">
	<div><img src="assets/wrong_through_material.png" alt=""></div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>多个材质元素不能同时占据空间上的同一点</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

材质不能穿过其他材质

举例来说，即使高度发生改变，一张（块）材质也不能穿过另一张材质

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsekRnTGVlVEQzNXc/whatismaterial_properties_physical_07_xhdpi_009.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsc2VZVUJ5bFNscFU/whatismaterial_properties_physical_07_xhdpi_009.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>材质不能穿过其他材质</p>
	</figcaption>
</figure>
</section>

<hr style="height:1px; margin-bottom: 50px;"></hr>

<h2 id="transform" style="color: #00bcd4">材质的变化</h2>

材质可以改变外观形状

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsRjREbXNsZXBrTFU/whatismaterial-materialprop-transformingmaterial-PaperShape_xhdpi_005.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsMndnRld3dl9nVU0/whatismaterial-materialprop-transformingmaterial-PaperShape_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

材质只能沿其平面放大或缩小

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsZWtfWjlEQ0RTcXc/whatismaterial-materialprop-transformingmaterial-PaperShapeLinear_xhdpi_005.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsLVpqQ0pBOXY3WDQ/whatismaterial-materialprop-transformingmaterial-PaperShapeLinear_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	</figcaption>
</figure>
</section>

材质不允许弯曲或折叠

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsMXhFNUo2WmJrLWc/whatismaterial-materialprop-transformingmaterial-PaperBendFold_xhdpi_006.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsM0s0eE5sODFxcnM/whatismaterial-materialprop-transformingmaterial-PaperBendFold_xhdpi_006.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	</figcaption>
</figure>
</section>

几张材质可以拼合成一张材质

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsRjREbXNsZXBrTFU/whatismaterial-materialprop-transformingmaterial-PaperShape_xhdpi_005.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsMndnRld3dl9nVU0/whatismaterial-materialprop-transformingmaterial-PaperShape_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

材质会在被分开后再次复原。例如，当你从材质中移去一部分，它还会再次归复完整。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsQV9PS2Q0anFoZzg/whatismaterial-materialprop-transformingmaterial-PaperSplitHeal_xhdpi_005.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsNlM0eEhPMDFwMlU/whatismaterial-materialprop-transformingmaterial-PaperSplitHeal_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

<hr style="height:1px; margin-bottom: 50px;"></hr>

<h2 id="motion" style="color: #00bcd4">材质的运动</h2>

材质可以在环境中任何地方自发的产生或消失

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQseERpUzUxRVRtMGs/whatismaterial-materialprop-movementmaterial-PaperPointExpand_xhdpi_005.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsTUF0YzJrX0xfWmc/whatismaterial-materialprop-movementmaterial-PaperPointExpand_xhdpi_005.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>


材质可以沿任何轴移动

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsWkhGeVpPNVdZbE0/whatismaterial-materialprop-movementmaterial-PaperMove_xhdpi_008.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsYXIyWl9fZURydTA/whatismaterial-materialprop-movementmaterial-PaperMove_xhdpi_008.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

z轴上的运动通常是材质和用户之间的交互引起的

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsYWJoQjFCYmdvU3c/whatismaterial-materialprop-movementmaterial-Material_Response_xhdpi_003.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsQW1HYnpicTVySG8/whatismaterial-materialprop-movementmaterial-Material_Response_xhdpi_003.mp4" type="video/mp4">
	</video>
	</div>
</figure>
</section>

<h5><a href="#envir" style="position:fixed;right:120px;bottom:30px">回到顶部</a></h5>









