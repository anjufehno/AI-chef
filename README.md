# AI Chef

> **Learning project** · React experiment with generative AI recipe suggestions.

AI Chef lets a user enter ingredients they already have and request a recipe suggestion generated from that ingredient list.

## Features

- Add ingredients interactively
- Maintain ingredient state in React
- Generate a recipe from the current ingredient list
- Render AI-generated Markdown-style recipe content
- Experiment with Claude and Hugging Face inference APIs

## Tech Stack

`React` · `JavaScript` · `Anthropic SDK` · `Hugging Face Inference` · `CSS`

## What I Practised

- React state management
- asynchronous API calls
- conditional rendering
- form handling
- integrating external AI services into a frontend prototype

## Run Locally

```bash
git clone https://github.com/anjufehno/AI-chef.git
cd AI-chef
npm install
npm start
```

The prototype expects the relevant API credentials in the local environment.

## Security Note

This repository is an **educational prototype**. Its direct browser-side AI SDK integration is useful for experimentation but is **not the architecture I would use for production secrets**. A production version should proxy AI requests through a protected server-side API.

## Project Status

Kept as a learning project demonstrating early work with React and generative-AI integrations.
