This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Illustrates bug with `next/font` when running turbopack in a containef.

To reproduce:

```
docker build -t next-font-bug .
docker run -p 3000:3000 next-font-bug
npm run dev
```

