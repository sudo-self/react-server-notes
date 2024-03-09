# Next.js App Router + Server Components Notes

> Try the demo live here: <a href="https://react-server-notes-sigma.vercel.app">React-Server-Notes</a>
<img width="1422" alt="Screenshot 2024-03-09 at 12 01 39 AM" src="https://github.com/sudo-self/react-server-notes/assets/119916323/7e019754-c1ab-456f-a180-ae2b083d0cba">

### Environment Variables

These environment variables are required to start this application (you can create a `.env` file for Next.js to use):

```bash
KV_URL='redis://:<password>@<url>:<port>' # vercel.com/kv
SESSION_KEY='your session key'
OAUTH_CLIENT_KEY='github oauth app id'
OAUTH_CLIENT_SECRET='github oauth app secret'
```

### Running Locally

1. `pnpm install`
2. `pnpm dev`

Go to `localhost:3000`.

### Deploy

You can quickly deploy the demo to Vercel by clicking this link:

[![Deploy with Vercel](https://vercel.com/button)](<https://vercel.com/new/git/external?repository-url=https://github.com/vercel/server-components-notes-demo&env=REDIS_URL,SESSION_KEY,OAUTH_CLIENT_KEY,OAUTH_CLIENT_SECRET&project-name=next-rsc-notes&repo-name=next-rsc-notes&demo-title=React Server Components (Experimental Demo)&demo-description=Experimental demo of React Server Components with Next.js. &demo-url=https://next-rsc-notes.vercel.app&demo-image=https://next-rsc-notes.vercel.app/og.png>)

