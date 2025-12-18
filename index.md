---
layout: default
lang: en
permalink: /
title: "English Accents"
description: "Learn English through authentic accents. Download English Accents on the App Store."
keywords: "English Accents, learn English, language learning, pronunciation, iOS app"
---

<div style="text-align: center; max-width: 600px; margin: 0 auto; padding: 2rem 1rem;">
  
  <h1 style="margin-bottom: 0.5rem;">English Accents</h1>
  <p style="color: #666; margin-bottom: 2.5rem;">Learn English through authentic voices</p>

  <!-- Hero Video -->
  <div style="margin-bottom: 2rem; position: relative;">
    <video 
      id="heroVideo"
      loop
      muted
      playsinline
      preload="metadata"
      style="
        width: 100%;
        max-width: 280px;
        object-fit: contain;
        background: #000;
        cursor: pointer;
        display: block;
        margin: 0 auto;
        border-radius: 1rem;
        box-shadow: 0 8px 30px rgba(0,0,0,0.15);
        aspect-ratio: 4/5;
      ">
      <source src="/assets/videos/Chillfriends_E06.mp4" type="video/mp4">
    </video>
    <button 
      id="playBtn" 
      type="button" 
      aria-label="Play"
      style="
        position: absolute; 
        left: 50%; 
        top: 50%; 
        transform: translate(-50%,-50%); 
        font-size: 2.5rem; 
        background: rgba(255,255,255,0.8); 
        border: none; 
        border-radius: 50%; 
        cursor: pointer; 
        z-index: 2; 
        width: 2.2em; 
        height: 2.2em; 
        display: flex; 
        align-items: center; 
        justify-content: center;
        box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      ">
      <span style="margin-left: 0.15em;">▶</span>
    </button>
  </div>

  <!-- App Store Badge -->
  <div style="margin-bottom: 3rem;">
    <a href="https://apps.apple.com/app/english-accents/id1281312028">
      <img src="/assets/images/download-on-the-app-store.svg" 
           alt="Download on the App Store" 
           style="height: 40px; display: block; margin: 0 auto;">
    </a>
  </div>

  <!-- Audio Section -->
  <div style="
    padding: 1.5rem;
    background: rgba(0,0,0,0.02);
    border-radius: 0.8rem;
    margin-bottom: 2rem;
  ">
    <button 
      id="audioPlayBtn"
      style="
        background: transparent;
        border: none;
        cursor: pointer;
        font-size: 1rem;
        padding: 0.5rem 0;
        margin-bottom: 0.75rem;
        color: inherit;
      ">
      ▶︎ Play full track
    </button>
    <audio id="audioPlayer" preload="none" style="display: none;">
      <source src="/assets/audios/Apologies We Forget to Say.mp3" type="audio/mpeg">
    </audio>
    <div style="font-size: 0.85rem; color: #888;">
      Available on 
      <a href="https://open.spotify.com/track/5HkrFa5czGAb4fEN8biPSB" style="text-decoration: none; color: inherit; border-bottom: 1px solid #ddd;">Spotify</a>
      <span style="margin: 0 0.3rem;">·</span>
      <a href="https://music.apple.com/album/apologies-we-forget-to-say/1859940737" style="text-decoration: none; color: inherit; border-bottom: 1px solid #ddd;">Apple Music</a>
    </div>
  </div>

</div>

<script>
  // Video controls
  const heroVideo = document.getElementById('heroVideo');
  const playBtn = document.getElementById('playBtn');

  // Try to autoplay muted video
  heroVideo.play().catch(() => {});

  playBtn.addEventListener('click', function() {
    heroVideo.muted = false;
    heroVideo.play();
    playBtn.style.display = 'none';
  });

  heroVideo.addEventListener('click', function() {
    if (playBtn.style.display === 'none') {
      heroVideo.pause();
      heroVideo.muted = true;
      playBtn.style.display = 'flex';
    }
  });

  // Audio controls
  const audioPlayer = document.getElementById('audioPlayer');
  const audioPlayBtn = document.getElementById('audioPlayBtn');
  let isPlaying = false;

  audioPlayBtn.addEventListener('click', function() {
    if (!isPlaying) {
      audioPlayer.play();
      audioPlayBtn.textContent = '⏸︎ Pause full track';
      isPlaying = true;
    } else {
      audioPlayer.pause();
      audioPlayBtn.textContent = '▶︎ Play full track';
      isPlaying = false;
    }
  });

  audioPlayer.addEventListener('ended', function() {
    audioPlayBtn.textContent = '▶︎ Play full track';
    isPlaying = false;
  });
</script>

---
{% include footer.html %}
