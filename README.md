# CoderOne - Online Learning Platform Project - Team 41 - Source Code

Hey, there. This repository contains the source code for our Online Course Platform project. The project is built using Next.js, a React framework. The project is a part of the CoderOne Web Devlopment Internship, organized by CoderOne.

![Sample Screenshot](<demo/Online Learning Platform Output Image.png>)

## Team Members - Team 41

1. Aravinthan
2. Abhishek
3. Priya
4. Jayanth
5. Chinmayee

## Demo Video

[Watch on YouTube](https://youtu.be/1Q2Q7z1Q1Qk)

or

<video src="demo/CoderOne LMS.mp4"></video>

## To Recreate the Project or Run Locally

### Sample .env file

```shell
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test<...>
CLERK_SECRET_KEY=sk_test<...>
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_OUT_URL=/sign-in

NEXT_PUBLIC_TEACHER_ID=user_<...>

DATABASE_URL="mysql://<username>:<password>@<host>:<port>/<dbname>"

# To use a Mongo DB database, add MongoDB connection string and update the prisma/schema.prisma file: data source.

UPLOADTHING_SECRET=sk_<...>
UPLOADTHING_APP_ID=<...>

MUX_TOKEN_ID=<...>
MUX_TOKEN_SECRET=<...>

NEXT_PUBLIC_APP_URL=http://localhost:3000

STRIPE_API_KEY=sk_test_<...>
STRIPE_WEBHOOK_SECRET=whsec_<...>
```

## Template output generated by create-next-app

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
