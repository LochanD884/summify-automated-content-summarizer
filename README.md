# 🤖 Summify — Automated Meeting Summarizer
## 📌 Overview
Summify is a practical AI-powered tool that converts long video, audio, or text meeting notes into short, meaningful summaries. It combines open-source video processing, powerful speech-to-text, and Google’s Gemini LLM to produce clear, structured outputs in plain text or Word format — ready to share.

## 🎯 Objectives
Save time by auto-summarizing lengthy meeting recordings.

Make online onboarding, webinars, or calls actionable.

Provide human-like summaries with clear bullet points.

Offer multiple output formats for easy distribution.

## 🔑 Key Features
Video to Audio: Extracts audio from video files using MoviePy.

Accurate Transcription: Uses AssemblyAI for speaker-labeled transcription.

AI Summaries: Summarizes large text with Gemini 2.0 Flash.

Flexible Outputs: Exports to .txt and .docx.

Chunking: Handles large transcripts with smart text chunking.

Cross-Platform: Runs locally or in Colab with minimal setup.

## ⚙️ How It Works
1️⃣ Input: Upload a video, audio, or text file.

2️⃣ Convert: If video, audio is extracted automatically.

3️⃣ Transcribe: Audio is sent to AssemblyAI for speech-to-text.

4️⃣ Summarize: Gemini generates a concise summary.

5️⃣ Output: Save results as text or Word files.

## 📂 Components
File	Purpose
summify.py	Main script (convert → transcribe → summarize → export)

.env	(Optional) Store API keys securely

requirements.txt	Lists Python dependencies

## 🧩 Technologies Used
Component	Technology

Video/Audio	Python, MoviePy

Transcription	AssemblyAI API

Summarization	Google Gemini (gemini-2.0-flash)

Export	python-docx

## 🗂️ Project Workflow
Step	Description

1️⃣	Clone the repo

2️⃣	Add your GOOGLE_API_KEY & ASSEMBLYAI_API_KEY

3️⃣	Install dependencies: pip install -r requirements.txt

4️⃣	Run: python summify.py

5️⃣	Follow prompts to select file type & export format

## ✅ Highlights
Works for video, audio, or plain text input.

Handles long transcripts with automatic chunking.

Simple, clear output structure with Markdown-ready formatting.

No complex setup if run in Colab — FFmpeg included.

## 📌 Requirements
API Keys

Google Generative AI

AssemblyAI

## 🗂️ Future Scope
✅ Integrate more LLM options (OpenAI, Claude, etc.)

✅ Add live progress indicators for long tasks.

✅ Support multi-language transcription.

✅ Deploy as a web app for non-technical users.
