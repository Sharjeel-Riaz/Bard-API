# Bard-API

A RESTful API for [PaLMFlow](https://github.com/Sharjeel-Riaz/PaLMFlow) created
using [Next.js](https://nextjs.org/).

![Banner](https://github.com/Sharjeel-Riaz/Bard-API/blob/main/public/PaLM%20API%20Banner.png?raw=true)

## Features

- 🌐 Next.js RESTful API
- 📡 Axios Integration for RESTful API
- 📦 PaLM 2.0 Integration for Text Generation
- 📝 Easy to setup and use

## Usage

This section explains on how you can create your own RESTful API using Google's
[PaLM 2.0](https://developers.generativeai.google/products/palm) for
[PaLMFlow](https://github.com/Sharjeel-Riaz/PaLMFlow).

- First of all, you need to clone this repository or fork it. Whatever works
  best for you.
- Go to [PaLM 2.0 API page](https://developers.generativeai.google/products/palm) to get access to your api and create a new one using
  makersuite under the category of `Chat Prompt`.
- Now create a `.env` file and add the following variables to it:

```
 BARD_API_KEY = "Your Google PaLM 2.0 API Key with double quotes."
```

- Your API end-point w.r.t your local development envrinoment will be looking
  like this: `http://your device's ip address:localhost port number/api/bardapi`
- Run the following command to install all of the necessary dependencies:
  `npm install`
- Now run `npm run dev` to open the local environment.
- You need to run both the end-point and your application simultaneously in
  order to use your application properly. Otherwise you can also deploy the
  end-point on a cloud platform like [Vercel](https://vercel.com/).
- Feel free to use it or make any necessary modifications `:D`
