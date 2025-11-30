# Setup Guide

## Prerequisites

- Airtable account
- n8n instance (cloud or self-hosted)
- API keys for:
  - CoinGecko (free tier)
  - OpenAI GPT-4
  - ElevenLabs
  - D-ID or HeyGen
  - Social media platforms

## Installation Steps

1. **Create Airtable Base**
   - Import schema from `airtable/schema.json`
   - Add your three characters to Characters table

2. **Configure n8n**
   - Import workflows from `n8n_workflows/`
   - Set up credentials for all APIs
   - Configure webhooks and triggers

3. **Test Workflow**
   - Run ingest workflow to fetch CoinGecko data
   - Verify character script generation
   - Test video rendering pipeline

## Configuration

Update these environment variables:
- `AIRTABLE_API_KEY`
- `OPENAI_API_KEY` 
- `ELEVENLABS_API_KEY`
- `DID_API_KEY`
- Social media API keys