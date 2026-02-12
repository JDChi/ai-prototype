# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

AI-assisted prototyping project for mobile prototypes and mini-programs. Currently focuses on frontend HTML/CSS development with Tailwind CSS.

## Tech Stack

- **AI Models**: Claude Code + MiniMax 2.1
- **Framework**: Tailwind CSS (via CDN for prototyping)
- **Format**: Single HTML files for mobile prototypes

## Commands

```bash
# View the prototype in browser
open projects/example/short-video-app.html

# Commit and push changes
git add <file> && git commit -m "message" && git push origin main
```

## Code Style

- Use Tailwind CSS utility classes for styling
- Configure custom colors in Tailwind config for brand consistency
- Keep custom CSS minimal (mainly animations)
- Mobile-first responsive design (max-width: 414px for mobile frame)

## Project Structure

Each project lives in its own folder under `projects/`:
```
projects/
├── example/              # Example/prototyping project
│   └── *.html
├── xxx-project/          # New project folder
│   └── *.html
└── yyy-project/          # Another project folder
    └── *.html
```

- Create a new folder for each project
- Keep projects isolated and organized
