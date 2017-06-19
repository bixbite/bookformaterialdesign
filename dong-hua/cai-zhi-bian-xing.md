<h1 id="envir" style="color:#00bcd4;margin: 0">材质变形</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>质感设计可以通过成倍增减的方式改变元素的形状和大小，使其外观看起来更为生动。</p>
</blockquote>

<h4 style="color:#00bcd4">矩形变形</h4>

* 对称变形
* 非对称变形

<h4 style="color:#00bcd4">放射变形</h4>

对称和圆形

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p style="color:#757575">内容</p>
<h4><a href="#rectangle">矩形变形</a></h4>
<h4><a href="#radial">径向变形</a></h4>
<h4><a href="#joindiv">融合和分割</a></h4>
</blockquote>

<h2 id="rectangle" style="color: #00bcd4">矩形变形</h2>

元素在屏内两点间的运动应遵循自然的凹型弧线。所有屏内运动都使用标准曲线缓动效果。

<h4 style="color:#00bcd4">上弧运动</h4>

现实世界中反重力的上升行为需要花费更多的精力。在屏幕上向上移动的元素应该通过较慢的向上运动来反应在加速过程中用力的行为。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Y2RoRE1vcnNPYVk/ShiftWithin_01_Upward_Do_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01R1pOdFdNUm0yOFk/ShiftWithin_01_Upward_Do_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>当向上对角移动时，应以浅缓到急剧的速率变化向上移动</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Ym5MR3U1czRuSEE/ShiftWithin_02_Upward_Dont_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bUdzZ0h0c2pVV2c/ShiftWithin_02_Upward_Dont_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要一开始就以急剧的速率向上移动</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">下弧运动</h4>

现实世界中下落的元素受重力影响而加速。在屏幕上向下移动的元素也应通过较快的下落运动反应出用力较少。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Y2RoRE1vcnNPYVk/ShiftWithin_01_Upward_Do_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01R1pOdFdNUm0yOFk/ShiftWithin_01_Upward_Do_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>相反地，对角向下运动时，开始急剧结束浅缓</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Ym5MR3U1czRuSEE/ShiftWithin_02_Upward_Dont_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bUdzZ0h0c2pVV2c/ShiftWithin_02_Upward_Dont_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要以浅缓的下降开始元素向下运动</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">何时不需要弧线运动</h4>

当元素沿一个坐标轴（不论水平或是垂直）运动时，不需要沿弧线移动。这些运动更简单，移动起来可能更快。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Y2RoRE1vcnNPYVk/ShiftWithin_01_Upward_Do_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01R1pOdFdNUm0yOFk/ShiftWithin_01_Upward_Do_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>保持沿单坐标轴直线运动</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Ym5MR3U1czRuSEE/ShiftWithin_02_Upward_Dont_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bUdzZ0h0c2pVV2c/ShiftWithin_02_Upward_Dont_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要使用不自然的弧线到单坐标轴运动上</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

元素进入或移出屏幕时，都只沿单坐标轴运动。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Y2RoRE1vcnNPYVk/ShiftWithin_01_Upward_Do_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01R1pOdFdNUm0yOFk/ShiftWithin_01_Upward_Do_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>线性进入方式易于遵守一个定义明晰的入口点</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Ym5MR3U1czRuSEE/ShiftWithin_02_Upward_Dont_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bUdzZ0h0c2pVV2c/ShiftWithin_02_Upward_Dont_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>当元素移出屏幕时，不要使用弧线轨迹，因为它可能使入口点变的复杂</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="inoutscreen" style="color: #00bcd4">入屏出屏运动</h2>

<h4 style="color:#00bcd4">自主运动</h4>

移入移出的元素被称为独立元素，因为它们不会影响屏内其它内容的位置。

<h4 style="color:#00bcd4">进入屏幕</h4>

进入屏幕的元素使用减速曲线来完成迅速进入的动作，这表明它们已经按照峰值速度移动。

<h4 style="color:#00bcd4">永久离开屏幕</h4>

元素永久离开屏幕使用加速曲线以较短的持续时间快速离开屏幕，因为它们不会再返回屏幕，且不需要用户额外关注。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01a09wS2pHdkVUcGc/InOut_01_ShiftInOutDo_v3-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01V3c5cHRmbmlYYkE/InOut_01_ShiftInOutDo_v3-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>对进入屏幕的元素使用减速曲线动效，而不影响周围元素的位置。对永久离开屏幕的此元素使用加速曲线动效。在手机上，减速转场通常持续225ms上下。加速转场大约195ms</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01eUtuc0RzblJZeTg/InOut_02_ShiftInOutDont_v3-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01WTg0VDIxYzJSdk0/InOut_02_ShiftInOutDont_v3-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要在这些情况下使用标准曲线。 对于入口而言，缓慢的加速是不必要的，因为用户焦点应在最后的休息点。 对于出口而言，由于终点不可见，所以不需要慢速减速。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">暂时离开屏幕</h4>

元素暂时离开屏幕应使用锐曲线,因为它们可能随时返回屏幕，并应出现在附近和可触及范围内。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01VzRiempLVndHQWM/InOut_03_ShiftOutTempDo_v4-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01alI4QmJZcVhoUE0/InOut_03_ShiftOutTempDo_v4-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>将锐曲线应用到暂时离开屏幕的元素上，这些元素可能从相同的退出点返回。当它们返回时，使用减速曲线。在手机上，这个转场通常在300ms上下。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01T3hETkkwTjRGV28/InOut_04_ShiftOutTempDont_v4-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01aWJxbzZwWl9FR2s/InOut_04_ShiftOutTempDont_v4-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要将加速曲线运用到永久离开屏幕的项目，或应用到从不同位置返回的元素上。如果返回，应使用减速曲线。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">相对运动</h4>

对于会影响屏幕上其它元素的移入移出运动，应沿着平滑的缓动曲线进行，以便它们能保持最低限度的破坏性，避免引人注目的戏剧性动作。屏内的移入移出运动应采用标准曲线。这个曲线相较独立元素的时长稍长。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01U3RfQ3dTN3RROE0/InOut_05_ShiftInOutRelativeDo_v3-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Qm1pV0ZjWnZIQmc/InOut_05_ShiftInOutRelativeDo_v3-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>如图，由于浮动操作按钮被下面的卡片进入影响，所以这两个元素都应采用标准曲线以保持一个平滑的开始和结束。在手机上，转场通常在300ms。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01NVR1akxla0pFa1k/InOut_06_ShiftInOutRelativeDont_v3-device.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RkhFaTRGN0J6UTg/InOut_06_ShiftInOutRelativeDont_v3-device.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>使用减速和加速曲线进行向上和向下运动会导致屏幕上的浮动操作按钮突然开始向上移动，并突然停止向下。这个运动是生硬且有破坏性的。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>






