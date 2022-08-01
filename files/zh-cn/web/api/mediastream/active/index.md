---
title: active
slug: Web/API/MediaStream/active
tags:
  - 参考
  - 媒体流
  - 属性
  - 接口
  - 活动
translation_of: Web/API/MediaStream/active
---
<p>{{APIRef("Media Capture and Streams")}}</p>

<p><strong><code>active</code></strong> 是 {{domxref("MediaStream")}} 接口的只读属性，返回布尔值，如果媒体流当前为活动状态时，返回 <code>true</code> ，否则返回 <code>false</code>。 至少有一条 {{domxref("MediaStreamTrack")}} 的媒体流不是{{domxref("MediaStreamTrack.ended")}} 状态时才认为是 <strong>活动的</strong> 。当所有轨道关闭时，媒体流的属性置为 <code>false。</code></p>

<h2 id="语法">语法</h2>

<pre class="syntaxbox">var <em>isActive</em> = <em>MediaStream</em>.active;</pre>

<h3 id="Value">Value</h3>

<p>布尔值，当媒体流当前为活动状态时为 <code>true</code> ; 否则为 <code>false</code>.</p>

<h2 id="样例">样例</h2>

<p>在这个例子中，使用{{domxref("MediaDevices.getUserMedia", "getUserMedia()")}}请求源为用户本地摄像机和麦克风的一条新流，当流可用时（即满足返回的{{jsxref("Promise")}}），根据该流当前是否处于活动状态来更新页面上的按钮。</p>

<pre class="brush: js">var promise = navigator.mediaDevices.getUserMedia({
  audio: true,
  video: true
});

promise.then(function(stream) {
  var startBtn = document.querySelector('#startBtn');
  startBtn.disabled = stream.active;
};)</pre>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>



<p>{{Compat("api.MediaStream.active")}}</p>