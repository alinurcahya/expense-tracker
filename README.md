# [Expense Tracker Application - Live Demo](https://expense-tracker-alinurcahya.vercel.app/)

## Getting Started

#### Install dependencies
```
npm install
```

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

## Stacks

- [Tailwind](https://tailwindcss.com/)
- [Clerk](https://clerk.com/docs)
- [Drizzle](https://orm.drizzle.team/)
- [Neon](https://neon.tech/)
- [Shadcn](https://ui.shadcn.com/)
- [Emoji Picker React](https://www.npmjs.com/package/emoji-picker-react)
- [Recharts](https://recharts.org/)
- [Vercel](https://vercel.com/)

## .env.local file 

```
## Clerk Credentials
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

## Clerk Redirect
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

## Database
NEXT_PUBLIC_DATABASE_URL=
```

### Reference
Thanks to [sayyidisal](https://github.com/sayyidisal) for the original.