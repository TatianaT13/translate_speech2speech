# translate_speech2speech
# Audio NLP Pipeline with Transcription, Translation & TTS

 A complete Streamlit-based pipeline for processing audio files: automatic transcription, machine translation, evaluation with WER/CER/BLEU/METEOR, and text-to-speech synthesis.

## Features

- Upload & transcribe audio files (WAV/MP3)
- Translate text via Whisper or M2M100
- Evaluate transcription & translation accuracy (WER, CER, BLEU, METEOR)
- Generate speech from translated text with Tacotron2
- Clean & elegant Streamlit interface
- GPU-compatible for local or cloud inference

## Technologies Used

| Task            | Model                     | Framework |
|-----------------|---------------------------|-----------|
| Transcription   | Whisper / Wav2Vec2 / Vosk | HuggingFace, Vosk |
| Translation     | M2M100 / Whisper          | Transformers |
| Evaluation      | jiwer, nltk               | Python |
| Text-to-Speech  | Tacotron2-DDC             | Coqui TTS |
| UI              | Streamlit                 | Python |
| Audio I/O       | Pydub, Soundfile          | Python |

