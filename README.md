# VoxGroup-AI

**Benchmark and Toolkit for AI Transcription of Multi-Speaker Focus Groups**

VoxGroup-AI is an applied research and engineering project focused on evaluating the capabilities and limitations of artificial intelligence systems in transcribing, diarizing, and analyzing focus group recordings with multiple speakers.

The project investigates real-world audio scenarios involving 8 to 10 participants, overlapping speech, interruptions, informal language, accents, emotional intensification, noisy environments, and complex turn-taking patterns.

## Objectives

1. Evaluate the performance of different AI transcription models in multi-speaker focus group contexts.
2. Compare transcription accuracy, speaker diarization quality, timestamp reliability, and robustness under noisy or overlapping speech conditions.
3. Identify failure modes in automatic speech recognition and diarization systems.
4. Develop a reproducible pipeline for preprocessing audio, generating transcriptions, normalizing outputs, and producing qualitative research reports.
5. Explore how AI can assist in sentiment analysis, emotional intensity detection, discourse analysis, and identification of key qualitative themes.

## Research Context

Focus groups are widely used in qualitative research, public opinion studies, market research, social diagnosis, and policy evaluation. However, transcribing these recordings is time-consuming, expensive, and prone to inconsistency.

Modern AI models can accelerate this process, but their limitations become more visible when dealing with multiple simultaneous speakers, interruptions, low-quality audio, regional vocabulary, and emotionally charged speech.

This project aims to document these limitations systematically and build practical workflows for researchers.

## Core Research Questions

* How accurately can AI transcribe group discussions with 8 to 10 speakers?
* How reliable is speaker diarization when participants interrupt or speak over one another?
* Which models perform better under noisy, informal, and emotionally intense speech conditions?
* Can AI detect emotional intensification, frustration, enthusiasm, hesitation, irony, or conflict in group conversations?
* How should AI-generated transcripts be reviewed, corrected, and transformed into useful qualitative reports?
* What are the ethical and methodological limits of using AI in qualitative transcription?

## Planned Backends

The project is designed to compare multiple transcription and diarization backends:

* OpenAI Speech-to-Text API
* OpenAI diarized transcription models
* NVIDIA Riva / Parakeet ASR
* Whisper / faster-whisper
* WhisperX with diarization
* Local and hybrid transcription workflows

## Expected Outputs

* Raw transcription files
* Cleaned transcripts
* Speaker-segmented transcripts when available
* Approximate turn-based transcripts when diarization is unavailable
* Qualitative summaries
* Sentiment and emotional intensity reports
* Model comparison tables
* Error analysis reports
* Reproducible benchmark methodology

## Ethical Guidelines

This project does not publish raw audio from real participants.

All real-world transcripts must be anonymized before public use. Personal names, addresses, institutions, and sensitive identifiers should be removed or replaced with neutral markers.

The project is intended to support qualitative researchers, not replace human interpretation. AI-generated transcripts and analyses must be reviewed before being used in formal reports.

## Status

Early development.

The first experimental phase compares practical transcription pipelines for Portuguese-language focus group recordings involving multiple speakers and overlapping speech.
