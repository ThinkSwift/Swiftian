```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "創造新事物。突破界限。斯威夫天是一個精選的互動平台，用於創意學習 Swift。"
keywords: "斯威夫天, Swift, SwiftUI, iOS, 創意編碼, 學習 Swift"
---

# 斯威夫天

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    您的瀏覽器不支持 video 標籤。
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

創造新事物。突破界限。  
旅程從這裡開始。

- [創造 探索 →](/coding/)
- [構建你的宇宙 →](/universe/)
- [隨著節拍移動 →](/groove/)
- [為創作者而生 →](/creators/)

---
<footer>
  <small><a href="/privacy/">隱私政策</a></small>
</footer>
```