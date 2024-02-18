## To create and deploy your application, you can take the following steps - 
1. Initialize a worker
```npm create cloudflare -- my-app```
2. Select ```no``` for Do you want to deploy your application
3. Start the worker locally
```npm run dev```
4. Login to cloudflare account
```npx wrangler login```
5. Deploy worker code
```npm run deploy```