## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# nextjs-getting-started - some steps that I did:
1. sets up a Next.js application with "starter example" `npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm`
2. cd `nextjs-dashboard` 
3. install dependencies `pnpm i`
4. start dev server `pnpm dev`
5. open  http://localhost:3000
6. I've deployed this repo using vercel and created a Neon postgres DB, inserted the envs inside the .env and now need to install the integration
7. `pnpm i @vercel/postgres`
8. uncomented seeds route.ts and triggered the seeding by acessing http://localhost:3000/seed

