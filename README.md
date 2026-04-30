Minimal reproducer for [an issue](https://github.com/mastra-ai/mastra/issues/15962) on the Mastra.ai framework

```
cp .env.example .env
# fill it with your OpenAI key and langfuse credentials

npm install
npm run start
```
- Open http://localhost:4111/ and chat with the agent
- Open your langfuse traces, see the cached input tokens calculations mismatch
