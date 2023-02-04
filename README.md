# Destack Starter Beta

This example shows a very basic version of the a *Destack* (beta) with Next.js. 

- There's one page, `pages/index.js`, that shows the visual editor (in development) and the compiled version (in production). 
- All the magic is done in, `pages/api/builder/handle.js`, that has to be setup once and handles templates saving and loading.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com) or preview in Gitpod:

[<img src="https://raw.githubusercontent.com/LiveDuo/destack/main/assets/deploy/vercel_big.png" width="92">](https://vercel.com/new/git/external?repository-url=https://github.com/LiveDuo/destack-starter-beta&project-name=destack-starter-beta&repository-name=destack-starter-beta)
&nbsp;&nbsp;&nbsp;
[<img src="https://raw.githubusercontent.com/LiveDuo/destack/main/assets/deploy/gitpod_big.png" width="92">](https://gitpod.io/#https://github.com/LiveDuo/destack-starter-beta)


## How to

#### Development

Clone this repository:
```sh
git clone https://github.com/liveduo/destack-starter-beta
```
Install dependencies:
```sh
npm i
```
Run in development:
```sh
npm run dev
```

#### Production

Build for production:
```sh
npm run build
```
Run in production:
```sh
npm start
```

Deploy it to the cloud with [Vercel](https://vercel.com/new) ([Documentation](https://nextjs.org/docs/deployment)).
