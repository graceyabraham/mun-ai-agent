# Mun — Real-Time Agentic Conversational AI

Mun is a fully local, real-time conversational AI system being developed as an NC State CSC 490 Independent Study project.

The project explores how conversational AI agents can maintain context, use memory, respond with consistent personality, and support natural spoken interaction while running locally.

## Why Mun?

Most conversational AI systems are designed around isolated prompt-and-response interactions. Mun explores what it takes to build a more continuous personal AI system: one that can maintain context, develop a consistent interaction style, remember relevant information over time, respond through natural speech, and eventually perceive and act in the physical world.

The project is focused on making that experience run locally, with an emphasis on responsiveness, privacy, and eventual edge deployment.

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

## Current Capabilities 

- Real-time spoken interaction
- Local LLM inference
- Streaming STT
- Neural TTS
- Conversational state
- Personality-driven response behavior
- Structured interaction classification

## In Progress

- Persistent memory
- Interruption handling
- Echo/self-hearing mitigation
- Latency optimization
- Proactive actions
- Edge deployment
- Physical embodiment and perception



## Goal

Develop Mun into a persistent, real-time personal AI capable of natural spoken interaction, memory, perception, and autonomous behavior while running locally on edge hardware. Long term, Mun will be extended into an embodied physical AI system capable of interacting with people and its environment.

> This repository is a public project showcase. The primary development repository is private.
