# Mun — Real-Time Agentic Conversational AI

Mun is a fully local, real-time conversational AI system being developed as an NC State CSC 490 Independent Study project.

The project explores how conversational AI agents can maintain context, use memory, respond with consistent personality, and support natural spoken interaction while running locally.

## Current Architecture

Microphone → VAD → STT → Conversation Manager → LLM → TTS → Audio

## Technologies

- Python
- Llama 3.2
- Ollama
- LiveKit
- Moonshine / Faster-Whisper
- Kokoro TTS
- Voice Activity Detection
- Structured Outputs

## Current Work

- Real-time speech interaction
- Conversational state and memory
- Personality-driven response behavior
- Turn detection and interruptions
- Local inference
- Latency benchmarking
- Edge deployment exploration

## Goal

Develop Mun into an autonomous, real-time conversational agent capable of running locally on PC and edge hardware.

> This repository is a public project showcase. The primary development repository is private.
