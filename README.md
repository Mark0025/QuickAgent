# Quick Voice bot demo

## About
- **What it is:** A copy of Greg Kamradt's demo voice bot that listens, thinks with an AI model and talks back; Mark made no changes.
- **Business:** learning
- **Status:** inactive since 2024-03
- **Source:** agent research 2026-11-04

This is a alpha demo showing a bot that uses Text-To-Speech, Speech-To-Text, and a language model to have a conversation with a user.

This demo is set up to use [Deepgram](www.deepgram.com) for the audio service and [Groq](https://groq.com/) the LLM.

This demo utilizes streaming for sst and tts to speed things up.

Video tutorial coming soon

The files in `building_blocks` are the isolated components if you'd like to inspect them

```
python3 QuickAgent.py
```