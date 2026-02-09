---
title: "Guide: How to Write a Blog Post Prompt"
date: "2026-02-09"
excerpt: "Stop getting generic AI content. Learn the structured framework for writing powerful prompts that force AI to write like a human expert."
category: "AI Productivity"
tags: ["AI", "Prompt Engineering", "Blogging", "Guide"]
coverImage: "https://raw.githubusercontent.com/MunBock/blog-posts-on-github/refs/heads/main/google-ap2.webp"
author: "Mun Bock Ho"
authorImage: "https://bockdev.com/images/munbock-ho.jpg"
authorBio: "Software Developer and Founder of Bockdev"
---

# Guide: How to Write a Blog Post Prompt

"Write me a blog post about marketing."

We have all been there. You type a vague sentence into ChatGPT, hit enter, and watch as it churns out a generic, robotic, "delving" wall of text that sounds like it was written by... well, a robot.

The frustration is real, but the problem isn't the AI—it's the input. The quality of the output depends strictly on the quality of the prompt.

In this guide, we'll dismantle the "garbage in, garbage out" cycle. You'll learn how to craft structured, powerful prompts that force the AI to write like a human expert, not a generic autocomplete engine.

## I. Define the Role & Persona

The first thing you must do is tell the AI **who** it is. Without a persona, the AI defaults to a neutral, helpful assistant voice that often feels bland. By assigning a specific role, you unlock specialized vocabulary, tone, and perspective.

- **Assign Identity**: Be specific. Instead of "You are a writer," use "Act as a Senior React Developer with 10 years of experience" or "You are a no-nonsense Fitness Coach."
- **Establish Credibility**: Mentioning expertise helps the AI prioritize authoritative information over general knowledge.
- **Set the Voice**: Do you want it to be "authoritative yet accessible" or "witty and conversational"? Define the vibe upfront.

> **Weak**: "Write a blog post about coding."
> **Strong**: "Act as a Senior Python Engineer writing for a technical audience. Your tone should be pragmatic and slightly cynical about over-engineering."

## II. Set the Context & Background (The "Why")

Context is king. If the AI doesn’t understand _why_ you are writing this post, it will guess—and usually guess wrong. You need to frame the discussion.

- **The Problem/Conflict**: Identify the specific pain point the reader is facing. For example, "Junior developers feel isolated in remote work environments."
- **The Goal**: What is the solution? What should the reader walk away with? "By the end of this post, the reader should have 3 actionable strategies to improve their visibility."

Giving the AI a mission prevents it from wandering into irrelevant territory.

## III. Specify the Audience (The "Who")

Writing for a C-level executive is vastly different from writing for a hobbyist. You must tell the AI exactly who is reading.

- **Target Demographics**: Beginners vs. Experts? Managers vs. Individual Contributors?
- **Prior Knowledge**: What do they already know? If you're writing for experts, tell the AI to "skip the basics." If for beginners, ask it to "avoid jargon or explain it simply."
- **Reader Intent**: Are they looking to buy something, learn a new skill, or be entertained?

> **Constraint**: "Assume the reader understands basic JavaScript but struggles with asynchronous patterns."

## IV. Define the Task (The "What")

Don't just ask for a "blog post." Be specific about the format and structure.

- **Content Type**: Do you want a "comprehensive deep-dive," a "listicle," or a "case study"?
- **Key Sections to Cover**: You can guide the structure by asking for specific sections:
  - Introduction (specifically asking for a 'Hook')
  - Core Concepts (The 'Meat')
  - Actionable Tips (The 'How-to')
  - Conclusion & Call to Action (CTA)

_Pro Tip_: Ask the AI to generate 5-10 click-worthy titles _before_ writing the post. It forces the model to brainstorm hooks early.

## V. Set Constraints & Formatting (The "Rules")

This is where you prevent the common AI pitfalls like fluff and weird formatting.

- **Length**: Give a word count range (e.g., "800-1200 words").
- **Formatting**: Explicitly ask for **Markdown**, **H2/H3 headers**, **bullet points**, and **bold text** for emphasis.
- **Restrictions**: Be ruthless here.
  - "No fluff."
  - "Avoid jargon."
  - "Do NOT use words like 'unleash', 'unlock', 'delve', or 'tapestry'."
- **SEO Requirements**: If needed, list keywords to include naturally.

## VI. Review & Refine (The "Loop")

The best content comes from iteration, not a single shot.

- **Iterative Approach**: Ask for an outline _first_. "Generate a detailed outline for my approval before writing the full post." This saves you from generating 1,000 words of the wrong content.
- **"Show, Don't Tell"**: Explicitly ask for examples. "Don't just explain the concept; provide a code snippet or a real-world analogy to illustrate it."
- **Tone Check**: If the output feels off, refine it. "That sounded too robotic. Rewrite the introduction to be more personal, as if you're speaking to a friend."

## VII. Example Prompt Structure (Template)

Ready to write? Copy this template and fill in the brackets for your next post.

```markdown
**Role**: [Insert Persona, e.g., Senior Marketing Strategist]

**Context**:
We are writing a blog post about [Topic].
The problem our readers face is [Pain Point].
Our goal is to provide [Solution/Takeaway].

**Task**:
Write a [Length, e.g., 1000-word] blog post regarding [Topic] for [Audience].

**Outline**:

1.  Introduction (Start with a strong hook)
2.  [Key Point 1]
3.  [Key Point 2]
4.  [Key Point 3 - Actionable Advice]
5.  Conclusion (Summary + Call to Action)

**Constraints**:

- Tone: [e.g., Professional, Witty, Direct]
- Format: Use Markdown with H2/H3 headers.
- Style: Use short paragraphs and bullet points for readability.
- **Restrictions**: Do NOT use the words "delve", "landscape", or "tapestry".
- "Show, Don't Tell": Include at least 2 specific examples or analogies.
```

## Conclusion

Writing great AI content isn't about replacing human creativity; it's about directing it. By treating your prompt as a detailed creative brief rather than a quick question, you turn the AI from a mediocre writer into a high-performing research assistant.

Try the template above on your next post and see the difference structure makes.
