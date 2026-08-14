# Nautical

Nautical is a planned suite of tools for logging that leverages AI.

Core components, please reference respective directory and read the included README for full descriptions:

- anchor (REST API) - The core REST API for the Nautical Stack. Used for the UI, CLI connects, able to connect to and configure the Nautical Stack.

- beacon (UI) - The core UI for the Nautical Stack. Provides an interface that connects to other services in the Nautical Stack, provides an alternative means to visualize your containerized infrastructure/applications, and continue/start/recall context for previous AI sessions.

- dredge (Zero Trust Sanitizer) - The log sanitizer for the Nautical Stack. Provides a zero trust REST API for tokenizing sensitive information in log data. Has the ability to also restore. Keeps an immutable log history of all tokenized log data.

- naut (CLI) - Includes several features of the Nautical Stack in a CLI tool. Can be independent or used as an entrypoint of the Nautical Stack.

- sluice (Log Aggregator) - The log aggregator for the Nautical Stack. Has the ability to forward logs and grab logs directly from your containerized infrastructure/applications. Leverages dredge to tokenize sensitive information in log data before forwarding or storing it.

- sonde (Log Watchdog) - The log watchdog for the Nautical Stack. Monitors containers and logs for suspicious activity, errors, and makes sure applications are healthy. Creates reports and alerts if anything is of concern.
