This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Video Link

https://www.loom.com/share/426697a67670443ca86ff56a328df6ad?sid=713152cc-c76d-4707-8ed1-d2410e4a356e

## Overview

I designed and implemented a responsive task management dashboard that strikes a balance between performance, usability, and maintainability. The application follows a modular architecture and leverages both cloud and local storage to enhance user experience and ensure reliable data persistence.
For authentication and session management, I integrated Supabase to provide secure user login and logout functionality. I implemented session checks using Supabase’s authentication API to maintain persistent user sessions across browser refreshes and device changes. Additionally, I developed fallback logic to gracefully handle expired sessions or unauthorized access, thereby strengthening the application's security and reliability.
In terms of task storage and syncing, I built a mechanism that keeps task states—such as completed or pending—consistent across sessions. To improve clarity and user engagement, I incorporated strike-through indicators that visually mark completed tasks.


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

## Development Environment

I used Visual Studio Code for coding and Git/GitHub for version control. The programming language is TypeScript with NextJS 15 as the framework, and I utilized libraries like @supabase/supabase-js for database interaction and Prisma for ORM, managed with pnpm.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

# Useful Websites

- [Supabase Documentation](https://supabase.com)
- [Prisma Documentation](https://prisma.io)
- [Nextjs Documentation](https://nextjs.org)

# Future Work

- Enhanced Error Handling & Validation.
- Add user profile management via Supabase Auth.
- Implement task deletion confirmation dialogs.
