# Architecture

## Initial Technology Stack

### Frontend

- Next.js
- TypeScript
- Tailwind CSS

### Stellar Integration

- Stellar SDK
- Stellar Wallets Kit
- Stellar Testnet

### Backend

The initial MVP will use Next.js server-side functionality.

A dedicated backend service may be introduced as the platform grows.

### Testing

- Vitest
- Playwright

### Deployment

The initial deployment target will be Vercel.

## High-Level Architecture

```text
User
  |
  v
Next.js Frontend
  |
  +------------------+
  |                  |
  v                  v
Learning System    Stellar Integration
  |                  |
  v                  v
Progress Data      Stellar Testnet
