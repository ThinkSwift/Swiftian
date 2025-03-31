```markdown
---
layout: default
title: "فكر بـ Swift."
permalink: /
description: "اصنع شيئًا جديدًا. ادفع الحدود. Swiftian هو منصة تفاعلية ومنسقة لتعلم Swift بطريقة إبداعية."
keywords: "Swiftian, Swift, SwiftUI, iOS, البرمجة الإبداعية, تعلم Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    المتصفح الخاص بك لا يدعم علامة الفيديو.
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

اصنع شيئًا جديدًا. ادفع الحدود.  
تبدأ الرحلة هنا.

- [ابدأ الاستكشاف →](/coding/)
- [ابنِ عالمك →](/universe/)
- [تحرك مع الإيقاع →](/groove/)
- [مصمم للمبدعين →](/creators/)

---
<footer>
  <small><a href="/privacy/">سياسة الخصوصية</a></small>
</footer>
```