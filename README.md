

---

# Shadow Follower 👁️🩸

**Shadow Follower** is a dark-fantasy, interactive generative typography simulation built entirely with HTML5 Canvas and Vanilla JavaScript. What appears to be a swarm of eldritch, crimson eyes floating in a void is actually an optical illusion constructed entirely from ominous words and phrases.

This project explores procedural generation, saccadic gaze tracking, and swarm mechanics to create an unsettling, living digital entity that watches your every move.

## ✨ The Experience

* **The Hive Mind:** The canvas features one giant "master" eye surrounded by 15 smaller satellite eyes. The entire swarm actively tracks your cursor (or touch input) across the screen.
* **Saccadic Glare:** Instead of smoothly tracking the mouse at all times, the eyes perform "saccades"—erratic, lightning-fast micro-movements and random wandering—mimicking a predatory, biological gaze.
* **Interactive Hive Blink:** Each eye blinks independently on its own randomized biological timer. However, clicking or tapping anywhere on the screen triggers a cascading "hive blink," forcing the entire swarm to blink in a synchronized, rippling wave.
* **The Maw:** At the bottom of the screen, a curved row of typographic "teeth" made of the word *"consume"* waits in the darkness.

## ⚙️ Key Features

* **Generative Eldritch Typography:** 100% of the artwork—the void background, the dark sclera, the crimson iris spokes, and the pitch-black pupils—is generated from a thematic dictionary of shadow-words (e.g., *"devour"*, *"abyss"*, *"sever"*, *"lurker"*). No images or textures are used.
* **High-Performance Architecture:** Rendering thousands of text strings every frame would normally destroy browser performance. This project circumvents that by rendering the complex "Master Eye" and the dense background to off-screen canvases just once upon initialization. The animation loop then dynamically scales, rotates, and masks these pre-rendered instances to maintain a smooth 60 FPS.
* **Procedural Eyelid Masking:** The predatory, sharp shape of the eyes is created using dynamic quadratic bezier curves that calculate the precise opening and closing states of the eyelids on every single frame.
* * the eyes of truth follows wherever you go , try moving cursor

Tech Stack

* **HTML5 Canvas:** For high-performance 2D rendering and clipping masks.
* **Vanilla JavaScript (ES6+):** For the object-oriented swarm logic, animation loop, and procedural text generation.
* **CSS3:** Minimal styling to ensure a seamless, full-screen void.

## 🚀 How to Run

This project requires zero dependencies, build tools, or frameworks.

1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. Move your mouse to guide the swarm's gaze, and click to trigger a hive blink.

---

### 📝 Short Description (For your GitHub "About" section)

Here is a short, punchy version tailored for the right-hand "About" sidebar of your repository (319 characters):

**Shadow Follower is a dark-fantasy generative typography simulation built in HTML5 Canvas. A swarm of crimson, eldritch eyes constructed entirely of ominous words actively tracks your cursor with erratic, predatory movements. Click anywhere to trigger a cascading hive-blink. No images, no libraries—just code and text.**
