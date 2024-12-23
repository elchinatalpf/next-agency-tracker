This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Index Content
* [Keys from https://github.com/webprodigies/plura-production/blob/main/.env.example](#keys-from-httpsgithubcomwebprodigiesplura-productionblobmainenvexample)
* [Technologies](#technologies)

## Installation
Using `bun create next-app`
* Typescript
* ESLint
* Tailwind CSS
* `src/` directory
* App Router
* Turbopack

## Getting Started
First, run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More
To learn more about Next.js, take a look at the following resources:
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome

## Deploy on Vercel
The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

 ## Keys from https://github.com/webprodigies/plura-production/blob/main/.env.example
 NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
DB_USERNAME=
DB_PASSWORD=

NEXT_PUBLIC_URL=
NEXT_PUBLIC_DOMAIN=
NEXT_PUBLIC_SCHEME=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_CLIENT_ID=
NEXT_PUBLIC_PLATFORM_SUBSCRIPTION_PERCENT=1
NEXT_PUBLIC_PLATFORM_ONETIME_FEE=2
NEXT_PUBLIC_PLATFORM_AGENY_PERCENT=1
NEXT_PLURA_PRODUCT_ID=
DATABPASE_PASSWORD=


# This was inserted by `prisma init`:
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=
PROD_DATABASE_URL=
LOCAL_DATABASE_URL=
# https://www.builder.io/c/docs/using-your-api-key
NEXT_PUBLIC_BUILDER_API_KEY=

## Technologies
* Uploadthing
* Shadcn/ui
