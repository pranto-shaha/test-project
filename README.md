# Experimental Project

A scratch workspace for trying ideas in code before they become a real product. Each experiment lives in its own folder so one test does not overwrite another.

Notes on how to run those experiments are in [cursor.md/PROJECT_GUIDE.md](cursor.md/PROJECT_GUIDE.md).

## Stack

- Node.js (CommonJS)
- [dotenv](https://github.com/motdotla/dotenv) for local environment variables

There is no app entry file yet. `package.json` lists `index.js` as the main file, and that file still needs to be added when the first experiment needs it.

## Setup

```bash
npm install
```

Copy any secrets into a local `.env` file and keep that file out of git. Use sample or public content in experiments.

## Layout

```text
Experimental Project/
├── README.md
├── package.json
├── cursor.md/
│   └── PROJECT_GUIDE.md
└── experiment-name/
```

Name each experiment folder after the thing you are testing, in lowercase with hyphens.

## Start an experiment

1. Create a folder at the project root, for example `experiment-offer-page`.
2. Add a `README.md` in that folder with one sentence: what you are testing and how you will know it worked.
3. Build the smallest version that answers that question.
4. Record the result in that same README: what you tried, what happened, and whether to keep, change, or drop it.
