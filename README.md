Your code already has context files.

Your marketing should too.

`GTM.md` is a simple, open-source format for describing your product's go-to-market context in one place.

Add it to your repository so ChatGPT, Claude, Codex, Cursor, and other AI agents can understand:

- what your product does
- who your ideal customer is
- why they buy
- your positioning
- your competitors
- your pricing
- your brand voice
- your acquisition channels
- your current GTM goals

Instead of explaining your business from scratch every time you ask AI to write a landing page, cold email, launch post, Reddit post, or campaign...

Give it `GTM.md`.

---

## Why GTM.md?

AI agents are becoming part of how products are built.

But they usually know much more about your **codebase** than your **business**.

You might already have:

```text
README.md
AGENTS.md
CLAUDE.md
.env.example
```

But when you ask:

> Write a Product Hunt launch.

Or:

> Find a better positioning angle.

Or:

> Write a cold email for this prospect.

You have to explain your product again.

And again.

And again.

`GTM.md` fixes that.

---

## How it works

Add this file to the root of your repository:

```text
your-product/
├── src/
├── README.md
└── GTM.md
```

Fill it with the important context about your business.

Then tell your AI agent:

```text
Read GTM.md before creating any marketing or GTM content.
```

That's it.

---

## What goes inside?

A `GTM.md` file can include:

```text
Product
↓
Problem
↓
Ideal Customer
↓
Positioning
↓
Competitors
↓
Offer & Pricing
↓
Messaging
↓
Brand Voice
↓
Acquisition Channels
↓
Buying Signals
↓
Content Strategy
↓
SEO / GEO
↓
Proof
↓
Objections
↓
Current Goals
```

The goal is not to create a giant marketing document.

The goal is to give AI **enough context to make better decisions**.

---

## Example

```md
# Product

Name: Acme

Website: https://acme.com

One-liner:
AI support agent for B2B SaaS teams.

# ICP

B2B SaaS companies with 5–100 employees.

Buyer:
Founder, Head of Support, COO.

# Problem

Support teams spend too much time answering repetitive questions.

# Positioning

Acme handles repetitive support requests automatically while escalating important conversations to humans.

# Main CTA

Start free

# Voice

Clear.
Concise.
Practical.
No generic AI buzzwords.
```

Now an AI agent has enough context to produce much better:

- landing page copy
- cold emails
- Product Hunt copy
- Reddit posts
- X posts
- comparison pages
- SEO content
- sales messaging
- campaign ideas

---

## Example prompts

### Landing page

```text
Read GTM.md.

Rewrite our homepage around the strongest customer pain and desired outcome.
```

### Reddit

```text
Read GTM.md.

Write a value-first Reddit post for our ICP.

Do not make it sound promotional.
Mention the product naturally only if relevant.
```

### Product Hunt

```text
Read GTM.md.

Create:
- tagline
- 500-character description
- first comment
- 3 gallery image concepts
```

### Cold outreach

```text
Read GTM.md.

Write a short cold email for this prospect.

Connect their current situation to the problem our product solves.
```

### Positioning

```text
Read GTM.md.

Give me 5 stronger positioning angles based on our ICP, competitors, and current offer.
```

---

## Buying signals

One useful section inside `GTM.md` is **Buying Signals**.

Instead of only describing *who* your customer is, describe what they do when they are getting close to buying.

Examples:

```text
- asks for alternatives to a competitor
- complains about their current solution
- asks for tool recommendations
- launches a new product
- hires for a relevant role
- discusses a problem we solve
- searches for a solution like ours
```

This can also be connected to external GTM tools.

For example, **Startories.com** can monitor sources such as Reddit, X, Product Hunt, directories, and search for fresh buying signals and help identify the companies and decision-makers behind them.

`GTM.md` provides the context.

Tools and AI agents can act on it.

---

## GTM.md + AI agents

The bigger idea is simple:

AI agents should understand not only:

```text
How does this product work?
```

but also:

```text
Who is it for?

Why do they buy?

How should we talk about it?

Where do we find them?

What are we trying to achieve?
```

That's what `GTM.md` is for.

---

## Recommended structure

The template currently covers:

1. Product
2. Problem
3. Ideal Customer Profile
4. Jobs To Be Done
5. Positioning
6. Unique Value Proposition
7. Why Customers Buy
8. Offer
9. Messaging
10. Voice
11. Acquisition Channels
12. Buying Signals
13. Content Strategy
14. Content Hooks
15. Launch Strategy
16. SEO / GEO
17. Proof
18. Objections
19. Current Goals
20. AI Agent Instructions
21. Channel-Specific Instructions
22. Update Rules

You don't need to fill every section.

Start with what you know.

Improve it as you learn.

---

## Principles

A good `GTM.md` should be:

**Simple**

One file.

**Human-readable**

No special parser required.

**AI-readable**

Structured enough for agents to understand.

**Portable**

Use it with any model or agent.

**Living**

Update it as your product and market evolve.

**Honest**

Never put fake testimonials, fake metrics, or invented customer claims inside it.

---

## The idea

Developers already give AI context about their code.

Founders should give AI context about their business.

```text
README.md → Understand the product

AGENTS.md → Understand how to work on the code

GTM.md → Understand how to market and sell the product
```

---

## Use it

1. Copy `GTM.md`
2. Add it to your repo
3. Fill in your product context
4. Ask your AI agent to read it
5. Stop explaining your business from zero

---

## Contributing

This is an open format.

If you think an important GTM section is missing, open an issue or submit a pull request.

The goal is to make `GTM.md` useful across:

- SaaS
- developer tools
- AI products
- agencies
- marketplaces
- open-source products
- B2B software

---

## License

MIT

Use it, modify it, fork it, ship it.

---

## GTM.md

**Your code has context for AI.  
Your business should too.**
