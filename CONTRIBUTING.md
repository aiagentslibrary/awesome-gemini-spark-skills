# Contributing to Awesome Gemini Spark Skills

Contributions are welcome, but this repo should stay simple, practical, and easy to scan.

## How to Contribute

1. Open an issue with your skill idea, or fork the repo.
2. Add one focused skill or one focused improvement.
3. Use a clear folder name and one `SKILL.md` file.
4. Open a pull request for review.

Maintainers review changes before they are merged. Do not add yourself as a collaborator unless you want someone to have direct write access.

## Good Skill Guidelines

A good skill should be:

- Specific enough to be useful
- Beginner-friendly
- Clear about which apps or connectors it uses
- Safe by default
- Explicit about what requires approval
- Easy to copy and test

## Required Skill Format

Each skill should live in its own folder:

```text
skills/category/skill-name/SKILL.md
```

Use this structure:

```md
---
name: skill-name
description: Short description with natural keywords and trigger phrases.
---

# ✅ Your Skill Name

## Main Goal
## Persona
## Tone
## If the User Says “Hi” or Starts Vaguely
## If the User Gives a Clear Request
## Connected Apps Used
## Approval Rules
## Workflow Process
## Required Output Format
## Final Standard
```

## Approval Rules

Every skill should ask approval before:

- Sending messages
- Editing or deleting files
- Sharing files externally
- Creating or changing calendar events
- Posting publicly
- Spending money
- Booking reservations
- Changing permissions or settings

## Pull Request Checklist

- [ ] The skill is useful and specific.
- [ ] The file uses clean Markdown.
- [ ] The skill includes connected apps used.
- [ ] The skill includes approval rules.
- [ ] No fake claims, fake data, or unsupported integrations were added.
