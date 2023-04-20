# OpenAI Image Generator

Experimenting with OPEN AI platform to build an application that generates images based on text 


My free trial for the OPEN AI API key expired so the app does not function as it is supposed to but once I buy the subscription for the API key, it will work :) 

(someone hire me so I can pay for the API subscriptions please :) ) 









This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.
