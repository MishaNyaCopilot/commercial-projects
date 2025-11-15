# SpeechQA

A scalable on-premises Telegram bot for audio transcription and sales call analysis, built with microservices architecture.

## Overview

SpeechQA is an on-premises Telegram bot that processes audio files to generate transcriptions using advanced AI models. It supports batch processing, user management, and integrates with LLM-based analysis for sales call evaluations against predefined scripts, ensuring data privacy and control.

Key features:
- Audio transcription using Whisper AI
- Sales script comparison and scoring
- Admin panel for user management and statistics
- Queue-based processing for scalability
- On-premises deployment for enhanced security
- Docker containerized deployment

## Tech Stack

- **Backend**: Python (AsyncIO)
- **Bot Framework**: python-telegram-bot
- **AI Models**:
  - Whisper (faster-whisper) for transcription
  - Ollama with Gemma models for analysis
- **Database**: PostgreSQL
- **Queue**: Redis
- **Deployment**: Docker & Docker Compose
- **Infrastructure**: Local Telegram Bot API server

## Architecture

The application consists of multiple microservices:
- **Bot Service**: Handles Telegram interactions and user management
- **Whisper Worker**: Processes audio transcription tasks
- **LLM Worker**: Performs script analysis and scoring
- **Telegram Bot API**: Local server for enhanced API access

## Usage

- Send audio files to the bot for transcription
- Use admin commands for user management and monitoring
- Configure presets for different transcription settings
- Manage script templates for call analysis

## Requirements

- NVIDIA GPU for AI processing
- Ubuntu Server 24.04 or compatible
- Docker Engine with NVIDIA Container Toolkit