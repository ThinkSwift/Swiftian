```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "新しいものを作り出す。境界を押し広げる。スイフティアンは、Swiftを創造的に学ぶためのキュレーションされたインタラクティブプラットフォームです。"
keywords: "スイフティアン, Swift, SwiftUI, iOS, クリエイティブコーディング, Swiftを学ぶ"
---

# スイフティアン

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    お使いのブラウザはvideoタグをサポートしていません。
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

新しいものを作り出す。境界を押し広げる。  
旅はここから始まります。

- [Create Explore →](/coding/)
- [Build Your Universe →](/universe/)
- [Move with the Beat →](/groove/)
- [Made for Creators →](/creators/)

---
<footer>
  <small><a href="/privacy/">プライバシーポリシー</a></small>
</footer>
```