# Cracked Glasses Studios Website — Agent Instructions

## Project

This is the official website for Cracked Glasses Studios.

The primary game currently being developed by the studio is:

**The Alchemist's Assistant**

## Technology

* Astro
* TypeScript
* Static site generation
* npm
* Git

Keep the project lightweight and minimize unnecessary dependencies.

Do not introduce React, Vue, Svelte, or another frontend framework unless explicitly requested.

## Website Architecture

The site is organized around:

* reusable Astro components
* Astro layouts
* Astro pages
* static assets
* shared styles

Expected structure:

src/
├── components/
├── layouts/
├── pages/
└── styles/

public/
└── assets/

## Current Routes

The planned website structure is:

/
/games
/games/the-alchemists-assistant
/about
/development
/support
/contact

Routes may be added or changed as development progresses.

## Development Rules

1. Inspect existing project files before modifying them when the task requires existing context.
2. Never invent file paths or claim a file was changed unless the change actually occurred.
3. Prefer modifying existing components over duplicating functionality.
4. Keep components reusable.
5. Do not introduce dependencies unless they are necessary.
6. Do not modify configuration files unless the task requires it.
7. Do not remove existing functionality without explicit instruction.
8. Preserve existing design decisions unless the task specifically changes them.
9. Use semantic HTML and accessible navigation.
10. Keep the site responsive.

## Verification

After meaningful code changes:

1. Run `npm run build`.
2. If the build fails, investigate the actual error.
3. Fix the error when it is directly related to the changes.
4. Run the build again.
5. Do not report success unless the build actually succeeds.

## Git

Do not commit changes unless explicitly instructed.

Do not push changes unless explicitly instructed.

## Agent Behavior

Before making a change:

* Understand the requested task.
* Identify the files actually relevant to the task.
* Read only the relevant files.
* Make the smallest appropriate change.
* Verify the result.

Do not repeatedly inspect the same files without a reason.

Do not use filesystem discovery commands when a known file path is already provided.

Do not rewrite unrelated files.

## Design Direction

The website represents an independent game studio.

The visual identity should feel:

* creative
* handcrafted
* professional
* atmospheric
* game-development focused

Avoid generic SaaS styling.

The Alchemist's Assistant should be treated as the studio's primary game and featured prominently.

## Important

When uncertain about architecture or design intent, stop and ask for clarification rather than inventing a major architectural decision.
