Here's the markdown content translated into Romanian, while preserving the markdown structure:

```markdown
---
layout: default
title: "Gândește Swift."
permalink: /
description: "Creează ceva nou. Împinge limitele. Swiftian este o platformă curată și interactivă pentru a învăța Swift creativ."
keywords: "Swiftian, Swift, SwiftUI, iOS, codare creativă, învață Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Browserul tău nu suportă eticheta video.
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

Creează ceva nou. Împinge limitele.  
Călătoria începe aici.

- [Creează Explorează →](/coding/)
- [Construiește-ți Universul →](/universe/)
- [Mișcă-te pe Ritm →](/groove/)
- [Creat pentru Creatori →](/creators/)

---
<footer>
  <small><a href="/privacy/">Politica de Confidențialitate</a></small>
</footer>
```