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
 <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <small><a href="/privacy/">Privacy Policy</a></small>
    <span id="languageToggle" style="cursor: pointer; font-size: 1.2em;">🌐</span>
  </div>
  <div id="languageList" style="display: none; margin-top: 20px; font-size: 0.9em;">
    <ul style="list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fill, minmax(180px, 1fr)); gap: 4px;">
      <li><a href="/ar/">🇸🇦 ar - مرحبا</a></li>
      <li><a href="/ca/">🇪🇸 ca - Hola</a></li>
      <li><a href="/zh-hans/">🇨🇳 zh-hans - 你好</a></li>
      <li><a href="/zh-hant/">🇹🇼 zh-hant - 你好</a></li>
      <li><a href="/hr/">🇭🇷 hr - Bok</a></li>
      <li><a href="/cs/">🇨🇿 cs - Ahoj</a></li>
      <li><a href="/da/">🇩🇰 da - Hej</a></li>
      <li><a href="/nl/">🇳🇱 nl - Hallo</a></li>
      <li><a href="/fi/">🇫🇮 fi - Hei</a></li>
      <li><a href="/fr/">🇫🇷 fr - Bonjour</a></li>
      <li><a href="/de/">🇩🇪 de - Hallo</a></li>
      <li><a href="/el/">🇬🇷 el - Γεια</a></li>
      <li><a href="/he/">🇮🇱 he - שלום</a></li>
      <li><a href="/hi/">🇮🇳 hi - नमस्ते</a></li>
      <li><a href="/hu/">🇭🇺 hu - Helló</a></li>
      <li><a href="/id/">🇮🇩 id - Halo</a></li>
      <li><a href="/it/">🇮🇹 it - Ciao</a></li>
      <li><a href="/ja/">🇯🇵 ja - こんにちは</a></li>
      <li><a href="/ko/">🇰🇷 ko - 안녕하세요</a></li>
      <li><a href="/ms/">🇲🇾 ms - Hai</a></li>
      <li><a href="/no/">🇳🇴 no - Hei</a></li>
      <li><a href="/pl/">🇵🇱 pl - Cześć</a></li>
      <li><a href="/pt/">🇵🇹 pt - Olá</a></li>
      <li><a href="/ro/">🇷🇴 ro - Salut</a></li>
      <li><a href="/ru/">🇷🇺 ru - Привет</a></li>
      <li><a href="/sk/">🇸🇰 sk - Ahoj</a></li>
      <li><a href="/es/">🇪🇸 es - Hola</a></li>
      <li><a href="/sv/">🇸🇪 sv - Hej</a></li>
      <li><a href="/th/">🇹🇭 th - สวัสดี</a></li>
      <li><a href="/tr/">🇹🇷 tr - Merhaba</a></li>
      <li><a href="/uk/">🇺🇦 uk - Привіт</a></li>
      <li><a href="/vi/">🇻🇳 vi - Xin chào</a></li>
    </ul>
  </div>
</footer>

<script>
  document.getElementById('languageToggle').addEventListener('click', function () {
    const list = document.getElementById('languageList');
    list.style.display = list.style.display === 'none' ? 'block' : 'none';
  });
</script>
