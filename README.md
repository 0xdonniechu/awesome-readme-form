# awesome-readme-form

Personal README playbook — distilled from 3 famous repos plus hard-earned experience, so the next README writes itself.

## Distilled from

| Source | ★ | What I took |
| --- | --- | --- |
| [Best-README-Template](https://github.com/othneildrew/Best-README-Template) | 16k | The standard section skeleton: shields → logo → About → Built With → Getting Started → Usage → Roadmap → Contributing → License → Contact |
| [awesome-readme](https://github.com/matiassingers/awesome-readme) | 21k | 141 sample READMEs — boiled down to the common rules: logo/banner, demo image up front, badges, TOC, copy-pasteable install |
| [dbader/readme-template](https://github.com/dbader/readme-template) | 2k | The minimal version for small repos: 1–2 sentence blurb, install, usage, release history |

## Checklist (apply to a new repo, delete what you don't need)

- [ ] Shields (badges) at the top: build, version, downloads, license — from [shields.io](https://shields.io)
- [ ] Centered logo/banner + name + 1–2 sentence description + Demo / Report Bug / Request Feature links
- [ ] Compact Table of Contents (use `<details>` when long) + back-to-top link at the end of each section
- [ ] About: state the problem it solves + a demo image/GIF RIGHT AWAY — no dry text walls
- [ ] Features: user-facing bullets — no internals (lib names, polling, fonts, About panels…)
- [ ] Built With: major frameworks/libs, as badges
- [ ] Getting Started: Prerequisites + Installation that runs on copy-paste, split by OS when needed
- [ ] Usage: short example + link to full docs
- [ ] Screenshots: 2-column table, pinned `width` (see Images)
- [ ] Roadmap or Release history (pick one; small repos can skip both)
- [ ] Contributing (5-step fork → PR), License, Contact
- [ ] Links/badges in reference style `[][id]`, declared at the bottom to stay tidy

## Images (hard-earned lessons)

- Markdown tables do NOT balance images — always pin a size: `<img src="..." width="400" alt="...">`
- Resize large screenshots before committing: `sips -Z 1600 in.png --out out.png`
- Animated feature → 1 GIF demo instead of 5 static shots
- Side-by-side images share one `width`; a single image can go full-width

## How to use

1. Copy [TEMPLATE.md](TEMPLATE.md) into the new repo as `README.md`
2. Fill in each section per the checklist, delete the rest
3. Re-read once through a stranger's eyes: is the repo's purpose clear in 10 seconds?
