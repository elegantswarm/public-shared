# Elegant Swarm MVP

## North-Star

Our long game is **self-driving startups**: a fleet of AI agents that ideate, validate, build, launch, and optimise with minimal human nudges.
The MVP is the first rung on that ladder—productising the *strategy* phase so founders reach conviction (or fail fast) in hours, not months.

## What is the MVP?

1. **Describe your idea** in plain language.  
2. **AI asks** the next-most-impactful question until your case is clear (or you're out of info)
3. **Agents create assets**, anything from Lean Canvas, stakeholder personas, competitive research, agentic case scrutiny, to your landing page(s), and prompts for product builder
3. **AI requests clarification** Each agent requests the most impactful clarifications needed to improve their output
5. **You're ready** to build, distribute, pivot, or kill

## Why this MVP?

> "Give me a lightweight yet authoritative single source of truth that turns my half‑baked idea into a fundable, executable venture in hours—without consultants or scattered docs."

1. **Idea-to-validation is slow** – founders juggle interviews, spreadsheets, slide decks, and ad-hoc tools for weeks before seeing whether an idea sticks.  
2. **Tool-sprawl hurts focus** – "Notion + Figma + Google + ChatGPT" creates silos; insights get lost.  
3. **Strategy work is still manual** – every founder answers the same questions from scratch and time-pressure keeps important information nuggets from surfacing early.

## Who is this MVP for?
Solo or 2‑person founder in **explore / validate** phase, €100–200 discretionary budget, aiming to decide **execute, pivot, or kill** fast.


## Questions for user interviews on MVP

* "Your thoughts: Who would use this when?"  
* "How much would you pay (one-off) or on a monthly subscription for each of the feature candidates below?"
* "Which feature candidates need to be in the MVP to make you a paying customer?"


## Pain points solved by MVP
- **Idea-to-clarity**: Capture and structure the problem/solution fast
- **Credibility boost**: Produce investor-grade evidence & narrative
- **Blind-spot** exposure: Surface hidden risks, compliance gaps, unknown competitors
- **Action momentum**: Deliver clear next steps & execution artefacts
- **Resource magnet**: Help attract co-founders, hires, advisors, investors

## Baseline capabilities
| ID | Baseline element | Description |
| --- | --- | --- |
| 1 | Adaptive onboarding | 30-minute, branching Q&A that captures the raw idea, founder context and goals; every next question is selected for maximal information gain, and the answers seed the Knowledge Base. |
| 2 | Clarification loop | After agents process the interview, the system surfaces missing or ambiguous data as short follow-up prompts; once the founder responds, all downstream documents are refreshed automatically. |
| 3 | Knowledge base | A read-only Notion-style interface to browse pages. Most features below are represented as page |

### Knowledge base structure
``` 
Knowledge Base /  
└── CEO  
  ├── Dashboard
  ├── Feed 
  ├── Clarifications
  └── Scrutiny
└── Strategy /
  ├── Lean canvas
  ├── Scrutiny
  └── Competition
    ├── Landscape
    └── Players/
      ├── Player A
      └── Player B
  ├── Press kit
  └── …
└── Distribution
  ├── Brand 
  ├── Scrutiny
  └── …
└── Product
  ├── User flows
  ├── Landing pages
  ├── Requirements
  ├── Sprints
  ├── Builder prompts
  └── …
```  

## MVP feature candidates (to be filtered in user interviews)

> [!NOTE]
> Most of these features automatically updated base don any input into the system by the user, reasoning, or research agents.

| ID | Feature candidate                       | Description                                                                                                               |
| -- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
|    | **Market & Customer Validation**        |                                                                                                                           |
| 01 | One-minute landing-page multiplier      | Generates a full landing page plus five headline/CTA variants, each with analytics and domain.                            |
| 02 | Cold-email synthesiser                  | One-click on any persona produces a personalised outreach email (with Calendly link) to schedule discovery calls fast.    |
| 03 | Synthetic user-testing report           | AI personas run task scenarios on a landing page/prototype and log UX issues.                                            |
| 04 | Stakeholder personas                    | Auto-generated archetypes (problem, pains, jobs, channels).                                                              |
| 05 | ICP-in-my-network                       | Scans founder's 1st/2nd-degree LinkedIn graph against persona attributes and returns 15 warm interview targets.           |
|    | **Business Planning & Strategy**        |                                                                                                                           |
| 06 | Lean canvas                             | Auto-fills and scrutinizes lean canvas using interview data and public research; stays live as assumptions evolve.        |
| 07 | Assumption map                          | Visual matrix of high-risk hypotheses with evidence status badges.                                                       |
| 08 | Simple financial model                  | 4-month cash-flow + runway slider (+ visual burn chart).                                                                 |
| 09 | Go / No-Go scorecard                    | Five-factor rubric (market, moat, risk, founder-fit, timing) outputs a coloured pursue/pause/kill decision and feeds the Decision-Delta KPI. |
| 10 | Pivot-idea recommender                  | When Go/No-Go is red, mines unmet assumptions and suggests three adjacent problems with higher TAM.                       |
| 11 | Market-sizing sheet                     | TAM/SAM/SOM with CAGR and source citations, exportable to deck.                                                          |
|    | **Competitor & Market Intelligence**    |                                                                                                                           |
| 12 | Auto-LinkedIn drill-downs               | Each competitor card links to pre-filled LinkedIn searches for current team, and past employees.                          |
| 13 | Competitor delta alerts                 | Nightly diff on rivals' pricing pages, changelogs, and GitHub/app-store notes to highlight relevant developments.         |
| 14 | Live industry feed                      | Continuous scrape of key players, blogs, competitors, forums, social chatter.                                            |
| 15 | Ecosystem heat-map                      | Interactive SVG that plots competitors, partners, and tools on a price-vs-complexity axis; exportable for pitch decks.    |
| 16 | Talent-pool pulse                       | Tracks open roles and salary bands at competitors; helps founders time their own hiring.                                  |
| 17 | Competitor churn detector               | Flags rivals showing layoffs or negative Glassdoor spikes, signalling weaknesses to exploit.                              |
| 18 | Competitive overview                    | Narrative synthesis of the market landscape, highlighting gaps and overcrowded niches.                                    |
| 19 | Competitor research table               | Structured sheet with founding year, funding, pricing model, and traction signals for each rival.                         |
| 20 | Competitive grid                        | Feature-by-player matrix showing where the startup can differentiate.                                                     |
| 21 | Domain context brief                    | One-page explainer of industry dynamics, history, and regulatory headwinds.                                               |
|    | **Branding & Communications**           |                                                                                                                           |
| 22 | Positioning statement                   | Geoffrey-Moore-style "For X … our Y" sentence auto-crafted from the interview to anchor all messaging and deck copy.      |
| 23 | Domain-grab radar                       | Suggests ten brandable available .com/.io/.co/.ai/... domains.                                                            |
| 24 | Brand kit prompt                        | Recommend multiple prompts. Recommend brand generator tools.                                                             |
| 25 | Instant press kit                       | AI-generates logo options, 50-word boilerplate, and up-scaled head-shot; zipped for instant PR use.                       |
| 26 | Pitch-deck content generator            | Just content, not style. Recommend Pitch-deck generator tools.                                                           |
| 27 | One-pager PDF auto-brander              | Compiles the lean canvas and key metrics into a visually branded one-pager PDF—handy for accelerators and quick investor mails. |
|    | **Growth & Funding**                    |                                                                                                                           |
| 28 | Funding-timeline tracker                | Charts median time comparable startups needed from pre-seed to Series A, helping founders set realistic raise cadence.    |
| 29 | Pre-seed valuation benchmarker          | Pulls last 30 disclosed rounds in the niche and shows cap-table impact for €1-5 m raises, removing guesswork in negotiations. |
| 30 | VC-thesis matcher                       | Parses thousands of investor write-ups and lists 15 angels whose theses overlap with the startup's problem space.         |
| 31 | Industry newsletter subscription hub    | One-click opt-in to industry newsletters, YC Startup School, Lenny's Newsletter, etc. Or referral to Mailbrew.           |
| 32 | 50% off for every referral              | Unique invite codes embedded in every export to track sign-ups and reward credits.                                       |
| 33 | One-click Notion export                 | Sets up a new Notion site with all content in the knowledge base.                                                         |
| 34 | VIP scan                                | Every week, our network gives expert advise and warm intros to the 10 strongest startups in our system.                  |
| 35 | Tech-stack path-finder                  | Converts roadmap epics into a "buy / AI-generate / open-source" matrix, linking to starter repos and prompt packs.        |
| 36 | Prompt-to-prototype pack                | Pre-filled prompts (with links to this KB) for low-code builders like Lovable to build demos and products quickly. |

## Post-MVP capabilities
- Autonomous product creation
- Autonomous marketing
- Autonomous validation
- Autonomous user interviews
- Autonomous sales
