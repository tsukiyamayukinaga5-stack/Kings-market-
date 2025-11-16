kings-market/
├── frontend/               # Next.js 15 App
│   ├── app/               # Routes (auth, marketplace, admin)
│   ├── components/        # UI components (negotiation, escrow)
│   ├── lib/               # Socket.io, API client
│   └── public/            # PWA assets, sw.js
├── backend/               # NestJS API
│   ├── src/
│   │   ├── auth/          # JWT, 2FA, OAuth
│   │   ├── escrow/        # Payment & escrow logic
│   │   ├── negotiations/  # Socket.io gateway
│   │   ├── fraud/         # ML fraud detection
│   │   └── database/      # Prisma schema
│   └── test/              # E2E tests
├── docker/                # Dockerfiles
├── .github/workflows/     # CI/CD pipelines
├── package.json           # Root workspace
└── README.md              # Full documentation
