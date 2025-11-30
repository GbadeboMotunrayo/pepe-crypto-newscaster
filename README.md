# Crypto Newscaster AI

Automated crypto news reporting with three distinct character personas. Generates, renders, and publishes video content across multiple platforms.

## Features

- **3 Character System**: Profit Pete (Bull), Loss Lana (Bear), Trend Tori (Neutral)
- **Multi-Platform**: YouTube, TikTok, Instagram, Twitter
- **AI-Powered**: LLM scripts, TTS voices, avatar videos
- **Workflow Automation**: n8n orchestration with Airtable database

## Quick Start

1. Clone this repository
2. Set up Airtable base using `airtable/schema.json`
3. Configure n8n workflows from `n8n_workflows/`
4. Add your API keys and credentials
5. Run the ingest workflow to start generating content

## Architecture

Data Sources → n8n Workflows → Airtable DB → AI Generation → Video Rendering → Publishing

## Characters

- **Profit Pete**: Bullish, opportunity-focused reporting
- **Loss Lana**: Risk-aware, cautionary analysis  
- **Trend Tori**: Balanced, educational market updates

## License

MIT License - see LICENSE file for details