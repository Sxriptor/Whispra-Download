<h1 align="center">
  <a href="https://crawlee.dev">
    <picture>
      <source
        media="(prefers-color-scheme: dark)"
        srcset="https://github.com/user-attachments/assets/5fd5f5ac-87a2-4051-83e2-8a3a52946e46"
      >
      <img
        alt="Whispra"
        src="https://github.com/user-attachments/assets/5fd5f5ac-87a2-4051-83e2-8a3a52946e46"
        width="300"
        height="100"
        style="margin-bottom:-4px;"
      >
    </picture>
  </a>
  <br>
  <small>Real Time Voice | Display Translation</small>
</h1>








<p align="center">
  <img src="https://img.shields.io/badge/version-1.8.8-white" alt="Downloads" style="max-width: 100%;">
    <img src="https://img.shields.io/badge/downloads-123-white" alt="Downloads" style="max-width: 100%;">
    <img src="https://img.shields.io/badge/discord-78 online-white" alt="Downloads" style="max-width: 100%;">
    <img src="https://img.shields.io/badge/stable-win 10/11-white" alt="Downloads" style="max-width: 100%;">
</p>


# Whispra Download

Public repo for downloading and installing **Whispra**, the real-time voice translation app.  
This repository provides easy access to the latest release installers, quick start guides, and troubleshooting resources.

<p align="center">
  <a href="https://whispra.xyz" target="_blank">
    <img src="https://img.shields.io/badge/website-whispra.xyz-white?style=for-the-badge" alt="Whispra Website">
  </a>
  <a href="https://account.whispra.xyz" target="_blank">
    <img src="https://img.shields.io/badge/account-account.whispra.xyz-white?style=for-the-badge" alt="Whispra Account">
  </a>
</p>

## ⚡ Introducing Whispra — Real-Time Voice, Text & Screen Translation  

Whispra is a next-generation desktop app that enables **real-time translation across voice, text, and screen** — powered by both **local** and **cloud-based AI models**.  

It captures your mic or speakers, detects the spoken language, translates it instantly, and plays it back through **ElevenLabs TTS**.  
You can also **translate any on-screen text** or **quickly translate copied/typed text** with one hotkey.  

Designed for **gamers, streamers, travelers, and remote teams**, Whispra combines cutting-edge local AI performance with seamless UX — giving you instant, private, and reliable translations even offline.  

---

## 💾 Download & Installation  

- **[Latest Release →](https://github.com/YOUR_ORG/whispra-download/releases/latest)**  
- Installers available for **Windows 10 / 11**  
- *(macOS and Linux builds coming soon)*  

> After installation, sign in with your Whispra account to sync preferences, device settings, and language profiles.

---

## 🧠 Model Architecture  

| Component | Technology | Description |
|------------|-------------|-------------|
| 🗣 **Speech Recognition** | Local **Whisper models** (CPU/GPU-accelerated) | Transcribes mic or system audio in real time. |
| 💬 **Language Understanding** | Local **GPT-based model** | Processes and reformats translated text, maintaining tone and context. |
| 🔊 **Text-to-Speech** | **ElevenLabs** | Generates natural, human-like playback in target languages. |
| 🪞 **Screen OCR** | **PaddleOCR (local)** | Detects and translates any text visible on your screen. |

All local models are bundled for **offline use**, with optional online fallback for enhanced accuracy.

---

## 🧩 System Requirements  

- **OS:** Windows 10/11 (64-bit)  
- **CPU/GPU:** Modern multi-core CPU; CUDA/DML GPU support optional  
- **Network:** Required for ElevenLabs TTS and cloud translation APIs  
- **Audio:** Microphone and speakers or headset  

---

## 🚀 Getting Started  

1. Download the installer from the [Releases page](https://github.com/YOUR_ORG/whispra-download/releases/latest).  
2. Run the setup wizard.  
3. Launch **Whispra** and sign in (or create an account).  
4. Select your preferred models (local or cloud).  
5. Configure your audio devices and start translating in real time.  

---

## 🔥 Core Features  

| Feature | Description |
|----------|-------------|
| 🎙 **Live Voice Translation** | Real-time bidirectional speech translation using Whisper + GPT. |
| 🖥 **Smart Overlay Mode** | Displays captions and translations on-screen with customizable positioning. |
| 🪞 **Screen Translation (OCR)** | Instantly capture and translate text from any active window. |
| ⚡ **Quick Translate (Text)** | Translate selected or clipboard text instantly via global hotkey. |
| 💻 **Local Model Support** | Run GPT and Whisper locally for privacy, speed, and offline use. |
| 🔊 **ElevenLabs TTS Playback** | Natural speech output in your chosen target language. |
| 🎮 **Gaming Optimized** | Minimal CPU/GPU load, low-latency I/O, and automatic audio routing. |
| 🧩 **Profile System** | Save and switch between device setups, model modes, and language pairs. |

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/ec446e09-89c3-4224-aa21-d323547b0711" width="48%" />
  <img src="https://github.com/user-attachments/assets/cc998929-3a75-43c1-b37b-c4947f3c1fdc" width="48%" />
</div>

---

## 🐛 Troubleshooting

### Common Issues

#### ❌ Microphone Access Denied

**Solution**: Grant microphone permissions in system settings
- **Windows**: Settings → Privacy → Microphone
- **macOS**: System Preferences → Security & Privacy → Microphone
- **Linux**: Check PulseAudio/ALSA permissions

#### ❌ API Key Validation Failed

**Solution**: Verify API keys are correct and have sufficient credits
- Check OpenAI account: [platform.openai.com/usage](https://platform.openai.com/usage)
- Check ElevenLabs account: [elevenlabs.io/subscription](https://elevenlabs.io/subscription)
- Check DeepInfra account: [deepinfra.com](https://deepinfra.com)

#### ❌ No Audio Output

**Solution**: Check virtual microphone setup
1. Try **📢 Test Virtual Mic** button
2. Verify other apps can see **"Virtual Microphone Output"** device
3. Check Windows audio settings for virtual microphone
4. Ensure VB-Audio Cable or similar virtual audio device is installed

#### ❌ Translation Not Working

**Solution**: Use debug console to identify issues
1. Click **Show Debug Console** to see real-time logs
2. Verify all API keys are configured correctly
3. Check selected models are available
4. Ensure internet connection for cloud providers
5. Check translation provider selection in Settings → Models

#### ❌ Overlay Not Showing

**Solution**: Troubleshoot overlay issues
1. Check if overlay is enabled in settings
2. Try a different hotkey if F11 conflicts with your game
3. Restart the application if overlay becomes unresponsive
4. Check overlay position settings

#### ❌ Local Models Not Working

**Solution**: Verify local model setup
1. Ensure Python is installed and accessible
2. Check PaddlePaddle installation (for OCR)
3. Verify Argos Translate models are downloaded
4. Check GPU acceleration settings if using GPU

### Debug Console

The debug console shows real-time information:
- API requests and responses
- Audio processing status
- Error messages and warnings
- Performance metrics
- Translation progress

Access it via: **Show Debug Console** button in the main interface

## 🧭 Resources  

- 📚 [Help Center](https://account.whispra.xyz/userguides)  
- 🐞 [Report a Bug or Request a Feature](https://account.whispra.xyz/report)  
- 💬 Community Discord *(coming soon)*  

---

## ⚖️ License  

This repository is for distribution purposes only.  
The Whispra application and bundled models are proprietary software © Whispra.  

---
