<h1 id="envir" style="color:#00bcd4;margin: 0">持续时间和缓动效果</h1>
<hr style="height:1px;"></hr>

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p>运动中的材质是响应和自然的。使用这些缓动曲线和持续时间模式来创造出平滑统一的动画</p>
</blockquote>
缓动曲线:
* 标准曲线
* 减速曲线
* 加速曲线
* 锐曲线

<blockquote style="color:#00bcd4;border-left: 4px solid #00bcd4;margin: 30px 0;">
<p style="color:#757575">内容</p>
<h4><a href="#speed">动画速度</a></h4>
<h4><a href="#dynamic">动态的持续时间</a></h4>
<h4><a href="#commons">通用动效持续时间</a></h4>
<h4><a href="#natural">自然的缓动曲线</a></h4>
</blockquote>

<h2 id="speed" style="color: #00bcd4">动画速度</h2>

当元素位置和状态发生改变时，动效应该足够快而不至需要等待，但转场为了便于理解可适当放慢速度。如果用户经常可以看到此动效，可以维持较短转场。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01S3dRNGEtaVRHbnM/QuickResponse_01_QuickDo_v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01eGJDZEVBUjZqVUU/QuickResponse_01_QuickDo_v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>动效要快，这样用户不需要等待动画完成。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01SlFzYzNJdG5MTXM/QuickResponse_01_QuickDont_v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01THVvNjB1eFYyVk0/QuickResponse_01_QuickDont_v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>不要慢慢的表现动画，因为它会造成不必要的延迟</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="dynamic" style="color: #00bcd4">动态的持续时间</h2>

针对不同的行进距离，元素运行速度和表面的变化，采取不同的动效持续时间，而不是为所有动画提供唯一的持续时间。

物体离开屏幕时的动效可能较短，因为它们需要较少的注意。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RmIzcDNDd2tnak0/DynamicDurations_01_LongDistance-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01WHpEd1JVWVBvUm8/DynamicDurations_01_LongDistance-v2.mp4" type="video/mp4">
	</div>
</figure>
<figcaption>当物体需要行进较长距离或表面发生显著变化时，需要使用较长的动效持续时间。</figcaption>
</section>

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bEdqaWFncGo2anM/DynamicDurations_02_ShortDistance-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01T3RNOFhadU96OTQ/DynamicDurations_02_ShortDistance-v2.mp4" type="video/mp4">
	</div>
</figure>
<figcaption>当物体行进距离较短或表面稍微发生改变时，使用较短的持续时间，以使运动不会显的太慢。</figcaption>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="commons" style="color: #00bcd4">通用动效持续时间</h2>

<h4 style="color:#00bcd4">手机</h4>

手机上的动效通常在300ms左右，在这种差异范围内：
* 较大的，复杂的全屏动效转场可能持续时间更久，一般超过375ms
* 元素进入屏幕一般在225ms左右
* 元素离开屏幕一般在195ms

转场动效超过400ms就会让人感觉到慢

<h4 style="color:#00bcd4">大屏</h4>

行进距离较长的元素要比在同一时间段内行进距离短的峰值速度更高。因此大屏上更应具有更长的持续时间，以便动效不会太快

<h4 style="color:#00bcd4">平板</h4>

平板上的持续时间应该比手机上长30%。例如在手机上的时长300ms，在平板上应该为390ms

<h4 style="color:#00bcd4">可穿戴</h4>

可穿戴设备上的动效持续时间应比手机上少30%

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01cjZHeUxGdHRIc2s/CommonDurations_01_3Devices_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01MS1KNXRLQ0hZUzQ/CommonDurations_01_3Devices_v1.mp4" type="video/mp4">
	</div>
</figure>
<figcaption>因为材质元素在较大尺寸设备上移动的距离更长，所以转场动效应比屏幕较小的设备稍慢。</figcaption>
</section>

<h4 style="color:#00bcd4">台式</h4>

桌面上的动效应该比相应移动端更快，更简洁。动效应保持在150ms-200ms。

因为桌面端的转场可能不那么引人注意，因此动效应立即响应且较之移动端更快。

复杂的页面转场通常会导致丢帧，因此更短的持续时间可以使丢帧问题变得不太明显，因为动效完成的更快。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01cjZHeUxGdHRIc2s/CommonDurations_01_3Devices_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01MS1KNXRLQ0hZUzQ/CommonDurations_01_3Devices_v1.mp4" type="video/mp4">
	</div>
</figure>
<figcaption>台式机上应用动效更快</figcaption>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="natural" style="color: #00bcd4">自然的缓动曲线</h2>

这些自然的缓动曲线影响一个元素的运动速度，透明度和大小变化。

在整个动画的持续过程中，加速和减速的变化应该保持平滑，这样做使得动画看起来不至于机械。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Nmh2YUJrLXRIQ00/NaturalEasing_01_CurveNoCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01U1Bwb0RRVW5rVFE/NaturalEasing_01_CurveNoCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

当物体运动的加速和减速越不对称，运动越显得更加自然和令人愉悦。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01QmRrZkxRMElCenM/NaturalEasing_00_AsymetricCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01VXpUY3h6NHBtbXc/NaturalEasing_00_AsymetricCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

<h4 style="color:#00bcd4">缓动曲线</h4>

根据所使用的平台或软件，缓动曲线的命名可能不同。 这些准则将它们称为标准，减速，加速和曲线。

