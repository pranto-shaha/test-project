# Experimental Project

A scratch workspace for trying ideas in code. Nothing is shipped from here until an experiment is worth keeping.

## What this project is

Experimental Project is a place to prototype, break things, and decide what is worth building for real. It is not a product yet. There is no app, no stack, and no users.

Use it when you want to:

- Test a marketing idea as a small page, script, or automation
- Try a layout, copy flow, or data shape before committing to a campaign tool
- Learn a piece of code by building the smallest version that proves the point

If an experiment works, copy the useful parts into a real project. Leave the rest here.

## Current layout

```text
Experimental Project/
└── cursor.md/
    └── PROJECT_GUIDE.md
```

`cursor.md` holds project notes and guides. Code for each experiment should live in its own folder at the project root, next to `cursor.md`, so one test does not overwrite another.

Suggested shape once work starts:

```text
Experimental Project/
├── cursor.md/
│   └── PROJECT_GUIDE.md
├── experiment-landing-page/
└── experiment-email-sequence/
```

Name each experiment folder after the thing you are testing, in lowercase with hyphens.

## How to start an experiment

1. Create a new folder at the project root. Example: `experiment-offer-page`.
2. Write one sentence at the top of a `README.md` in that folder: what you are testing and how you will know it worked.
3. Build the smallest version that answers that question. Skip accounts, dashboards, and extra pages until the core idea is visible.
4. Run it locally and use it the way a real person would: click, type, and read the result.
5. Record the outcome in the experiment README: what you tried, what happened, and whether to keep, change, or drop it.

One experiment per folder. Do not mix two ideas in the same files.

## Working in Cursor

- Keep this guide in `cursor.md` and update it when the project grows a real structure, stack, or rule.
- Ask for changes against a specific experiment folder so edits stay inside that test.
- When a change affects what someone sees (a page, layout, or on-screen text), check it in the browser before treating it as done.
- Do not put passwords, API keys, or customer data in this folder. Experiments should use fake or public sample content.

## When an experiment is done

Keep it if you would reuse the code or the lesson. Otherwise leave a short note in that experiment’s README and move on. A finished experiment should answer three things:

- What was tested
- What the result was
- What to do next (build it properly, try a variation, or stop)

## Next step

Pick one idea and create its folder. The first useful line in its README is the question that experiment exists to answer.
