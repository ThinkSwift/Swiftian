---
layout: default
title: "Think Swift."
description: "Make something new. Push boundaries. Swiftian is a curated, interactive platform for learning Swift creatively."
keywords: "Swiftian, Swift, coding, iOS, creative coding, learn Swift"
permalink: /
---

# Swiftian

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

Make something new. Push boundaries.  
The journey starts here.

- [Create. Explore. →](/coding/)
- [Build Your Universe →](/universe/)
- [Move with the Beat →](/groove/)
- [Made for Creators →](/creators/)

---
