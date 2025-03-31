```markdown
---
layout: default
title: "Piensa en Swift."
permalink: /
description: "Crea algo nuevo. Empuja los límites. Swiftian es una plataforma interactiva y curada para aprender Swift de manera creativa."
keywords: "Swiftian, Swift, SwiftUI, iOS, codificación creativa, aprender Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Tu navegador no soporta la etiqueta de video.
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

Crea algo nuevo. Empuja los límites.  
El viaje comienza aquí.

- [Crear Explorar →](/coding/)
- [Construye Tu Universo →](/universe/)
- [Muévete al Ritmo →](/groove/)
- [Hecho para Creadores →](/creators/)

---
<footer>
  <small><a href="/privacy/">Política de Privacidad</a></small>
</footer>
```