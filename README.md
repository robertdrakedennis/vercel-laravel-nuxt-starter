# Laravel Nuxt Vercel Starter

> A Laravel Nuxt template that can deploy to Vercel functions.

## Prelude

- This starter template is based around the idea of [cretueusebiu/laravel-nuxt](https://github.com/cretueusebiu/laravel-nuxt) project starter
- This project template uses [juicyfx/vercel-php](https://github.com/juicyfx/vercel-php) and [nuxt/builder](https://github.com/nuxt/vercel-builder) under the hood (major thanks to them!)
- Make sure to read the [Nuxt docs](https://nuxtjs.org/).
- Make sure to read the [Laravel docs](https://laravel.com/).

## Features

- Nuxt 2.14+
- Laravel 8+
- Deploys to Vercel
- Nuxt SSR
- Laravel Serverless
- Nuxt Serverless

## Environment Variables (and how Vercel works with them)

You'll notice that in `vercel.json` there is little to no environment variables that laravel and nuxt needs. You're encouraged to leave them out of version control and use Vercel's dashboard to control your environment variables. You can learn more about this [here](https://vercel.com/docs/build-step#system-environment-variables)

## Local Development

At the time of writing [juicyfx/vercel-php](https://github.com/juicyfx/vercel-php) does not support local development. You'll have to use traditional ways of hosting a php server locally.
