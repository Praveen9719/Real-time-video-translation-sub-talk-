# Real-time-video-translation-sub-talk-

# 🎙️ Voice Assistant with Video & Audio Processing

A Python-based voice assistant that integrates **speech recognition**, **real-time translation**, and **video/audio processing** features using:

- [pygame](https://www.pygame.org) for audio playback
- [speech_recognition](https://pypi.org/project/SpeechRecognition/) for speech-to-text
- [googletrans](https://pypi.org/project/googletrans/) for translation
- [moviepy](https://zulko.github.io/moviepy/) for extracting and editing audio/video

---

## 📌 Features
- 🎤 Convert speech to text
- 🌎 Translate text to multiple languages
- 🎬 Extract audio from video files
- 🔊 Play audio with `pygame`
- 🛠 Thread-safe audio processing (fixes `WinError 32` issues on Windows)
