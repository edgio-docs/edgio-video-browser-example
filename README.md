# Edgio Video Browser Example

An example application that uses Edgio, Next.js, and prefetching.

## Getting Started

### Clone This Repo

Use `git clone https://github.com/edgio-docs/edgio-video-browser-example.git` to get the files within this repository onto your local machine.

### Install dependencies

On the command line, in the project root directory, run the following command:

```bash
npm i -g @edgio/cli
npm install
```

### Run the Next.js app locally

Run the Next.js app with the command:

```bash
edgio dev
```

Load the site: http://127.0.0.1:3000

### Testing production builds locally

You can do a production build of your app and test it locally using:

```bash
edgio build
edgio run --production
```

Setting --production runs your app exactly as it will be uploaded to the Layer0 cloud using serverless-offline.

## Deploying on Edgio

Deploying requires an account on Edgio. [Sign up here for free](https://edgio.app). Once you have an account, you can deploy on Edgio by running the following in the root folder of your project:

```bash
edgio deploy
```
