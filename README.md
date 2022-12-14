<p align="center">
<img src="https://user-images.githubusercontent.com/62262162/191147968-710e4c3c-6082-4aad-949e-ba49b06ef7f8.svg" alt="Next Level Week Esports Logo"/></p>

<br>

The evolved version of the **Esports** project on the [Next Level Week](https://lp.rocketseat.com.br/nlw) by Rocketseat.

The web client is deployed on Netlify here:

  [Preview NLW Esports](https://chimerical-brioche-e47d77.netlify.app/)

<hr>

**WORK IN PROGRESS:** Internationalization (i18n), new screens, form validations, unit tests w/ Jest, e2e tests w/ Cypress, pipeline deploy w/ Github Actions.

<hr>
<br>

  - [Description](#description)
  - [Stack and tools](#stack-and-tools)
  - [Quickstart](#quickstart)

<br>

## Description

The project is called *Find your Duo*.
It is a platform to find the perfect partner to play your favorite game together, by connecting your Twitch.tv account.

<p align="center">

<img src="https://user-images.githubusercontent.com/62262162/191152699-2bba0fc6-f7b4-4bd1-ab17-828d5b284929.png" alt="Next Level Week Esports Logo"/></p>
<img src="https://user-images.githubusercontent.com/62262162/191152701-f28bae8f-ed88-40cf-ae5e-78ee190be77f.png" alt="Next Level Week Esports Logo"/></p>


## Stack and tools
* Node.js
* Prisma
* React.js
* TypeScript
* TailWindCSS
* Radix UI
* Vite


## Quickstart

### Server

First, create a new ``.env`` file on the root directory, using the `.env.example` template as base.

Then, to create the local db run:
```sh
$ npm install
$ npm run db:migrate
```

After that, to start the server, run:
```sh
$ npm run dev
```

### Web

To run the local Vite web client:
```sh
$ npm install
$ npm run dev
```


