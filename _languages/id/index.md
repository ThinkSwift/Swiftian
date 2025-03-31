Sure, here is the translated markdown content in Indonesian, with the markdown structure preserved:

```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "Buat sesuatu yang baru. Dorong batasan. Swiftian adalah platform interaktif yang dikurasi untuk belajar Swift secara kreatif."
keywords: "Swiftian, Swift, SwiftUI, iOS, pemrograman kreatif, belajar Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Browser Anda tidak mendukung tag video.
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

Buat sesuatu yang baru. Dorong batasan.  
Perjalanan dimulai di sini.

- [Buat Jelajahi →](/coding/)
- [Bangun Semestamu →](/universe/)
- [Bergerak dengan Irama →](/groove/)
- [Dibuat untuk Kreator →](/creators/)

---
<footer>
  <small><a href="/privacy/">Kebijakan Privasi</a></small>
</footer>
```