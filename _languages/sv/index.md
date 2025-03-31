```markdown
---
layout: default
title: "Tänk Swift."
permalink: /
description: "Skapa något nytt. Pressa gränser. Swiftian är en kuraterad, interaktiv plattform för att lära sig Swift på ett kreativt sätt."
keywords: "Swiftian, Swift, SwiftUI, iOS, kreativ kodning, lär dig Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Din webbläsare stöder inte videotaggen.
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

Skapa något nytt. Pressa gränser.  
Resan börjar här.

- [Skapa Utforska →](/coding/)
- [Bygg ditt Universum →](/universe/)
- [Rör dig med Takten →](/groove/)
- [Skapat för Skapare →](/creators/)

---
<footer>
  <small><a href="/privacy/">Integritetspolicy</a></small>
</footer>
```