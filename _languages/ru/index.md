```markdown
---
layout: default
title: "Думай по-Свифтовски."
permalink: /
description: "Создавай что-то новое. Раздвигай границы. Swiftian - это курируемая, интерактивная платформа для творческого изучения Swift."
keywords: "Swiftian, Swift, SwiftUI, iOS, творческое кодирование, изучение Swift"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Ваш браузер не поддерживает видео тег.
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

Создавай что-то новое. Раздвигай границы.  
Путешествие начинается здесь.

- [Создавай и Исследуй →](/coding/)
- [Строй свою Вселенную →](/universe/)
- [Двигайся с Ритмом →](/groove/)
- [Создано для Творцов →](/creators/)

---
<footer>
  <small><a href="/privacy/">Политика конфиденциальности</a></small>
</footer>
```