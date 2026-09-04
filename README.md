# 🎙️ Index-TTS 2.5: Free Voice Cloning & Emotion Control in Google Colab

This repository contains an easy-to-use Google Colab notebook for running **Index-TTS 2.5**. This AI allows you to clone any voice for completely free and manipulate the speaker's emotion, speed, and pronunciation using zero coding.

**🎥 Watch the Tutorial:** [How to Clone ANY Voice for FREE | Text to Speech AI](https://www.youtube.com/watch?v=dU6lEq_AvV0) by [@CoinNoin](https://www.youtube.com/@CoinNoin)

**🚀 Run in Colab:** [Open Google Colab Notebook](https://colab.research.google.com/drive/1dobJAb8FyXBymtg1eKU9WzTlqukaJE8W?usp=sharing)

---

## ✨ Features Supported in this Notebook

This notebook is divided into 9 easy-to-run cells:

1. **⚙️ Install Dependencies**: Sets up the `uv` package manager and clones the `index-tts` core repository.
2. **📥 Download Models**: Fetches the core IndexTTS-2.5 model weights needed for production generation.
3. **🗣️ Voice Cloning (Single Reference Audio)**: Upload a 3 to 10-second clear voice clip, and the AI will generate speech matching that exact voice in English, Chinese, Japanese, Spanish, or Arabic.
4. **🎭 Emotion Control (Audio Reference)**: Upload a base speaker voice and a second emotional voice (e.g., someone crying or yelling). The AI applies the emotion to your base voice!
5. **📊 Emotion Control via Vector Parameters**: Fine-tune emotions using sliders for *happy*, *angry*, and *sad*.
6. **🤖 Auto Emotion Detection**: Automatically infers the speaker's emotional state straight from the context of your text using Qwen models.
7. **📝 Emotion Description**: Tell the AI exactly how the speaker feels via a text prompt (e.g., "Overwhelming tears of joy and disbelief").
8. **⏱️ Speed Control**: Use sliders to speed up or slow down the generated speech.
9. **🔤 Exact Pronunciation Control**: Use CMU Phonemes (`<word|PHONEMES>`) to force precise pronunciations for specific words.

## 🛠️ How to Use

1. Open the [Colab link](https://colab.research.google.com/drive/1dobJAb8FyXBymtg1eKU9WzTlqukaJE8W?usp=sharing).
2. Go to **Runtime > Change runtime type** and ensure **T4 GPU** is selected.
3. Run **Cell 1** and **Cell 2** to install the dependencies and models.
4. Go to **Cell 3** (or whichever feature you want to use), type your text, pick your language, and hit Play. 
5. When prompted, upload your short reference `.wav` audio file.
6. The AI will output a downloadable `.wav` file with your generated voice!

## 🤝 Credits
* **Tutorial & Notebook Creator:** [CoinNoin](https://www.youtube.com/@CoinNoin)
* **Underlying AI Model:** [Index-TTS](https://github.com/index-tts/index-tts)
