---
title: "Hello, world. Hello, Astro"
date: "2026-02-07"
tags: ["web dev"]
description: "Notes on building a simple personal site, why Astro made sense, and what might come next."
---

For a while now, I’ve wanted a small landing page that could point people to the various platforms I use, share the occasional piece of writing, and host a few resources.
I’ve taken a couple stabs at building this site, but previous attempts always seemed to morph into a traditional blog format. Before long, I could see it becoming another
product that would require ongoing maintenance just to feel alive.

After seeing people create personal sites using tools like [Linktree](https://linktr.ee/), [Hugo](https://gohugo.io/), and [Astro](https://astro.build/), I decided
I’d try the same.

Linktree felt too simple for what I wanted, so I focused on Hugo and Astro. I reviewed available themes for both systems, and while many felt good, nothing was quite right for me.
Knowing I’d want to create my own theme, I started by digging into the documentation for both tools. Astro felt easier to grasp fairly quickly, so I began planning out what
I actually wanted from a personal site.

## A simple structure

At its core, the site only needed a few things:

- a minimal homepage that acts as a link hub  
- a place for short posts and notes  
- somewhere to host lightweight resources  
- no backend, no database, no runtime complexity  

Most importantly, it needed to stay understandable. I wanted to be able to step away for months and come back without having to relearn the system.

## Why Astro fit

Astro worked well here because it keeps the focus on static content. Pages are just files, posts are just Markdown, and the output is predictable. There’s no pressure to turn everything
into components or wire up client-side behavior. That made it easy to move quickly without feeling like I was committing to a framework-heavy setup. The result is a site that’s fast,
readable, and easy to extend when needed.

## Hosting and sharing

With a static generator selected and a basic theme in place, I started to think about hosting. I already had a domain name purchased, but didn’t want to add another monthly fee to the
ever-growing list of subscriptions we all seem to accumulate.

Because the site is fully static, it can be hosted for free using GitHub Pages. The repository builds the site and serves it directly, with no additional infrastructure required.

The repo itself is public, both for transparency and so others can reference or reuse the structure if they want to build something similar. There’s nothing particularly novel here, but
that’s the point — the setup is intentionally boring and easy to understand.

## What might come next

For now, this site does what I need it to do. It’s a fun project space that gives me the functionality I was looking for. If others end up liking this setup, I may package it into a small
generator or starter theme that can spin up the same structure quickly for others.

## Done is a feature

Building this site reminded me of the benefits of keeping scope small: the site can actually stay finished. If it grows, it will be because it’s useful, not because it needs more surface area.

For now, it’s live, it works, and it’s easy to maintain, which is exactly what I was aiming for. Thanks for checking out my site and taking the time to read these posts.
