Multimodal Emotion Analysis System

This project presents a multimodal emotion analysis system that combines speech recognition, acoustic emotion detection, and language-based sentiment analysis using state-of-the-art deep learning models. The system integrates multiple AI models to analyze human emotions from speech data more accurately.
The architecture consists of three main stages. First, speech emotion recognition is performed using a fine-tuned Wav2Vec2 model to capture acoustic emotional features from audio signals. Second, the Whisper model is used to convert speech into text through automatic speech recognition (ASR). Finally, the transcribed text is analyzed by a Llama-based language model to determine the emotional context and sentiment of the spoken content.
Each model was fine-tuned using different datasets optimized for its task. The Wav2Vec2 model was trained on an English Speech Emotion Recognition dataset, leveraging language-independent acoustic features. The Whisper model was fine-tuned using the Turkish Common Voice 17 dataset to improve speech recognition performance for Turkish speech. For text-based emotion classification, the Llama model was trained using the TReMo Turkish emotion dataset.
The system demonstrates how combining audio-based and text-based emotion analysis can improve the overall performance of emotion recognition tasks. This multimodal approach allows the system to capture both acoustic cues and linguistic information, leading to more robust emotion detection compared to single-modality methods.
This project was developed as a Computer Engineering graduation project at Yıldız Technical University.

Technologies Used
Python
PyTorch
HuggingFace Transformers
Wav2Vec2
Whisper
Llama
LoRA / QLoRA Fine-Tuning
