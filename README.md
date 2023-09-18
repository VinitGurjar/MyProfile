# Next-Supabase-User-client

### This app authenticates and identifies the user, stores their profile information in the superbase database, and allows the user to log in, update their profile details, and upload a profile photo. The app uses:
  
   1. Supabase Database: a Postgres database for storing your user data and Row Level Security so data is protected and users can only access their information.
   1. Supabase Auth: users log in through magic links sent to their email (without having to set up passwords).
   1. Supabase Storage: users can upload a profile photo.
   ![su](https://supabase.com/docs/_next/image?url=%2Fdocs%2Fimg%2Fuser-management-demo.png&w=1920&q=75)

- I coded this app in `.ts` and `.tsx` yes I used `typescript` like a pro so there is something you should check I've done, see [generating types](https://supabase.com/docs/guides/api/rest/generating-types) to automatically generate types from your database tables.

---
This is a [Next. js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
