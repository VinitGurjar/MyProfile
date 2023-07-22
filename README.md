# Next-Supabase-User-client
> With the help of this article [Build a User Management App with NextJS](https://supabase.com/docs/guides/getting-started/tutorials/with-nextjs) I've build this app.
-  This tutorial demonstrates how to build a basic user management app. The app authenticates and identifies the user, stores their profile information in the database, and allows the user to log in, update their profile details, and upload a profile photo. The app uses:
  
   1. Supabase Database : a Postgres database for storing your user data and Row Level Security so data is protected and users can only access their own information.
   1. Supabase Auth : users log in through magic links sent to their email (without having to set up passwords).
   1. Supabase Storage : users can upload a profile photo.
   ![su](https://supabase.com/docs/_next/image?url=%2Fdocs%2Fimg%2Fuser-management-demo.png&w=1920&q=75)

- I codeed this app in `.ts` and `.tsx` yes I used `typescript` like a pro so there something you should check I've done, see [generating types](https://supabase.com/docs/guides/api/rest/generating-types) to automatically generate types from your database tables.

---
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
