# Tax Preparation Skill for Claude Code

If you don't want to install this manually, just tell Claude:

```text
Install and use https://github.com/alqz/claude-tax-preparation
```

This Skill helps Claude prepare your tax return: read the source docs, compute the return, fill the official PDF forms, and hand back a clear summary of what to review before you file.

## What It Does

- Reads W-2s, 1099s, brokerage statements, and prior-year returns
- Asks the questions Claude needs to finish the return
- Computes federal and state tax results, including capital gains and carryovers
- Downloads official blank PDF forms and fills them programmatically
- Verifies outputs and returns a human-friendly summary of refunds, forms, and next steps

## Installation

```
/plugin marketplace add alqz/claude-tax-preparation
/plugin install tax-preparation
```

## What It Looks Like

Start with a simple prompt:

![Starting prompt in Claude](docs/images/start-prompt.png)

Claude asks the follow-up questions needed to finish the return:

![Filing questions UI](docs/images/filing-questions.png)

It works through the preparation steps and keeps track of progress:

![Workflow progress](docs/images/workflow-progress.png)

## What You Get

- Filled PDF forms ready for you to review and file
- A summary of federal and state results
- Any carryover values to save for next year
- A checklist of what to sign, review, and file

## Contributing

This is a fork of [robbalian/claude-tax-filing](https://github.com/robbalian/claude-tax-filing). Contributions are welcome via PR.
