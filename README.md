# Chat Agent on the Aptos Blockchain

A simple chat agent built using Move Agent Kit, Next.js, OpenAI, Anthropic, Langchain and Vercel AI SDK that enables interaction with the Aptos blockchain through natural language.

## Features

- Natural language interaction with Aptos blockchain
- Wallet balance checking and transaction capabilities
- Support for multiple LLM providers (OpenAI and Anthropic)
- Real-time streaming responses
- Built on Next.js and Vercel AI SDK for optimal performance

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- pnpm package manager
- An Aptos wallet and private key
- API keys for OpenAI or Anthropic

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Alstudd/aptos-chat-agent.git
   cd aptos-chat-agent
   ```

2. Install dependencies:
   ```bash
   pnpm i
   ```

3. Set up environment variables:
   ```bash
   cp .example.env .env
   ```
   
4. Edit the `.env` file with your API keys and Aptos wallet details:
   ```
   PANORA_API_KEY=your_panora_key_here
   APTOS_PRIVATE_KEY=your_aptos_private_key_here
   ANTHROPIC_API_KEY=your_anthropic_key_here
   OPENAI_API_KEY=your_openai_key_here
   ```

5. Start the development server:
   ```bash
   pnpm dev
   ```

6. Open your browser and navigate to `http://localhost:3000`

## Usage

Simply type natural language requests in the chat interface such as:
- "What's my wallet balance?"
- "Send 0.5 APT to 0x123..."
- "Show me recent transactions"
