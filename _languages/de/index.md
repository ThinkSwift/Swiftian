```markdown
layout: default
title: "Denke Swift."
permalink: /
description: "Erschaffe etwas Neues. Grenzen überschreiten. Swiftian ist eine kuratierte, interaktive Plattform zum kreativen Lernen von Swift."
keywords: "Swiftian, Swift, SwiftUI, iOS, kreatives Programmieren, Swift lernen"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Ihr Browser unterstützt das Video-Tag nicht.
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

Erschaffe etwas Neues. Grenzen überschreiten.  
Die Reise beginnt hier.

- [Erstellen Erkunden →](/coding/)
- [Baue Dein Universum →](/universe/)
- [Bewege dich im Takt →](/groove/)
- [Für Kreative gemacht →](/creators/)

---
<footer>
  <small><a href="/privacy/">Datenschutzrichtlinie</a></small>
</footer>
```