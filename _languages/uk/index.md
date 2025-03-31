```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "Make something new. Push boundaries. Swiftian - це кураторська, інтерактивна платформа для творчого вивчення Swift."
keywords: "Swiftian, Swift, SwiftUI, iOS, creative coding, learn Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Ваш браузер не підтримує відео тег.
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

Зробіть щось нове. Розсувайте межі.  
Подорож починається тут.

- [Створюйте Досліджуйте →](/coding/)
- [Будуйте свій Всесвіт →](/universe/)
- [Рухайтеся в такт →](/groove/)
- [Створено для творців →](/creators/)

---
<footer>
  <small><a href="/privacy/">Політика конфіденційності</a></small>
</footer>
```