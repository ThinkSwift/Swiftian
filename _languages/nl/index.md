```markdown
---
layout: default
title: "Denk Swift."
permalink: /
description: "Maak iets nieuws. Verleg grenzen. Swiftian is een samengestelde, interactieve platform voor het creatief leren van Swift."
keywords: "Swiftian, Swift, SwiftUI, iOS, creatieve codering, leer Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Je browser ondersteunt de video tag niet.
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

Maak iets nieuws. Verleg grenzen.  
De reis begint hier.

- [Creëer Verken →](/coding/)
- [Bouw Je Universum →](/universe/)
- [Beweeg met de Beat →](/groove/)
- [Gemaakt voor Makers →](/creators/)

---
<footer>
  <small><a href="/privacy/">Privacybeleid</a></small>
</footer>
```