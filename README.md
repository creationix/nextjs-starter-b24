This is a [Next.js](https://nextjs.org/) project bootstrapped with `create-next-app` (with some minor adaptations for Wasmer).

## Getting Started

First, run the development server:

```bash
npm run dev
```

You can run the Next.js example using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
wasmer run wasmer-examples/next-wasmer-starter --net
```

> [!TIP]
> You can also run `wasmer run . --net` in the root of this repo

Open [http://localhost:3000](http://localhost:3000) with your browser to see your Next.js app.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Wasmer Edge

The easiest way to deploy your Next.js app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://nextjs-wasmer-starter.wasmer.app/

First, you'll need to run `npm run edge:build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> You will also need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
