```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "Make something new. Push boundaries. Swiftian je kurirana, interaktivna platforma za kreativno učenje Swifta."
keywords: "Swiftian, Swift, SwiftUI, iOS, kreativno kodiranje, učenje Swifta"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Vaš preglednik ne podržava video tag.
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

Napravite nešto novo. Pomičite granice.  
Putovanje počinje ovdje.

- [Kreiraj Istraži →](/coding/)
- [Izgradi Svoj Svemir →](/universe/)
- [Pokreni se uz Ritam →](/groove/)
- [Stvoreno za Kreatore →](/creators/)

---
<footer>
  <small><a href="/privacy/">Politika privatnosti</a></small>
</footer>
```