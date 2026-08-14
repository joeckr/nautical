## Naut TODO

1. MVP

  - Ability to pipe in commands in your terminal. Naut with then take the output and will facilitate a connection to you local AI (Ollama to start)
  - Ability to ask your AI to summarize (human readable version format of the logs), debug (provide any feedback on errors), trace (provide details related to a provided string input), anomoly (scan code for potential anomalies or malicious activity)

2. More Local AI

  - Add support for more local AI services and models
  - Allow users to configure and switch between different local AI models and services

3. Feature integration with Dredge (A piece of the Nautical Stack)

  - The ability to sanitize and restore sensitive information from log output
  - This becomes a key feature to open up to remote AI services
  - BadgerDB for local data storage or other cache related key/value store

4. The ability to limit context/token usage

  - Before adding heavy duty remote AI services, we should add a way to limit context/token usage
  - Allow users to set the max number of log lines to include in the context
  - Allow users to set the max number of tokens to include in the context
  - Allow users to use a local AI to initially compress the log context before sending it to the remote AI service

5. Add remote AI service support

  - Amazon Bedrock
  - Anthropic
  - OpenAI
  - Google
  - Groq
  - CoPilot
  - Any others that seems important to include

6. Connect back to the Nautical Stack

  - Connects to Nautical Anchor
  - Anchor is the core REST API for the Nautical Stack

7. TBD
