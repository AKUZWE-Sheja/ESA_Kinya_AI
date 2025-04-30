# ESA_kinya_ai 🌍🗣️  
*A Kinyarwanda Voice Assistant with a Local Heart and Global Vision*

> “Technology speaks a thousand languages, but it sings when it speaks your own.”

ESA_kinya_ai is more than just code—it's a whisper of heritage turned into a digital echo. It's a locally-run voice assistant that understands and responds in Kinyarwanda, bringing speech recognition (STT), natural language processing (NLP), and text-to-speech (TTS) together in one graceful dance. Whether you're a Rwandan developer, a linguist at heart, or simply someone who wants to hear your mother tongue reflected in tech—this project is for you.

Demo Screenshot 
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/f99c74f7-1673-49fb-8fbc-85526c824cd8" />


## Features ✨

- 🎙️ **Speech-to-Text (STT)** with NeMo’s Conformer model, tuned for the musicality of Kinyarwanda.
- 🔊 **Text-to-Speech (TTS)** with the KinyaTTS VITS2 model—because our voices deserve to be heard, clearly and beautifully.
- 💬 **Natural Language Understanding** so your assistant doesn’t just listen, it *understands*.
- 🖥️ **Gradio-powered Interface** with:
  - 🎧 Microphone input
  - 📁 Audio file upload
  - 🔁 Automatic response playback
- 🌐 Ready to deploy, or remix into something even more magical.

  ## Installation 🛠️

### Prerequisites

- Python ≥ 3.8  
- pip (Python package manager)  
- (Optional) An NVIDIA GPU for extra speed 🏎️

### Setup

```bash
git clone https://github.com/AKUZWE-Sheja/ESA_Kinya_AI.git
cd kinyarwanda_Voice_AI
pip install -r requirements.txt
```
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. ✨ First time? Don’t worry—the models download automatically.

```bash
ASR: mbazaNLP/Kinyarwanda_nemo_stt_conformer_model
TTS: Pre-trained KinyaTTS model
```

### Usage 🚀

Running the Web Interface

```bash
python interface.py
```
The interface will launch at:

```bash
http://localhost:7860
```

How it works:

🎤 Speak or upload Kinyarwanda audio → 🧠 NLP processes your words → 🔈 Assistant responds out loud.

It’s that seamless.

### Project Structure 📂
```bash
.
├── interface.py        # Gradio web interface
├── assistant.py        # The beating heart of the assistant
├── stt_module.py       # Converts voice to text
├── tts_module.py       # Speaks responses
├── nlp_module.py       # Understands meaning and context
├── audio_samples/      # Example inputs
├── outputs/            # Assistant-generated replies
└── requirements.txt    # All the magic beans (dependencies)
```

### Requirements
```bash
gradio>=3.0
torch>=1.10
torchaudio>=0.10
nemo_toolkit[asr]>=1.7
soundfile>=0.10
huggingface_hub>=0.10
numpy>=1.21
matplotlib>=3.5  # Required by some NeMo components
```
### Contributing – Let's Build This Together 🤝
Found a bug? Have an idea? Or just want to lend your spark?
Feel free to open a PR or issue for:

- 🐞 Bug fixes
- 🌟 New features
- 📚 Better docs

Your creativity is welcome here.

### ⚠️ Limitations
- Needs quiet audio for best results
- Limited intents (but easily expandable)
- Some models must be pre-initialized before TTS kicks in

### 📚 Resources and Credits
- STT Model: https://huggingface.co/mbazaNLP/Kinyarwanda_nemo_stt_conformer_model
- TTS Engine: https://github.com/anzeyimana/KinyaTTS
- Gradio Interface: https://gradio.app/
- NVIDIA NeMo: https://github.com/NVIDIA/NeMo
- Audio Processing: https://github.com/jiaaro/pydub, https://pytorch.org/audio/stable/index.html
- STT model: https://github.com/agent87/RW-DEEPSPEECH-API

### 🙏 Acknowledgements
- Rwanda MIT Research Team – for open-sourcing KinyaTTS
- Hugging Face – for hosting and distributing models
- NVIDIA – for the NeMo framework
