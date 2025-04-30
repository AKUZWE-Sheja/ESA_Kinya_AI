# Kinyarwanda_Voice_AI 🇷🇼
Kinyarwanda Voice Assistant - A locally-run AI assistant that understands and speaks Kinyarwanda. Features speech recognition (STT), natural language processing, and text-to-speech (TTS) with Gradio web interface. Ideal for Rwandan developers, researchers, and language preservation efforts.

!Demo Screenshot 
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/f99c74f7-1673-49fb-8fbc-85526c824cd8" />


## Features ✨

- 🎙️ Speech-to-text for Kinyarwanda using NeMo Conformer model
- 🔊 Text-to-speech with custom KinyaTTS VITS2 model
- 💬 Natural language processing for question answering
- 🖥️ Gradio web interface with:
  - Microphone recording
  - Audio file upload
  - Automatic response playback
- 🌐 Ready for deployment

  ## Installation 🛠️

### Prerequisites
- Python 3.8 or higher
- pip package manager
- (Optional) NVIDIA GPU for faster inference

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Chloe-sys/kinyarwanda_Voice_AI.git
cd kinyarwanda_Voice_AI


2.Install dependencies:

```bash
pip install -r requirements.txt
Download models (automatic on first run):

ASR: mbazaNLP/Kinyarwanda_nemo_stt_conformer_model

TTS: Pre-trained KinyaTTS model


