# Takeoff: Mistral API

This module is a guide to the Mistral API.

## Resources

- [Takeoff](https://JoinTakeoff.com)
- [Mistral Docs](https://platform.mistral.com/docs/overview)
- [Mistral API Reference](https://platform.mistral.com/docs/api-reference)

## Recommendations

We recommend using [Cursor](https://cursor.sh/) to write code.

## Prerequisites

You will need an Mistral API Key.

Get one [here](https://platform.mistral.com/api-keys).

Copy the `.env.example` file to `.env`.

```bash
cp .env.example .env
```

In `.env`, fill in the API key.

```bash
MISTRAL_API_KEY=your-mistral-api-key
```

## Install Packages

```bash
npm i
```

## Structure

The example code is in the `examples` folder.

Your code is in the `me` folder.

## Run Code

Install `tsx` to run the examples.

```bash
npm i -g tsx
```

Example: Run the `audio-create-speech-example` and `audio-create-speech-me` files.

Copy the relative path of the file.

For the example code, run the following command:

```bash
tsx examples/audio/create-speech.ts
```

For your code, run the following command:

```bash
tsx me/audio/create-speech.ts
```
