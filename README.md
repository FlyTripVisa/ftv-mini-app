# FTV-MINI-APP AI 👽 CHAT

ftv-mini-app/
├── wrangler.toml
├── package.json
├── tsconfig.json
├── src/
│   ├── index.ts          (main Worker entry)
│   ├── do/
│   │   ├── AIAgent.ts    (AI agent Durable Object)
│   │   ├── ChatSession.ts (chat session Durable Object)
│   │   └── RealtimeStream.ts (realtime streaming Durable Object)
│   └── types.ts          (shared types)
├── public/
│   ├── index.html        (chat UI)
│   ├── style.css
│   └── app.js            (client-side JS)
└── README.md
