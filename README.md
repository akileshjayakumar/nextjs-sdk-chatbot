# Next.js SDK Chatbot
A simple streaming chatbot built with Next.js, Vercel AI SDK, and OpenAI.

## Quick Start
```bash
git clone https://github.com/akileshjayakumar/nextjs-sdk-chatbot.git
cd nextjs-sdk-chatbot
npm install
```

## Capabilities
- Streaming assistant responses in the chat UI
- Server-side OpenAI call in `src/app/api/chat/route.ts`
- Edge runtime for low-latency request handling
- Tailwind + shadcn/ui components for a clean, responsive interface

## Configuration
- `OPENAI_API_KEY`: Required for related integrations/features.

## Usage
```bash
yarn dev
```

## Contributing and Testing
- Contributions are welcome through pull requests with clear, scoped changes.
- Run the following checks before submitting changes:
```bash
yarn lint
yarn build
```

## License
Licensed under the `MIT` license. See [LICENSE](./LICENSE) for full text.
