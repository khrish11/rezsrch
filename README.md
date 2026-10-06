# rezsrch

Neon configuration project with backend service skills and integration setup.

## Overview

This project contains Neon database configuration and automated skill definitions for Neon cloud services including:

- **Neon Postgres** - Lakebase PostgreSQL with branching, search, and scalability
- **Neon Auth** - Managed Better Auth for authentication
- **Neon Functions** - Serverless Node.js functions deployed on Neon branches
- **Neon Object Storage** - S3-compatible storage that branches with your database
- **Neon AI Gateway** - Unified API for LLM model routing

## Project Structure

```
.
├── .agents/skills/neon-*/      # Neon service skill definitions
├── neon.ts                     # Neon configuration file
├── package.json                # Node.js dependencies
└── .gitignore                  # Git ignore rules
```

## Setup

1. Install dependencies:
```bash
npm install
```

2. Configure Neon services in `neon.ts`

3. Use the Neon CLI to manage branches and deployments

## Skills

The project includes automated skills for:
- Database schema management and migrations
- Authentication setup and user management
- Serverless function deployment
- Object storage and file management
- AI/LLM integration and routing

## License

MIT
