```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "Faites quelque chose de nouveau. Repoussez les limites. Swiftian est une plateforme interactive et organisée pour apprendre Swift de manière créative."
keywords: "Swiftian, Swift, SwiftUI, iOS, codage créatif, apprendre Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Votre navigateur ne supporte pas la balise vidéo.
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

Faites quelque chose de nouveau. Repoussez les limites.  
Le voyage commence ici.

- [Créer Explorer →](/coding/)
- [Construire Votre Univers →](/universe/)
- [Bougez au Rythme →](/groove/)
- [Fait pour les Créateurs →](/creators/)

---
<footer>
  <small><a href="/privacy/">Politique de Confidentialité</a></small>
</footer>
```