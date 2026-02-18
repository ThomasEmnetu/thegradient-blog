---
date: '2026-02-07T01:00:00-07:00'
draft: false
title: "I’ve Been Drinking the AI Kool-Aid…and I Love It"
tags: ["AI", "Engineering", "Productivity", "Opinion"]
categories: ["AI"]
author: ["Thomas Emnetu"]
showToc: true
TocOpen: false
---

## I was overly pessimistic about AI for a while.

I harped on the harms, ethical shortcomings, the ways this tech could be misused or cause real damage.

I still hold those concerns. 

I assure you they haven't disappeared.

But I had a profound experience this week that shifted something fundamental in how I'm thinking about this.

## I deployed my first multi-agent swarm

I had a vague product idea. No detailed spec, just a rough concept.

I set up a simple multi-agent system as the following:

- PM agent to define scope
- backend agent to build server side
- frontend agent to handle the UI
- QA agent to catch issues

Then I stepped back.

For over 30 minutes, I didn't touch my keyboard; after enabling auto-approval for the session.

The agents coordinated. Delegated tasks to each other. Built a database schema. Wrote frontend code. When things broke, they debugged and self-corrected.

In under an hour, I had a working product. Backend running, UI rendering, everything functional end-to-end.

I've tried AI coding tools before, but this was fundamentally different. Don't get me wrong, the output wasn't perfect production level code. But the autonomous **coordination** actually worked.

## I'm not here to be a grifter

I'm not gonna sell you a dream that "AI will replace all developers" or "everyone can build anything now"; though the latter is becoming increasingly true.

Let me be clear. The system isn't magic. It made mistakes. It wrote code that needed refactoring.

But what surprised me was how the bottleneck wasn't at all the models capabilities.

It was **how I structured the problem.**

When I gave clear, specific scopes to each agent, they executed extraordinarily well. 

Conversely, when I was vague, it caused them to spiral, still producing working code, but their bar for quality dropped.

The quality of output correlated directly with the quality of problem decomposition.

That's a different skill than writing code.

It's effectively architecting systems in an organized feedback loop.

## Why this matters

We often discuss AI progress in terms of model capabilities. 

Which frontier model reasons the best, creates the best outputs, has the highest benchmark scores, etc.

But they've improved so much in the past 12 months, that you can disregard any marginal gains you may receive by using a specific LLM. 

<figure>
  <img src="/images/best-in-agentic-coding.png" alt="SWE Benchmark Results">
  <figcaption>Data from the SWE Benchmark that evaluates if LLMs can resolve GitHub Issues. Measures agentic reasoning.</figcaption>
</figure>

Orchestration is becoming the most valuable skill, i.e. systems thinking.

Multi-agent systems aren't new conceptually. The idea of breaking work into specialized sub-tasks and coordinating them has been around for years.

What changed is that the models are now good enough (and inference is cheap enough) that orchestration actually works at a practical level.

<a href="https://claude.com/customers/spotify" target="_blank">Spotify is now using this in production to resolve errors and conflicts.</a> It's become a critical part of their workflow, freeing up developer time for bigger-picture efforts.

The economics finally make sense.

## The part I'm grappling with

This creates real questions I don't have answers to yet.

If the skill shifts from *writing code* to *decomposing problems and directing agents* what does expertise mean?

How do we maintain quality when the barrier to shipping is this low?

What happens when non-technical people can orchestrate complex systems without understanding what's happening under the hood?

For a period of time, I believed this transition would be fairly gradual. 

Models getting better over years, causing workflows to evolve incrementally, giving folks time to adapt to the changes.

But watching a multi-agent system go from nothing to a working product in an hour makes me realize the shift is more discontinuous than I expected.

At some point, you have to reflect on whether you are adapting or resisting.

---

## History as context

Developers used punch cards to program from the 1940s-1970s.

<figure>
  <img src="/images/punchcard-computer.jpeg" alt="Punch Card Computer">
  <figcaption>IBM keypunch machine used to punch holes into paper cards for early computer data entry and programming</figcaption>
</figure>


When CLIs and GUIs became standard, their expertise didn't disappear. 

It simply evolved.

The ones who "adapted" were not the ones who memorized punch card syntax. 

They were the ones who understood the underlying problems & learned the new abstractions.

Same pattern playing out again, just a different font.

The abstractions are shifting. The problems remain.

## What I'm doing about it

I'm experimenting deliberately.

Reading everything I can. Building small swarms. Analyzing their points of failure. Talking to people who understand multi-agent architecture at a deeper level than I do.

Not at all because I'm trying to stay ahead or worried about being left behind.

But because I'm genuinely trying to understand what's actually possible versus what's hype.

And because the gap between demos and production reality is often massive.

## The uncomfortable truth

I titled this "I've been drinking the AI kool-aid" because that's what it feels like.

I'm more optimistic about multi-agent systems than I expected to be.

But optimism without critical examination is just hype.

So what I'm closely studying and paying attention to is:

- How do these systems maintain context over longer sessions (i.e. days/weeks)?
- What is most optimal memory architecture to enable execution of more complex work?
- When one agent makes a mistake, how does that cascade through the system?

These are some of the problems exciting me that've yet to be solved in the industry. 

## My perspective

I have no idea where this goes from here.

But I just experienced something that changed how I think about what's possible with current technology. It was imperative that I share it.

Right now, with the tools that exist today, anyone can semantically orchestrate an autonomous multi-agent swarm that builds working software in less than an hour.

That's worth your attention. Especially if you work in tech or aspire to.

The nature of the work is changing faster than most can adjust. 

So what does this mean for us?

I'm honestly trying to worry less about that.

I'm much more concerned with challenging myself and feeding my curiosity, so my skills don't atrophy.  

more from me soon