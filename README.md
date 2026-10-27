# AI Car Ad Generator — n8n + Telegram

## Overview

A personal automation project built with n8n that uses AI-assisted text generation and Telegram messaging to create vehicle advertisement content.

## Features

- n8n workflow automation
- AI-assisted vehicle advertisement generation
- Telegram messaging integration
- Structured vehicle information and generated ad content
- Adaptable to different makes and models by updating the vehicle details

## Current Status

This is an early-stage personal prototype. Vehicle details are currently entered directly into the n8n workflow. The generated advertisement is sent through Telegram.

The workflow can be adapted to different vehicles by updating the input fields. Accepting vehicle details directly from users through Telegram is a planned improvement.

## Planned Improvements

- Accept vehicle details dynamically through Telegram
- Support multiple languages and international markets
- Add input validation and error handling
- Improve testing and setup documentation

## Requirements

- An n8n instance
- A Telegram bot
- An AI model provider and its required credentials

## Setup

1. Import the sanitized workflow JSON into n8n.
2. Configure your own Telegram and AI model credentials.
3. Replace the Telegram chat ID placeholder with your own intended destination.
4. Review the workflow settings and test it using sample vehicle information.

## Security

Never publish API keys, bot tokens, passwords, authorization headers, or private customer information. Review workflow exports before sharing them publicly.

## Disclaimer

This is a personal learning and portfolio project. It is an early-stage prototype and is not presented as a production-ready service.
