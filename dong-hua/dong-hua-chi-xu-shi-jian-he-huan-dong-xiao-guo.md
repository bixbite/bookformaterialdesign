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







<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01dG5OVlFUTVFySTg/Responsive_01_Durations-v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01a05pM2FXWEN0b0U/Responsive_01_Durations-v1.mp4" type="video/mp4">
	</video>
	</div>
</figure>
<figcaption>较大的动画时长应保持在300-400ms，较小的保持在150-200ms。大于或小于这些时长的动画可能会让人感到迟钝或目光难以追踪。</figcaption>
</section>

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01aGFDUmZwNG1sTTQ/Responsive_02_Feedback-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01YVB4OXVzV3NQR3M/Responsive_02_Feedback-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>该动画通过立即从触碰点向外扩散的墨水晕染效果来确认用户的输入。浮起的卡片组件表面当前处于组件激活状态。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RkRSNjBMbGU2UHM/Responsive_03_SurfaceConnection-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01MkJzdEZuY0E5YXM/Responsive_03_SurfaceConnection-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>该动画显示了新创建的组件平面如何与创建它的元素或动作进行衔接。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">自然</h4>

质感设计描绘的是与现实世界中力学相一致的自然的运动。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01ZDVubnRMcENfcnM/Natural_01_Easing-v1.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01aWFoSHhFRVRpZW8/Natural_01_Easing-v1.mp4" type="video/mp4">
	</div>
</figure>
<figcaption>在现实世界中，元素的加速减速运动受到其重量和物体表面摩擦的影响。同样，在质感设计中开始和结束的动作也不会突然发生。</figcaption>
</section>

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01eUt4Umt0dHVfblU/Natural_02_Arc-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01SktIam0yei0wSnM/Natural_02_Arc-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>受真实世界中力学的启发，例如重力，元素应沿弧线运动而非直线。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01b0VCclNJdV9xZmM/Natural_03_Transform-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bzJOUXhfTTVZY28/Natural_03_Transform-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>材质元素的变形也应该沿弧线运动。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">察觉</h4>

材质元素可以意识到它周围的环境，包括它周围的用户或其他材质。材质可以被吸附其它元素上，并根据用户意图作出适当的反应。[相关阅读](https://material.io/guidelines/motion/choreography.html)

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01TkJIam1HM0VsdEU/Aware_01_Choreo-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01TFFreDdlSVp3dGc/Aware_01_Choreo-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>随着元素转场到视图，它们及其周围环境以一种可以定义它们关系的方式进行动画编排。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01QVYxZ3NITnJfUjA/Aware_02_MoveAway-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RFdjQWE4ZXBseWM/Aware_02_MoveAway-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>材质元素可以推移其它材质元素。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RHpoUVJ2UEk0cWc/Aware_03_Magnets-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01YXR3cjNJeUdRNG8/Aware_03_Magnets-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>元素可以吸附到其它元素上，彼此接近并与之会合。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">意图</h4>

材质的运动可以将焦点在正确的时间引导到正确的位置。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01YmV5SERQVU0wQjQ/Intentional_01_Focus-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01SDNmSjRhbE9FNVU/Intentional_01_Focus-v3.mp4" type="video/mp4">
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>转场动画可以帮助引导用户进行下一步交互。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01SjhfQzB4QmI1WUk/Intentional_03_Disabled-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01RF9qdXlyMC1ETDA/Intentional_03_Disabled-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>通过运动可以传达出不同的信号，比如是否这个动作不可完成。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Y09iZVJNcktPalE/Intentional_02_Ring-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01akJiWVBnT3Bkc1U/Intentional_02_Ring-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>动画可以帮助将焦点放在需要用户注意的元素上。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="trans" style="color: #00bcd4">优秀转场的关键</h2>

成功的动画设计拥有以下特性：

<h4 style="color:#00bcd4">运动要迅速</h4>

交互不应使用户等待的时间超过必要的时间

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01emlGOWRnRkpMOVk/GoodTransition_QuickDo-v4.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01aHJmMm9aR3JvazQ/GoodTransition_QuickDo-v4.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>迅速的动画无需让用户必须等待其完成。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01SEVWZVRRbk40ZDA/GoodTransition_QuickDont-v4.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01bDBVZE5ndzctZW8/GoodTransition_QuickDont-v4.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>许多元素交错和缓慢的动作将延长动画的持续时间。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">运动要清晰</h4>

转场动画应该清晰，简介，连贯。应避免一次做太多事情。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01UlJKVG9BVVFuMHM/GoodTransition_ClearDo-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01NDkzU2FaYlFHMXM/GoodTransition_ClearDo-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>保持一个清晰的路径进入下一个视图，尽管元素被编为一组。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01UlJKVG9BVVFuMHM/GoodTransition_ClearDo-v3.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01NDkzU2FaYlFHMXM/GoodTransition_ClearDo-v3.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>当多个元素在不同方向或交叉路径上移动时，转场可能会令人困惑。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>

<h4 style="color:#00bcd4">运动要连贯</h4>

材质元素由速度，反应和用意统一起来。任何自定义的动画体验应在整个程序中保持一致。

<section style="margin-bottom: 30px">
<figure style="width: 90%;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01WjlzM09rd2Y2WVE/GoodTransition_Cohesive-v4.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01eG45MUV2blJQTWc/GoodTransition_Cohesive-v4.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="padding: 10px;margin-top:10px">
	<p>即使这些应用有着不同的功能，它们相似的动画体验使他们感觉这些交互彼此相关。</p>
	</figcaption>
</figure>
</section>

<hr style="height:1px; margin: 50px 0;"></hr>

<h2 id="meanani" style="color: #00bcd4">动画的含义</h2>

这些运动模式的好处可以从以下两个实例中发现，遵循这些模式的范例和未遵循这些模式的范例相比较。

<section style="margin-bottom: 30px">
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01MU04ZGg3WjB1MXM/ImplicationsDo-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01Um1wdzhBR1ZuYVE/ImplicationsDo-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #4caf50;padding: 10px;margin-top:10px">
	<p style="color: #2e7b32;margin-bottom: 0.3em;">正确</p>
	<p>在转场期间，用户被引导到下一个视图。物体表面的变化反应了层级关系。后台加载降低了感知延迟。</p>
	</figcaption>
</figure>
<figure style="width: 45%;float: left;margin-right: 20px;">
	<div>
	<video loop="" preload="auto" tabindex="0" width="100%" height="100%" controls="">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01N0xBbXNTVGtrM2c/ImplicationsDont-v2.webm" type="video/webm">
	<source src="https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B14F_FSUCc01anJjQkt4QS1GRzQ/ImplicationsDont-v2.mp4" type="video/mp4">
	</video>
	</div>
	<figcaption style="border-top:15px solid #d32f2f;padding: 10px;margin-top:10px">
	<p style="color: #d32f2f;margin-bottom: 0.3em;">错误</p>
	<p>由于没有转场的发生和确切的焦点，我们无从发现新视图如何与之前视图相关联。无法表达出任何层级关系。加载符的出现过于明显的体现加载的动作。</p>
	</figcaption>
</figure>
<div style="clear: both;"></div>
</section>
