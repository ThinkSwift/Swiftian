```markdown
---
layout: default
title: "Think Swift."
permalink: /
description: "कुछ नया बनाएं। सीमाओं को पार करें। Swiftian स्विफ्ट को रचनात्मक रूप से सीखने के लिए एक क्यूरेटेड, इंटरैक्टिव प्लेटफॉर्म है।"
keywords: "Swiftian, Swift, SwiftUI, iOS, क्रिएटिव कोडिंग, स्विफ्ट सीखें"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    आपका ब्राउज़र वीडियो टैग का समर्थन नहीं करता।
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

कुछ नया बनाएं। सीमाओं को पार करें।  
यात्रा यहां से शुरू होती है।

- [Create Explore →](/coding/)
- [Build Your Universe →](/universe/)
- [Move with the Beat →](/groove/)
- [Made for Creators →](/creators/)

---
<footer>
  <small><a href="/privacy/">गोपनीयता नीति</a></small>
</footer>
```