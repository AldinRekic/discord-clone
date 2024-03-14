##   Discord Clone: Real-Time Chat Built with Next.js

**Empower real-time communication** with this feature-rich Discord clone built on **Next.js**.

**Tech Stack:**

- **Front-End:** Next.js, React, Socket.io, Tailwind CSS, ShadcnUI
- **Back-End:** Prisma, MySQL (Supabase)
- **Authentication:** Clerk

**Key Features:**

- **Seamless Chat:** Chat in real-time with **Socket.io**.
- **Rich Messaging:** Send text, attachments, and edit/delete messages.
- **Voice & Video Calls:** Foster deeper connections with built-in voice and video call functionalities.
- **Channel & Server Management:** Create and manage channels and servers with roles and unique invites.
- **Modern UI/UX:** Enjoy a visually appealing and responsive design built with **Tailwind CSS** and **ShadcnUI** (light/dark mode included).
- **Robust Data & Security:** Leverage **Prisma** for data management and **Clerk** for secure authentication.

### Cloning the repository

```shell
git clone https://github.com/AldinRekic/discord-clone.git
```

### Install packages

```shell
npm i
```
### Setup .env file
```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

POSTGRES_HOST=
POSTGRES_PORT=
POSTGRES_USER=
POSTGRES_PASSWORD=
POSTGRES_DB=

DATABASE_URL=

WEBSOCKET_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=

```
### Start the app

```shell
npm run dev
```
## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
