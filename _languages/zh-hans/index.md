```markdown
---
layout: default
title: "思考 Swift。"
permalink: /
description: "创造新事物。突破界限。斯威夫天是一个为创意学习 Swift 而精心策划的互动平台。"
keywords: "斯威夫天, Swift, SwiftUI, iOS, 创意编程, 学习 Swift"
---

# 斯威夫天

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    您的浏览器不支持视频标签。
  </video>
  <span id="soundIcon" style="position: absolute; top: 10px; right: 10px; font-size: 24px; cursor: pointer;">🔇</span>
</p>

<script>
  const video = document.getElementById('logoVideo');
  const soundIcon = document.getElementById('soundIcon');

  video.addEventListener('click', function() {
    video.muted = !video.muted;
    soundIcon.textContent = video.muted ? "🔇" : "🔊"; 
  });

  soundIcon.addEventListener('click', function(event) {
    event.stopPropagation(); 
    video.muted = !video.muted;
    soundIcon.textContent = video.muted ? "🔇" : "🔊";
  });
</script>

创造新事物。突破界限。  
旅程从这里开始。

- [创造 探索 →](/coding/)
- [构建你的宇宙 →](/universe/)
- [随节拍移动 →](/groove/)
- [为创作者而生 →](/creators/)

---
<footer>
  <small><a href="/privacy/">隐私政策</a></small>
</footer>
```