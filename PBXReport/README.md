# PBX Report Bot

## Project Overview

A comprehensive automated reporting system for PBX call center analytics, designed for enterprise environments requiring secure, on-premises deployment. This solution provides real-time call center performance insights through automated Telegram notifications, featuring multi-server redundancy and persistent configuration management.

## Key Features

### 📊 Automated Analytics
- **Shift-based reporting**: Automated reports for first shift (15:00-19:00) and second shift (19:40-00:30) with Manila timezone
- **Multi-format delivery**: Excel spreadsheets with detailed agent statistics and PNG visualization charts
- **Real-time metrics**: Success/fail rates, talk time analysis, and agent performance tracking

### 🔒 Enterprise Security
- **On-premises deployment**: Fully containerized solution running on customer infrastructure
- **Secure API integration**: Direct connection to PBX servers without external data exposure
- **Role-based access control**: Admin-only configuration interface with granular permissions

### 🏗️ Robust Architecture
- **Multi-server redundancy**: Combines data from multiple PBX servers for high availability
- **Persistent configuration**: PostgreSQL database for all dynamic settings and user management
- **Automated scheduling**: Cron-based report generation with timezone-aware execution

## Technical Stack

- **Backend**: Python 3.13, AsyncIO, aiohttp
- **Database**: PostgreSQL with asyncpg driver
- **Bot Framework**: aiogram 3.x for Telegram integration
- **Data Processing**: pandas, matplotlib for analytics and visualization
- **Deployment**: Docker Compose with multi-service architecture
- **Monitoring**: Comprehensive logging and error handling

## Deployment & Infrastructure

### On-Premises Focus
This project was specifically designed for on-premises deployment in enterprise environments where data security and local infrastructure control are paramount. The solution runs entirely within the customer's network, ensuring:

- No external data transmission
- Full control over infrastructure and security policies
- Compliance with local data regulations
- Minimal external dependencies

### Containerized Architecture
- **Bot Service**: Handles Telegram interactions and admin management
- **Generator Service**: Processes PBX data and generates reports
- **Database Service**: Persistent storage for configuration and state
- **Automated orchestration**: Docker Compose for seamless deployment and scaling

## Business Impact

Successfully implemented for a commercial client requiring automated call center reporting with strict on-premises requirements. The system processes thousands of call records daily, providing management with actionable insights while maintaining complete data sovereignty within their infrastructure.

## Technologies Demonstrated

- Asynchronous programming with Python
- REST API integration and data aggregation
- Database design and async operations
- Telegram bot development with interactive interfaces
- Docker containerization and orchestration
- Cron job scheduling and timezone handling
- Data visualization and Excel report generation
- Enterprise-grade logging and error management

---

*This project showcases expertise in building secure, scalable solutions for enterprise environments with on-premises deployment requirements.*