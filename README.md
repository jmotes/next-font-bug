## Illustrates bug with `next/font` when running turbopack in a container.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). The only modifications made are to enable Turbopack and add the Dockerfile.

To reproduce:

```
docker build -t next-font-bug .
docker run -p 3000:3000 next-font-bug
```

<img width="1099" alt="image" src="https://github.com/jmotes/next-font-bug/assets/1943254/a906ad30-63c2-4766-a870-52899b07de0a">
