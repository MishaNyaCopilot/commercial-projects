# Monitoring Bot

A Telegram-based monitoring system designed to track website availability, response status, and content changes. The bot provides real-time notifications and scheduled reports, making it suitable for operational monitoring and uptime control.

## Key Features

- **Multi-Provider Scraping**: Uses several external scraping services (Checkly, ScraperAPI, Scrapfly) to ensure reliable data collection.
- **Real-Time Alerts**: Sends immediate Telegram notifications when a monitored page becomes unavailable or returns an unexpected result.
- **Scheduled Reports**: Supports periodic summaries with current site status and recent events.
- **Flexible Configuration**: Each monitor can be customized with its own URL, check interval, expected response, and provider selection.
- **Secure Admin Controls**: Includes restricted-access commands for managing monitors, providers, and report schedules.
- **On-Premises Deployment**: Fully self-hosted using Docker and Docker Compose.

## Technology Stack

- **Backend**: Python using Aiogram framework  
- **Database**: PostgreSQL  
- **Queueing / Scheduling**: Internal asynchronous workers  
- **Scraping Providers**: Checkly, ScraperAPI, Scrapfly  
- **Containerization**: Docker and Docker Compose  
- **Logging & Diagnostics**: Integrated structured logging and health checks

## Use Cases

- Website uptime monitoring  
- Content-change detection  
- Operational alerting for small and medium businesses  
- Redundant monitoring using multiple providers  

This project demonstrates experience in building reliable, automated monitoring services with multi-provider integrations and asynchronous processing.