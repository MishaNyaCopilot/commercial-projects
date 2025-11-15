# BadPressChecker

A sophisticated reputation monitoring system designed for proactive detection of negative press and online reputation risks. This commercial solution provides real-time alerts and automated analysis to help businesses maintain their brand integrity.

## Features

- **Telegram Bot Interface**: Intuitive management through a dedicated Telegram bot for keyword configuration and report delivery
- **Automated SERP Scanning**: Continuous monitoring of search engine results using multiple scraping providers
- **AI-Powered Analysis**: Advanced LLM-based classification of search results to identify potential reputation risks
- **Customizable Monitoring**: Flexible keyword management with enable/disable controls and ignore lists
- **Scheduled Reports**: Automated daily and hourly reporting with configurable time zones
- **On-Premises Deployment**: Full containerized solution deployable on local infrastructure for maximum security and control

## Technology Stack

- **Backend**: Python with aiogram framework
- **Database**: PostgreSQL for data persistence
- **AI/ML**: Ollama-powered LLM for intelligent content analysis
- **Scraping**: Integration with ScraperAPI, Scrapfly, and Checkly for robust data collection
- **Deployment**: Docker containerization with docker-compose orchestration

## Architecture Overview

The application consists of:
- Main bot service handling user interactions and scheduling
- LLM worker service for AI-powered content analysis
- PostgreSQL database for storing keywords, results, and configurations
- Multiple scraping providers for comprehensive search result collection

This solution demonstrates expertise in building scalable, AI-enhanced monitoring systems with enterprise-grade deployment capabilities.