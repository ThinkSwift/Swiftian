```markdown
---
layout: default
title: "Pense Swift."
permalink: /
description: "Crie algo novo. Ultrapasse limites. Swiftian é uma plataforma interativa e curada para aprender Swift de forma criativa."
keywords: "Swiftian, Swift, SwiftUI, iOS, codificação criativa, aprender Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Seu navegador não suporta a tag de vídeo.
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

Crie algo novo. Ultrapasse limites.  
A jornada começa aqui.

- [Crie Explore →](/coding/)
- [Construa Seu Universo →](/universe/)
- [Mova-se com o Ritmo →](/groove/)
- [Feito para Criadores →](/creators/)

---
<footer>
  <small><a href="/privacy/">Política de Privacidade</a></small>
</footer>
```