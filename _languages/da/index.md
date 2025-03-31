```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "Make something new. Push boundaries. Swiftian er en kurateret, interaktiv platform til at lære Swift kreativt."
keywords: "Swiftian, Swift, SwiftUI, iOS, kreativ kodning, lær Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Din browser understøtter ikke video tagget.
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

Make something new. Push boundaries.  
Rejsen starter her.

- [Skab udforsk →](/coding/)
- [Byg dit univers →](/universe/)
- [Bevæg dig med rytmen →](/groove/)
- [Skabt til skabere →](/creators/)

---
<footer>
  <small><a href="/privacy/">Privatlivspolitik</a></small>
</footer>
```