<h4 style="color:#00bcd4">标准曲线</h4>

标准曲线是最常见的缓动曲线，也被称为渐入渐出。它是指元素快速加速然后缓慢减速的运动。它适用于材质的缩放及其它的一些属性变化。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01blBnODdnZnZuVE0/NaturalEasing_02_StandardCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01LXZKZ0NUeVRrdzg/NaturalEasing_02_StandardCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

<div class="module" style="margin-bottom: 30px">
<table class="s-tag-table">
<tbody>
<tr><td colspan="1" rowspan="1"><p>Platform</p></td><td colspan="1" rowspan="1"><p>Protocol</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>Android</p></td><td colspan="1" rowspan="1"><p>FastOutSlowInInterpolator</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>iOS</p></td><td colspan="1" rowspan="1"><p>[[CAMediaTimingFunction alloc] initWithControlPoints:0.4f:0.0f:0.2f:1.0f]</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>CSS</p></td><td colspan="1" rowspan="1"><p>cubic-bezier(0.4, 0.0, 0.2, 1);</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>After Effects</p></td><td colspan="1" rowspan="1"><p>Outgoing Velocity: 40%<br>Incoming Velocity: 80%</p></td></tr>
</tbody>
</table>
</div>

<h4 style="color:#00bcd4">减速曲线</h4>

当使用减速曲线时，元素以全速进入屏幕并且缓慢减速到静止点。

在减速过程中，元素可以在尺寸或透明度上进行放大。在某些情况下，当元素以0透明度进入屏幕时，它们可能会以较大的尺寸略微缩小的形式进入。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01MTRaLVVwVmNad3M/NaturalEasing_03_DecelerationCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01cEVUck1yWENMRzQ/NaturalEasing_03_DecelerationCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

<div class="module" style="margin-bottom: 30px">
<table class="s-tag-table">
<tbody>
<tr><td colspan="1" rowspan="1"><p>Platform</p></td><td colspan="1" rowspan="1"><p>Protocol</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>Android</p></td><td colspan="1" rowspan="1"><p>LinearOutSlowInInterpolator</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>iOS</p></td><td colspan="1" rowspan="1"><p> [[CAMediaTimingFunction alloc] initWithControlPoints:0.0f:0.0f:0.2f:1.0f]</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>CSS</p></td><td colspan="1" rowspan="1"><p>cubic-bezier(0.0, 0.0, 0.2, 1);</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>After Effects</p></td><td colspan="1" rowspan="1"><p>Outgoing Velocity: 0%<br>
Incoming Velocity: 80%</p></td></tr>
</tbody>
</table>
</div>

<h4 style="color:#00bcd4">加速曲线</h4>

当使用加速曲线时，元素以全速离开屏幕，直到元素移出屏幕也不会减速。

元素在动画开始时加速，并可能尺寸和透明度都降低到0. 在有些情况下，当元素以0%不透明度离开屏幕时，它们也可能在尺寸上略微缩小。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01U1lNVGFiV0plWHc/NaturalEasing_04_AccelerationCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01TndGaDBxRTRpOW8/NaturalEasing_04_AccelerationCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

<div class="module" style="margin-bottom: 30px">
<table class="s-tag-table">
<tbody>
<tr><td colspan="1" rowspan="1"><p>Platform</p></td><td colspan="1" rowspan="1"><p>Protocol</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>Android</p></td><td colspan="1" rowspan="1"><p>FastOutLinearInInterpolator</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>iOS</p></td><td colspan="1" rowspan="1"><p> [CAMediaTimingFunction alloc] initWithControlPoints:0.4f:0.0f:1.0f:1.0f]</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>CSS</p></td><td colspan="1" rowspan="1"><p>cubic-bezier(0.4, 0.0, 1, 1);</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>After Effects</p></td><td colspan="1" rowspan="1"><p>Outgoing Velocity: 40%<br>Incoming Velocity: 0%</p></td></tr>
</tbody>
</table>
</div>

<h4 style="color:#00bcd4">锐曲线</h4>

当使用锐曲线时，元素快速加速和减速。它通常被随时退出并可能返回屏幕的元素使用。

元素可以从屏幕的开始点迅速加速，然后以不对成的曲线快速减速到静止点，随即立即消失。其减速比标准曲线更快，因为它不会遵循一个精准的路径离开屏幕。元素可以随时从该点返回。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01d2xfcmNhRXl0ck0/NaturalEasing_05_SharpCurve_v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01aHVDZFVTSy1LLW8/NaturalEasing_05_SharpCurve_v1.mp4" type="video/mp4">
	</div>
</figure>
</section>

<div class="module" style="margin-bottom: 30px">
<table class="s-tag-table">
<tbody>
<tr><td colspan="1" rowspan="1"><p>Platform</p></td><td colspan="1" rowspan="1"><p>Protocol</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>Android</p></td><td colspan="1" rowspan="1"><p>-</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>iOS</p></td><td colspan="1" rowspan="1"><p>-</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>CSS</p></td><td colspan="1" rowspan="1"><p>cubic-bezier(0.4, 0.0, 0.6, 1);</p></td></tr>
<tr><td colspan="1" rowspan="1"><p>After Effects</p></td><td colspan="1" rowspan="1"><p>Outgoing Velocity: 40%<br>Incoming Velocity: 40%</p></td></tr>
</tbody>
</table>
</div>
