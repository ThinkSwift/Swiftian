---
layout: default
title: "스위프티안 - Swiftian 공식 사이트"
description: "스위프티안은 창의적인 코딩 프로젝트와 스토리텔링을 통해 Swift를 배우는 인터랙티브 학습 플랫폼입니다."
keywords: "스위프티안, Swiftian, 스위프트, Swift, iOS, 코딩, 프로그래밍, 창의적 코딩"
permalink: /ko/
lang: ko
---

# 스위프티안

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Your browser does not support the video tag.
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

새로운 것을 만들어보세요.  
한계를 뛰어넘는 여정이 여기에서 시작됩니다.

- [창조하고 탐험하라 →](/ko/coding/)
- [나만의 우주 만들기 →](/ko/universe/)
- [비트와 함께 움직이기 →](/ko/groove/)
- [창작자들을 위한 공간 →](/ko/creators/)

---
<footer>
  <small><a href="/privacy/">개인정보 보호정책</a></small>
</footer>
