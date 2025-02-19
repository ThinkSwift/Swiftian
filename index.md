---
title: Welcome to Swiftian
layout: default
---

<!-- Persistent Music Player -->
<iframe src="/player.html" id="music-iframe" style="display: none;"></iframe>

<style>
/* Floating Music Button */
#music-button {
    position: fixed;
    top: 20px;
    right: 20px;
    background: rgba(98, 0, 234, 0.9);
    color: white;
    border: none;
    padding: 12px 20px;
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
    border-radius: 25px;
    display: flex;
    align-items: center;
    gap: 10px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
    transition: all 0.3s ease;
    z-index: 1000;
}

#music-button:hover {
    background: rgba(55, 0, 179, 0.9);
    transform: scale(1.05);
}

/* Loop Active Style */
#music-button.loop-active {
    background: rgba(255, 152, 0, 0.9);
}

#music-icon {
    font-size: 18px;
}
</style>

<!-- Floating Music Button -->
<button id="music-button">
    <span id="music-icon">🎵</span> <span id="music-label">Swiftian Groove</span>
</button>

<script>
document.addEventListener("DOMContentLoaded", function() {
    const musicButton = document.getElementById("music-button");
    const musicFrame = document.getElementById("music-iframe").contentWindow;
    
    let isPlaying = false;

    // Play/Pause Toggle
    musicButton.addEventListener("click", function() {
        if (isPlaying) {
            musicFrame.postMessage("pause", "*");
            musicButton.innerHTML = "🎵 Swiftian Groove";
        } else {
            musicFrame.postMessage("play", "*");
            musicButton.innerHTML = "⏸ Swiftian Groove";
        }
        isPlaying = !isPlaying;
    });

    // Ensure iframe music remains persistent
    window.addEventListener("message", function(event) {
        if (event.data === "playing") isPlaying = true;
        if (event.data === "paused") isPlaying = false;
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
