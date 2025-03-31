Certainly! Below is the markdown content translated into Hebrew while preserving the markdown structure:

```markdown
---
layout: default
title: "תחשוב סוויפט."
permalink: /
description: "תיצור משהו חדש. תדחוף גבולות. Swiftian היא פלטפורמה אינטראקטיבית ומעוצבת ללמידת סוויפט בצורה יצירתית."
keywords: "Swiftian, סוויפט, SwiftUI, iOS, קידוד יצירתי, ללמוד סוויפט"
---

# Swiftian

<p align="center">
  <video id="logoVideo" autoplay loop muted playsinline preload="metadata" style="width: 100%; max-width: 640px; height: auto; cursor: pointer;">
    <source src="/assets/videos/logo.mp4" type="video/mp4">
    הדפדפן שלך אינו תומך בתג הווידאו.
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

תיצור משהו חדש. תדחוף גבולות.  
המסע מתחיל כאן.

- [צור חקור →](/coding/)
- [בנה את היקום שלך →](/universe/)
- [זוז עם הקצב →](/groove/)
- [נוצר עבור יוצרים →](/creators/)

---
<footer>
  <small><a href="/privacy/">מדיניות פרטיות</a></small>
</footer>
```

Note: The word "Swiftian" was left unchanged as per your instruction, but if it was intended to be replaced or translated differently, please let me know!