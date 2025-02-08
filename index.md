---
title: Welcome to Swiftian
layout: default
---

<style>
/* Floating Music Button */
#music-container {
    position: fixed;
    top: 20px;
    right: 20px;
    display: flex;
    align-items: center;
    gap: 8px;
    z-index: 1000;
}

#music-button {
    background-color: #6200ea;
    color: white;
    border: none;
    padding: 10px 16px;
    font-size: 14px;
    cursor: pointer;
    border-radius: 20px;
    transition: background 0.3s ease;
}

#music-button:hover {
    background-color: #3700b3;
}

/* Small Loop Toggle */
#loop-toggle {
    width: 24px;
    height: 24px;
    background-color: #444;
    color: white;
    border: none;
    font-size: 12px;
    cursor: pointer;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.3s ease;
}

#loop-toggle.active {
    background-color: #ff9800;
}

#loop-toggle:hover {
    background-color: #666;
}
</style>

<!-- Floating Music Controls -->
<div id="music-container">
    <button id="music-button">🎵 Play</button>
    <button id="loop-toggle" title="Loop off">🔁</button>
</div>

<audio id="background-music">
    <source src="/assets/music/Mixea_MediumNeutral_Swiftian Groove.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

<script>
document.addEventListener("DOMContentLoaded", function() {
    const musicButton = document.getElementById("music-button");
    const loopToggle = document.getElementById("loop-toggle");
    const music = document.getElementById("background-music");

    let isPlaying = false;
    let isLooping = false;

    musicButton.addEventListener("click", function() {
        if (isPlaying) {
            music.pause();
            musicButton.innerHTML = "🎵 Play";
        } else {
            music.play();
            musicButton.innerHTML = "⏸ Pause";
        }
        isPlaying = !isPlaying;
    });

    loopToggle.addEventListener("click", function() {
        isLooping = !isLooping;
        music.loop = isLooping;
        loopToggle.classList.toggle("active", isLooping);
        loopToggle.title = isLooping ? "Loop on" : "Loop off";
    });
});
</script>

---

# 🚀 Welcome to Swiftian

**Swiftian** is a coding education platform where you can learn Swift and build your own projects.

## 🌟 Features
- 📖 Learn Swift with interactive examples
- 🛠️ Build and test Swift projects in real-time
- 🎨 Create your own productivity tools with Swift
- 🌍 Share your creations with the community

## ✨ Why Swiftian?
> "Think Swift, Code Fast."  
Swiftian is designed to make learning Swift easy and fun, with hands-on projects that help you build real-world applications.

---

## 📌 Start Learning Today!
[🚀 Get Started](https://swiftian.com/get-started)

📚 Read the [Documentation](https://swiftian.com/docs)  
💬 Join the Community (Coming Soon!)  

---

### 🎨 **Dark Mode Support**
<style>
@media (prefers-color-scheme: dark) {
  body {
    background-color: #121212;
    color: #ffffff;
  }
  a {
    color: #bb86fc;
  }
}
</style>

---

🔹 **Swiftian - Think Swift.**  
📌 Made with ❤️ by the Swiftian Team.
