# Next.js SDK Chatbot

A simple streaming chatbot built with Next.js, Vercel AI SDK, and OpenAI.

Live demo: [nextjs-sdk-chatbot.vercel.app](https://nextjs-sdk-chatbot.vercel.app)

## Quick Start

```bash
git clone https://github.com/akileshjayakumar/nextjs-sdk-chatbot.git
cd nextjs-sdk-chatbot
npm install
```

Create `.env.local`:

```bash
OPENAI_API_KEY=your_openai_api_key
```

Run locally:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Core Capabilities

- Streaming assistant responses in the chat UI
- Server-side OpenAI call in `src/app/api/chat/route.ts`
- Edge runtime for low-latency request handling
- Tailwind + shadcn/ui components for a clean, responsive interface

## Configuration

Required environment variable:

- `OPENAI_API_KEY`: API key used by the chat route

The default model is set in `src/app/api/chat/route.ts`. Update it if needed for your OpenAI account/project.

## Usage

1. Start the app with `npm run dev`.
2. Type a message in the input box.
3. Submit and watch the assistant stream the reply in real time.

## Contributing and Testing

- Run lint checks: `npm run lint`
- Build for production: `npm run build`
- Start production server: `npm run start`

PRs are welcome for UI improvements, model/provider updates, and chat UX enhancements.

## License

[MIT](LICENSE)
