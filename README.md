# With Docker - Multiple Deployment Environments


demo app :
https://app-demo-3-beta.vercel.app


This examples shows how to use Docker with Next.js and deploy to multiple environment with different env values. Based on the [deployment documentation](https://nextjs.org/docs/deployment#docker-image).

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example with-docker-multi-env nextjs-docker-multi-env
```

```bash
yarn create next-app --example with-docker-multi-env nextjs-docker-multi-env
```

```bash
pnpm create next-app --example with-docker-multi-env nextjs-docker-multi-env
```

Enter the values in the `.env.development.sample`, `.env.staging.sample`, `.env.production.sample` files to be used for each environments.

## Using Docker and Makefile

### Development environment - for doing testing

```
make build-development
make start-development
```

Open http://localhost:3001

### Staging environment - for doing UAT testing

```
make build-staging
make start-staging
```

Open http://localhost:3002

### Production environment - for users

```
make build-production
make start-production
```

Open http://localhost:3003

## Running Locally

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.





<img width="1260" height="986" alt="Capture d’écran 2025-09-18 à 20 48 10" src="https://github.com/user-attachments/assets/b4c33a9f-4986-4630-99fb-0942eb957490" />

creation roles/users :


![Image 19-09-2025 à 16 37](https://github.com/user-attachments/assets/20d91532-9435-4ec4-a5c0-d5378bc1fad6)



creation roles/users:



![IMG_5079](https://github.com/user-attachments/assets/d6950259-fa93-48db-8699-fe1e21fa2ffb)




![Image 21-09-2025 à 23 09](https://github.com/user-attachments/assets/61f89de4-4e4e-41ad-b127-17d269cfdb6b)

