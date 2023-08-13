# [Weekly Report](https://zhoubaotong.com)


This project generate weekly report with simple sentence for you using AI.

[![Weekly Report](./public/screenshot.jpg)](https://zhoubaotong.com)

## How it works

This project uses the [OpenAI GPT-3 API](https://openai.com/api/) (specifically, text-davinci-003) and [Vercel Edge functions](https://vercel.com/features/edge-functions) with streaming. It constructs a prompt based on the form and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.

## Running Locally

After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and put your API key in a file called `.env`.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/alvinxdev/zhoubaotong&env=OPENAI_API_KEY,NEXT_PUBLIC_USE_USER_KEY,OPENAI_MODEL&project-name=zhoubaotong&repo-name=zhoubaotong)

NEXT_PUBLIC_USE_USER_KEY = false
OPENAI_MODEL = gpt-3.5-turbo

<!-- https://www.seotraininglondon.org/gpt3-business-email-generator/ -->

## Credits

Inspired by [TwtterBio](https://github.com/Nutlope/twitterbio) and [zhengbangbo](https://github.com/zhengbangbo/chat-simplifier).

## Statement

This project is a secondary development based on [Weekly Report](https://github.com/guaguaguaxia/weekly_report).