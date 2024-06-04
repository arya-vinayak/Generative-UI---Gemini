# Generative UI with Google Gemini

An open-source AI chatbot app template built with Next.js, the Vercel AI SDK, Google Gemini, and Vercel KV. 

## Features

- [Next.js](https://nextjs.org/) App Router
- React Server Components (RSCs), Suspense, and Server Actions
- Vercel AI SDK for streaming chat UI
- Google Gemini as the default chat model
- [shadcn/ui](https://ui.shadcn.com/) for reusable components
- Chat History, rate limiting, and session storage with [Vercel KV](https://vercel.com/storage/kv)
- Dark mode support

## Running Locally

To run the Next.js AI Chatbot locally, follow these steps:

1. Install dependencies:

```bash

pnpm install

```

1. Set up your environment variables:

Create a `.env.local` file in the root directory of the project with the following variables:

```
# Get your Google Gemini API Key from: https://ai.google.dev/aistudio
GOOGLE_GENERATIVE_AI_API_KEY=XXXXXXXX

# Instructions to create KV database: https://vercel.com/docs/storage/vercel-kv/quickstart
KV_URL=XXXXXXXX
KV_REST_API_URL=XXXXXXXX
KV_REST_API_TOKEN=XXXXXXXX
KV_REST_API_READ_ONLY_TOKEN=XXXXXXXX

```

1. Start the development server:

```bash
pnpm i
pnpm dev

```

Your app should now be running on [localhost:3000](http://localhost:3000/).

This repository is inspired from the [repository template](https://github.com/vercel-labs/gemini-chatbot)  with an additional dark mode UI feature . For more information about the Vercel AI SDK, visit the [official documentation](https://sdk.vercel.ai/).