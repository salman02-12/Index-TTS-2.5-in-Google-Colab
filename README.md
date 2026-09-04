# 🎙️ Index-TTS 2.5 Voice Cloning Colab

This repository contains a simple, no-code Google Colab notebook to clone any voice completely for free using **Index-TTS 2.5**[cite: 1].

[![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=dU6lEq_AvV0)

## ✨ Features
This notebook allows you to easily generate text-to-speech audio with powerful customization:
* **Multi-Language Support**: Works in English, Chinese, Japanese, Spanish, and Arabic[cite: 1].
* **Instant Voice Cloning**: Only requires a clear, quiet 3 to 10-second audio clip to duplicate a voice[cite: 1].
* **Emotion Transfer**: Upload a secondary audio clip (like someone crying or yelling) to transfer that exact emotion to your main voice[cite: 1].
* **Emotion Sliders**: Mix emotions manually using sliders for happy, angry, or sad parameters[cite: 1].
* **Auto Emotion Detection**: Automatically detect the correct emotion from the context of your text.
* **Speed Control**: Use sliders to easily make the voice speak faster or slower[cite: 1].
* **Phoneme Control**: Use special phoneme codes to force the AI to pronounce specific words perfectly[cite: 1].

## 🚀 How to Use
1. Open the `.ipynb` file in Google Colab.
2. Ensure your hardware accelerator is turned on. Go to **Runtime > Change runtime type** and select **T4 GPU**[cite: 1].
3. Run **Cell 1** and **Cell 2** to install dependencies and download the Index-TTS models[cite: 1]. (This may take a few minutes[cite: 1]).
4. Navigate to **Cell 3**, type the text you want the AI to say, choose your language, and click play[cite: 1].
5. You will be prompted to upload your short reference audio file[cite: 1].
6. The AI will output a `.wav` file of your generated speech[cite: 1].

Explore Cells 4 through 9 for advanced emotion, speed, and pronunciation controls!

## 🤝 Credits
Powered by the [Index-TTS](https://github.com/index-tts/index-tts) project and [CoinNoin](https://www.youtube.com/@CoinNoin)[cite: 1].
