# Leading with AI

A 4-session Generative AI & Prompt Engineering training program for non-technical business leaders across **HR, Finance, Supply Chain, Banking, and Sales & Marketing** — designed and delivered by **Dr. Avinash Kumar Singh**.

The goal isn't to turn anyone into an engineer. It's to leave every session with something usable on Monday morning — a prompt, a framework, an agent, or a workflow you actually built yourself.

## Program outline

| # | Date | Session | Covers |
|---|---|---|---|
| 1 | Sat 22 Aug | **AI in Action: From LLMs to Powerful Prompts** | The story of AI (ML, DL, NLP, CV, LLMs), how an LLM actually works, tokens & cost, what a prompt is and why it works, and the RTCCF prompting framework |
| 2 | Sun 23 Aug | **Advanced AI, Prompting Like a Pro + AI Responsible Use** | Advanced prompting techniques and use cases, plus responsible-AI guardrails: data security and avoiding confidential-data risk |
| 3 | Sat 29 Aug | **Build Your AI Teammate: Creating Your First AI Agent** | Turning prompt engineering into a working AI agent |
| 4 | Sun 30 Aug | **Automate with AI: From Workflows to Intelligent Automation** | Chaining tools together into automated, hands-off workflows |

## Repo structure

Each session gets its own folder once its materials are finalized. Session 1 is complete; 2–4 will follow the same pattern as the program progresses.

```
LWAI-5/
├── README.md                                             ← you are here
├── agenda.txt                                             ← raw session planning notes
└── Introduction to Gen AI and Basic Prompt Engineering/   ← Session 1 materials
    ├── README.md                                         ← Session 1 details
    ├── genai_session1_deck.html                           ← the animated slide deck
    ├── Sales Data.csv
    ├── HR Attrition Data.csv
    ├── Marketing Campaign Data.csv
    ├── Prompt Engineering.pdf
    ├── Prompt Engineering Examples.pdf
```

Open any session's own `README.md` for what's in that folder and how to use it.

## Who this is for

Working professionals with 5–30 years of experience who use AI occasionally but haven't been trained on it — the sessions are built around real problems from each function (HR, Finance, Supply Chain, Banking, Sales & Marketing), not generic AI theory.

## Before you clone

`Sales Data.csv` (Session 1) is ~22 MB. GitHub allows it, but it'll slow down every clone of this repo. If the program grows to include more large datasets, consider moving them to [Git LFS](https://git-lfs.com) rather than committing them directly.

## License & sharing

No license is set yet — add one (e.g. MIT for the slide deck's code, a separate note for each dataset's own license) before making this repo public. The three datasets used in Session 1 are public training datasets; see that folder's README for individual credits. No proprietary or confidential data belongs in this repo.
