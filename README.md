# Hoku-Birthday-2024

Currently on BETA Test: Hoku Birth Day dashboard for wish for hoku birthday on 2024.
Data stucture on mongodb will be: [This server side code:Line 92](https://github.com/siravijbb/Hoku-Birthday-2024-Wish-SendingAndReader/blob/main/src/routes/%2Bpage.server.ts#L92)


# Struture

Data structure provided: by [baku-bd-static-2023 by RikiNozomu](https://github.com/RikiNozomu/baku-bd-static-2023)
<br>FrontEnd:Sveltekit + Flowbite + Tailwind For Frontend
<br>Middleware: Sveltekit Connected with on-refresh mongoDB

## How to get started

Clone this rep

`git clone https://github.com/Polygang-Polygon-Fan-Club/Hoku-Birthday-2024`

then

`cd Hoku-Birthday-2024`

then create .env file and put this
<br>`MONGO_URL=mongodb://localhost:27017/YOURMONGODB`
NOTE: no need for "" on both sides.

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
pnpm run dev

# or start the server and open the app in a new browser tab
pnpm run dev -- --open
```

## Building

To create a production version of your app:

```bash
pnpm run build
```

You can preview the production build with `pnpm run dev`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
