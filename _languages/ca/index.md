```markdown
---
layout: default
title: "Pensa en Swift."
permalink: /
description: "Crea alguna cosa nova. Trenca límits. Swiftian és una plataforma interactiva i curada per aprendre Swift de manera creativa."
keywords: "Swiftian, Swift, SwiftUI, iOS, programació creativa, aprendre Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    El teu navegador no suporta l'etiqueta de vídeo.
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

Crea alguna cosa nova. Trenca límits.  
El viatge comença aquí.

- [Crea Explora →](/coding/)
- [Construeix el teu Univers →](/universe/)
- [Mou-te amb el Ritme →](/groove/)
- [Fet per a Creadors →](/creators/)

---
<footer>
  <small><a href="/privacy/">Política de Privacitat</a></small>
</footer>
```