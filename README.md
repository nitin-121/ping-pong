# 🏓 Ping Pong - Android Game

A neon-styled Ping Pong game built with HTML5 Canvas + Apache Cordova, packaged as an Android APK.

## 🎮 Features

- **Neon-styled paddles** — cyan (player) vs pink (CPU)
- **Touch controls** — swipe/drag to move your paddle
- **Smart AI opponent** — adapts difficulty to ball speed
- **Score tracking** — first to 7 wins
- **Speed progression** — ball accelerates on each paddle hit
- **Particle effects** — on paddle collisions
- **Sound effects** — Web Audio API beeps
- **Start screen & Game Over** — with replay button

## 📲 Installation

1. Download `releases/PingPong.apk` (3.4 MB)
2. Transfer to your Android phone
3. Enable **Settings → Security → Unknown Sources**
4. Install and play!

## 🛠️ Tech Stack

- **HTML5 Canvas** — game rendering
- **Apache Cordova 13** — Android wrapper
- **Android SDK 36** — build tools
- **Gradle 8.14** — build system
- **OpenJDK 17** — Java runtime

## 🎯 How to Play

1. Tap **"TAP TO START"** to begin
2. **Swipe or drag** on the screen to move your left paddle
3. Bounce the ball past the CPU's paddle to score
4. First player to reach **7 points** wins!

## 📁 Project Structure

```
├── www/index.html          # Game source (HTML5/JS/CSS)
├── platforms/android/      # Cordova Android project
├── releases/PingPong.apk   # Ready-to-install APK
├── config.xml              # Cordova config
└── package.json            # Cordova dependencies
```

## 🔨 Build from Source

```bash
# Prerequisites: JDK 17, Android SDK 36, Gradle, Cordova
export JAVA_HOME=/path/to/jdk17
export ANDROID_HOME=/path/to/android-sdk

cordova platform add android
cordova build android

# APK output: platforms/android/app/build/outputs/apk/debug/app-debug.apk
```

## 📄 License

MIT
