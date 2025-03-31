```markdown
---
layout: default
title: "Gondolkodj Swift módra."
permalink: /
description: "Alkoss valami újat. Lépj át határokat. A Swiftian egy gondosan összeállított, interaktív platform a Swift kreatív tanulásához."
keywords: "Swiftian, Swift, SwiftUI, iOS, kreatív kódolás, tanulj Swiftet"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    A böngésződ nem támogatja a videó tag-et.
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

Alkoss valami újat. Lépj át határokat.  
Az utazás itt kezdődik.

- [Alkoss Fedezz fel →](/coding/)
- [Építsd meg az Univerzumod →](/universe/)
- [Mozogj a Ritmussal →](/groove/)
- [Alkotóknak készült →](/creators/)

---
<footer>
  <small><a href="/privacy/">Adatvédelmi irányelvek</a></small>
</footer>
```