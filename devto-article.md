---
title: I Built a Collection of 150+ AI Prompts That Actually Work — Here's What I Learned
published: false
tags: ai, productivity, chatgpt, opensource
---

After months of using AI tools daily, I got tired of writing the same types of prompts over and over. So I compiled my best-performing prompts into a free, open-source collection.

## The Problem

Most "prompt packs" online are either:
- Paywalled ($29 for a PDF? Really?)
- Full of vague, useless prompts like "Write me a poem about nature"
- Not tested across different AI models

## The Solution

I created [AI Prompt Pack](https://github.com/writsop/ai-prompt-pack) — 150+ fill-in-the-blank prompts organized into 7 categories:

1. **Business & Marketing** (25 prompts) — Competitor analysis, pitch decks, marketing plans
2. **Content Creation** (25 prompts) — Blog posts, social media, newsletters, video scripts
3. **Coding & Development** (20 prompts) — Code review, debugging, architecture decisions
4. **Data Analysis** (15 prompts) — SQL queries, dashboards, data visualization
5. **Productivity** (25 prompts) — Meeting notes, decision frameworks, automation
6. **Education & Learning** (20 prompts) — Study guides, lesson plans, research
7. **Creative & Personal** (20 prompts) — Writing, brainstorming, personal development

## What Makes These Different

Every prompt uses a consistent format:

```
Act as a [ROLE] with [EXPERIENCE]. I need [TASK]. 
Context: [YOUR SITUATION]. Provide [OUTPUT FORMAT].
```

This structure works because it gives the AI:
- **Role context** — expertise level and perspective
- **Clear task** — exactly what you need
- **Your context** — specific details for personalization
- **Output format** — structured response you can use immediately

## My Top 5 Most-Used Prompts

### 1. The Competitor Teardown
```
Act as a competitive intelligence analyst. Analyze [COMPETITOR] vs my product [YOUR PRODUCT]. 
Compare: pricing, features, market positioning, strengths, weaknesses. 
Provide a SWOT matrix and 3 strategic recommendations.
```

### 2. The Code Reviewer
```
Act as a senior [LANGUAGE] developer doing a code review. Review this code for:
- Bugs and edge cases
- Performance issues  
- Security vulnerabilities
- Readability improvements
Code: [PASTE CODE]
Provide specific line-by-line feedback with fixed examples.
```

### 3. The Meeting Summarizer
```
Summarize this meeting transcript into:
1. Key decisions made
2. Action items (who, what, deadline)
3. Open questions
4. Next steps
Format as a table. Transcript: [PASTE]
```

### 4. The Blog Post Generator
```
Write a [WORD COUNT] blog post about [TOPIC] for [AUDIENCE].
Tone: [TONE]. Include: introduction with hook, [NUMBER] subheadings, 
practical examples, and a call-to-action. 
SEO keywords to include: [KEYWORDS].
```

### 5. The Decision Framework
```
I need to decide between [OPTION A] and [OPTION B]. 
Context: [SITUATION]. Constraints: [CONSTRAINTS].
Analyze using: pros/cons, risk assessment, opportunity cost, 
and reversibility. Give a clear recommendation with reasoning.
```

## Get the Full Pack

👉 **[GitHub: writsop/ai-prompt-pack](https://github.com/writsop/ai-prompt-pack)** — Star it, fork it, use it.

It's MIT licensed, completely free, and PRs are welcome if you have prompts to add.

---

*If this saved you time, I accept tips at `0x6d15eE39fB46Eb439d7B19ACEd5d36A4A327eAa2` on Base (USDC/ETH).*
