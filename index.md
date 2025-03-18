---
layout: default
title: "Think Swift."
permalink: /
description: "Make something new. Push boundaries. Swiftian is a curated, interactive platform for learning Swift creatively."
keywords: "Swiftian, Swift, SwiftUI, iOS, creative coding, learn Swift"
---

# Swiftian

<p align="center" style="position: relative; display: inline-block;">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 250px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <span id="soundIcon" style="
    position: absolute;
    bottom: 10px; right: 10px;
    font-size: 20px;
    background: rgba(0, 0, 0, 0.6);
    color: white;
    padding: 5px 8px;
    border-radius: 50%;
    cursor: pointer;
  ">🔇</span>
</p>

<script>
  const video = document.getElementById('logoVideo');
  const soundIcon = document.getElementById('soundIcon');

  function toggleSound() {
    video.muted = !video.muted;
    soundIcon.textContent = video.muted ? "🔇" : "🔊";
  }

  video.addEventListener('click', toggleSound);
  soundIcon.addEventListener('click', function(event) {
    event.stopPropagation(); // 비디오 클릭과 충돌 방지
    toggleSound();
  });
</script>


Make something new. Push boundaries.  
The journey starts here.

- [Create Explore →](/coding/)
- [Build Your Universe →](/universe/)
- [Move with the Beat →](/groove/)
- [Made for Creators →](/creators/)

---
<footer>
  <small><a href="/privacy/">Privacy Policy</a></small>
</footer>
