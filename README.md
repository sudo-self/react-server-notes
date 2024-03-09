# Next.js App Router + Server Components Notes

> Try the demo live here: [**next-rsc-notes.vercel.app**]([https://react-server-notes-sigma.vercel.app]).



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

[![Deploy with Vercel](https://vercel.com/button)](<https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fserver-components-notes-demo&env=REDIS_URL,SESSION_KEY,OAUTH_CLIENT_KEY,OAUTH_CLIENT_SECRET&project-name=next-rsc-notes&repo-name=next-rsc-notes&demo-title=React%20Server%20Components%20(Experimental%20Demo)&demo-description=Experimental%20demo%20of%20React%20Server%20Components%20with%20Next.js.%20&demo-url=https%3A%2F%2Fnext-rsc-notes.vercel.app&demo-image=https%3A%2F%2Fnext-rsc-notes.vercel.app%2Fog.png>)

