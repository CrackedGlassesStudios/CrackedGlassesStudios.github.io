# Cracked Glasses Studios Website — Project Map

## Project Root

`F:\CGSWebsite`

## Application

Cracked Glasses Studios official studio website.

Primary featured game:

`The Alchemist's Assistant`

## Technology

* Astro
* TypeScript
* npm
* Static site generation
* Git

## Directory Structure

```text
src/
├── components/
│   ├── Header.astro
│   └── Footer.astro
│
├── layouts/
│   └── MainLayout.astro
│
├── pages/
│   ├── index.astro
│   └── about.astro
│
└── styles/
```

```text
public/
└── assets/
```

## Architecture

### MainLayout.astro

Location:

`src/layouts/MainLayout.astro`

Purpose:

Global HTML document layout shared by pages.

Responsibilities:

* HTML document structure
* page title
* metadata
* Header
* main content slot
* Footer

Pages should use this layout rather than duplicating the document structure.

### Header.astro

Location:

`src/components/Header.astro`

Purpose:

Global site header and navigation.

The header should be reusable across the website.

### Footer.astro

Location:

`src/components/Footer.astro`

Purpose:

Global site footer.

The footer should be reusable across the website.

## Pages

### Homepage

`src/pages/index.astro`

Purpose:

Primary landing page for Cracked Glasses Studios.

The homepage should prominently introduce the studio and feature The Alchemist's Assistant.

### About

`src/pages/about.astro`

Purpose:

Studio information and identity.

## Planned Routes

```text
/
├── games/
│   └── the-alchemists-assistant/
├── about/
├── development/
├── support/
└── contact/
```

These routes do not necessarily exist yet.

## Planned Game Page

Route:

`/games/the-alchemists-assistant`

Purpose:

Primary promotional page for The Alchemist's Assistant.

Expected content will eventually include:

* game overview
* screenshots/media
* gameplay information
* world/lore information
* development progress
* links to follow/support the project

Do not invent final game information. Use established project information when implementing content.

## Styling

Shared styling will live under:

`src/styles/`

Avoid creating multiple competing global style systems.

Prefer reusable component and page styles where appropriate.

## Assets

Public assets belong under:

`public/assets/`

Do not embed large binary assets directly into Astro source files.

## Dependency Policy

Keep dependencies minimal.

Do not add a frontend framework.

Do not add a UI component library unless explicitly requested.

## Build

The production build command is:

```text
npm run build
```

Expected output:

```text
dist/
```

## Agent Change Strategy

For every task:

1. Read the relevant project instructions.
2. Consult this project map.
3. Identify only the files required for the task.
4. Read those files.
5. Make the smallest appropriate changes.
6. Run the build.
7. Fix build errors caused by the changes.
8. Verify the final result.
9. Do not modify unrelated files.

## Current Project State

The Astro project is initialized.

The current known routes are:

* `/`
* `/about`

The project currently builds successfully.

The website architecture is still in early development.

## Design Direction

Cracked Glasses Studios should feel like an independent game studio rather than a generic software company.

Design characteristics:

* atmospheric
* creative
* handcrafted
* professional
* game-focused

The Alchemist's Assistant is the primary project and should eventually be the visual centerpiece of the website.
