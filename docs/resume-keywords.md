# SpecForge — Resume Points

**SpecForge: AI Product Spec Generator**

- Built an AI-powered spec generator with **Next.js**, **React**, **TypeScript** and **REST APIs** that turns product ideas into exportable **Markdown PRDs**.
- Built a conversational AI interviewer using the **Claude API**, **LLM Tool Calling**, **JSON Schema** and **Prompt Engineering** to get structured, validated answers from the model.
- Wrote a single **LLM integration layer** that works with **Anthropic Claude**, **OpenAI GPT-4o** and **Google Gemini**, using the **Adapter Pattern**.
- Designed a **PostgreSQL** database using **JSONB** to store conversation state and **ACID Transactions** to save each spec as a new version safely.
- Tested the API routes with **Vitest** **Unit Testing** and **Mocking**, and enforced code quality with **ESLint**.

**Skills:** Next.js · React · TypeScript · Node.js · PostgreSQL · LLM APIs · Claude · OpenAI · Gemini · Vitest · REST APIs

---

## Where each keyword lives (for interview prep)

| Keyword | File |
|---|---|
| Tool Calling, JSON Schema, Prompt Engineering | `builder/lib/interview-engine.ts`, `builder/lib/spec-generator.ts` |
| Adapter Pattern, multi-provider LLM | `builder/lib/llm-client.ts` |
| PostgreSQL, JSONB | `builder/db/schema.sql`, `builder/lib/conversation.ts` |
| ACID Transactions, spec versioning | `builder/lib/spec.ts` |
| REST APIs | `builder/src/app/api/` |
| Vitest, Mocking | `builder/src/app/api/routes.test.ts`, `builder/lib/*.test.ts` |
