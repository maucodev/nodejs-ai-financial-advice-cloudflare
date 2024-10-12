# AI Financial Advice Worker

This is the Cloudflare worker project for the financial advice app.

## Prerequisites

Before running the project, you must set up the following environment variables to authenticate with the required APIs:

### Setting Environment Variables

* **OPENAI_API_KEY**: This is required to access OpenAI's API. You can get your API key from [OpenAI](https://platform.openai.com/signup/).

    ```
    npx wrangler secret put OPENAI_API_KEY
    ```

## Cloudflare commands

Create a worker

```
npm create cloudflare@latest
```

Deploy

```
npx wrangler deploy
```

Configure an environment variable

```
npx wrangler secret put VARIABLE_NAME
```
