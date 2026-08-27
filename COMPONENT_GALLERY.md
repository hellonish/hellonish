# GitHub Profile Component Gallery

This is a visual playground for the components considered for the `hellonish` profile. Every section renders the real component directly. Personalized widgets use the `hellonish` account wherever the provider supports it.

> [!NOTE]
> Dynamic widgets depend on third-party public services. If a personalized preview is temporarily rate-limited, use the provider-owned reference preview beside it or open the linked configurator.

## Contents

### Profile composition map

| Page area | Existing gallery options | New community options added below |
|---|---|---|
| **Head / hero** | Custom terminal banner, Capsule Render, Typing SVG | ProfileKit Hero, Cinematic Card, Hacker Card, Neofetch Profile, `svg-terminal` |
| **Skills** | Skill Icons, Shields.io | Go Skill Icons, ProfileKit Tags, Tech DNA |
| **Cards** | Summary Cards, Readme Stats, Streak, Trophy, Metrics | ProfileKit data cards, Profile Cards Action, avatar-centric profile card |
| **Project showcase** | Readme Stats pinned repository | ProfileKit Pin, Linear-style project status, project timeline, auto-generated project index |
| **Activity** | Activity Graph, Contribution Snake | Arcade contribution games, 3D contribution calendar, Contribution City |
| **Extras** | Profile views | Now panel, pet streaks, radar, matrix, heartbeat |

### Original provider lab

1. [Custom terminal banner](#1-custom-terminal-banner)
2. [Shields.io badges](#2-shieldsio-badges)
3. [Profile view counter](#3-profile-view-counter)
4. [Skill Icons](#4-skill-icons)
5. [GitHub Profile Summary Cards](#5-github-profile-summary-cards)
6. [GitHub Readme Stats](#6-github-readme-stats)
7. [GitHub Activity Graph](#7-github-activity-graph)
8. [Contribution Snake](#8-contribution-snake)
9. [Readme Typing SVG](#9-readme-typing-svg)
10. [GitHub Streak Stats](#10-github-streak-stats)
11. [GitHub Profile Trophy](#11-github-profile-trophy)
12. [Capsule Render](#12-capsule-render)
13. [Lowlighter Metrics](#13-lowlighter-metrics)
14. [New community component lab](#14-new-community-component-lab--august-2026)

---

## 1. Custom terminal banner

The current custom-built component. It provides complete control over text, animation, typography, dimensions, and colors without depending on a rendering service.

<p align="center">
  <img src="assets/name-banner.svg" alt="Nishant Sharma terminal banner" width="820" />
</p>

**Useful controls:** SVG `width` and `height`, background and border colors, prompt text, subtitle, cursor behavior, reveal timing, sweep animation, and reduced-motion handling.

---

## 2. Shields.io badges

[Provider and configurator](https://shields.io/badges/static-badge)

### Available styles

| `flat` | `flat-square` | `plastic` |
|:---:|:---:|:---:|
| ![LinkedIn flat](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white) | ![LinkedIn flat-square](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white) | ![LinkedIn plastic](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=plastic&logo=linkedin&logoColor=white) |

| `for-the-badge` | `social` | Brand-matched custom colors |
|:---:|:---:|:---:|
| ![LinkedIn for-the-badge](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white) | ![GitHub social](https://img.shields.io/github/followers/hellonish?style=social) | ![Portfolio badge](https://img.shields.io/badge/Portfolio-hellonish.dev-0d1117?style=flat-square&logo=vercel&logoColor=38bdf8) |

### Suggested contact row

<p align="center">
  <a href="https://www.linkedin.com/in/nishantsh20/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="Connect with Nishant on LinkedIn" /></a>
  <a href="https://www.hellonish.dev"><img src="https://img.shields.io/badge/Portfolio-hellonish.dev-0d1117?style=flat-square&amp;logo=vercel&amp;logoColor=38bdf8" alt="Visit Nishant's portfolio" /></a>
  <a href="https://github.com/hellonish?tab=followers"><img src="https://img.shields.io/github/followers/hellonish?style=flat-square&amp;color=27c93f&amp;labelColor=0d1117&amp;logo=github" alt="Follow hellonish on GitHub" /></a>
</p>

**Useful controls:** `style`, `label`, `color`, `labelColor`, `logo`, `logoColor`, `logoSize`, and `cacheSeconds`.

---

## 3. Profile view counter

[Provider documentation](https://github.com/antonkomarev/github-profile-views-counter)

| Flat | Flat square | For the badge | Abbreviated |
|:---:|:---:|:---:|:---:|
| ![Profile views flat](https://komarev.com/ghpvc/?username=hellonish&label=Profile%20views&color=38bdf8&style=flat) | ![Profile views flat square](https://komarev.com/ghpvc/?username=hellonish&label=Profile%20views&color=38bdf8&style=flat-square) | ![Profile views for the badge](https://komarev.com/ghpvc/?username=hellonish&label=Profile%20views&color=38bdf8&style=for-the-badge) | ![Profile views abbreviated](https://komarev.com/ghpvc/?username=hellonish&label=Views&color=27c93f&style=flat-square&abbreviated=true) |

**Useful controls:** `color`, `style`, `label`, `base`, and `abbreviated`. The provider also offers a hidden `pixel` style.

---

## 4. Skill Icons

[Provider and icon catalog](https://github.com/tandpfun/skill-icons)

### Dark theme

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,nodejs,fastapi,postgres,redis,docker,aws,terraform,githubactions,pytorch,git,linux&amp;theme=dark&amp;perline=8" alt="Nishant's technical stack in dark mode" />
</p>

### Light theme

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,nodejs,fastapi,postgres,redis,docker,aws,terraform,githubactions,pytorch,git,linux&amp;theme=light&amp;perline=8" alt="Nishant's technical stack in light mode" />
</p>

### Automatic light/dark switching

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,ts,react,nextjs,fastapi,postgres,redis,docker&amp;theme=dark" />
    <img src="https://skillicons.dev/icons?i=python,ts,react,nextjs,fastapi,postgres,redis,docker&amp;theme=light" alt="Core technical stack" />
  </picture>
</p>

**Useful controls:** icon IDs and order, `theme=dark|light`, and `perline=1–50`.

---

## 5. GitHub Profile Summary Cards

[Provider documentation and themes](https://github.com/vn7n24fzkq/github-profile-summary-cards)

### Full-width profile details

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=hellonish&amp;theme=github_dark&amp;title_color=38bdf8&amp;text_color=7c8fa8&amp;icon_color=27c93f&amp;chart_color=38bdf8&amp;border_color=1f2a37&amp;bg_color=0d1117&amp;animation=draw" />
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=hellonish&amp;theme=github&amp;title_color=0969da&amp;text_color=57606a&amp;icon_color=1a7f37&amp;chart_color=0969da&amp;border_color=d0d7de&amp;bg_color=f6f8fa&amp;animation=draw" alt="Nishant's GitHub profile details" />
</picture>

### Individual card types

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hellonish&amp;theme=github_dark&amp;title_color=38bdf8&amp;icon_color=27c93f&amp;hide_logo=true&amp;animation=stagger" alt="Nishant's GitHub statistics" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=hellonish&amp;theme=github_dark&amp;title_color=38bdf8&amp;chart_color=27c93f&amp;animation=load" alt="Languages across Nishant's repositories" />
</p>

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=hellonish&amp;theme=github_dark&amp;title_color=38bdf8&amp;chart_color=27c93f&amp;animation=sequence" alt="Languages used in Nishant's commits" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=hellonish&amp;theme=github_dark&amp;utcOffset=-4&amp;title_color=38bdf8&amp;chart_color=27c93f&amp;animation=draw" alt="Nishant's productive commit time" />
</p>

### Theme samples

| `github_dark` | `tokyonight` | `transparent` |
|:---:|:---:|:---:|
| ![GitHub dark summary card](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hellonish&theme=github_dark) | ![Tokyo Night summary card](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hellonish&theme=tokyonight) | ![Transparent summary card](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=hellonish&theme=transparent) |

**Useful controls:** card type, theme, `title_color`, `text_color`, `bg_color`, `border_color`, `icon_color`, `chart_color`, `hide_logo`, `exclude`, `exclude_repos`, `utcOffset`, `animation`, and `duration`.

---

## 6. GitHub Readme Stats

[Provider documentation and themes](https://github.com/anuraghazra/github-readme-stats)

> [!IMPORTANT]
> The shared public deployment can rate-limit. These are personalized live URLs; self-hosting is available if a chosen card needs guaranteed availability.

### General statistics

<p align="center">
  <img height="190" src="https://github-readme-stats.vercel.app/api?username=hellonish&amp;show_icons=true&amp;include_all_commits=true&amp;rank_icon=percentile&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=38bdf8&amp;text_color=7c8fa8&amp;icon_color=27c93f" alt="Nishant's GitHub Readme Stats card" />
</p>

### Language layouts

<p align="center">
  <img height="190" src="https://github-readme-stats.vercel.app/api/top-langs?username=hellonish&amp;layout=compact&amp;langs_count=8&amp;size_weight=0.5&amp;count_weight=0.5&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=38bdf8&amp;text_color=7c8fa8" alt="Nishant's languages in compact layout" />
  <img height="190" src="https://github-readme-stats.vercel.app/api/top-langs?username=hellonish&amp;layout=donut&amp;langs_count=6&amp;size_weight=0.5&amp;count_weight=0.5&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=38bdf8&amp;text_color=7c8fa8" alt="Nishant's languages in donut layout" />
</p>

### Repository cards

<p align="center">
  <a href="https://github.com/hellonish/singularity"><img src="https://github-readme-stats.vercel.app/api/pin?username=hellonish&amp;repo=singularity&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=38bdf8&amp;text_color=7c8fa8&amp;icon_color=27c93f" alt="Singularity repository card" /></a>
  <a href="https://github.com/hellonish/Finassistant"><img src="https://github-readme-stats.vercel.app/api/pin?username=hellonish&amp;repo=Finassistant&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=38bdf8&amp;text_color=7c8fa8&amp;icon_color=27c93f" alt="Finassistant repository card" /></a>
</p>

**Useful controls:** stats shown or hidden, icons, rank style, theme, gradients, custom colors, border visibility and radius, locale, top-language layout, language count, repository exclusions, language weighting, and repository card description height.

---

## 7. GitHub Activity Graph

[Provider documentation and themes](https://github.com/Ashutosh00710/github-readme-activity-graph)

### Personalized branded graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=hellonish&amp;bg_color=0d1117&amp;color=7c8fa8&amp;title_color=38bdf8&amp;line=38bdf8&amp;point=27c93f&amp;area=true&amp;area_color=0ea5e9&amp;hide_border=true&amp;radius=10&amp;height=280&amp;days=45" />
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=hellonish&amp;bg_color=f6f8fa&amp;color=57606a&amp;title_color=0969da&amp;line=0969da&amp;point=1a7f37&amp;area=true&amp;area_color=54aeff&amp;hide_border=true&amp;radius=10&amp;height=280&amp;days=45" alt="Nishant's recent GitHub activity graph" />
</picture>

### Provider-owned `github-compact` reference

![GitHub compact activity graph reference](https://raw.githubusercontent.com/Ashutosh00710/github-readme-activity-graph/main/asset/github-compact.svg)

**Useful controls:** theme, background, title, text, line, point, area and border colors, area visibility, border visibility, radius, height, days, date range, grid, and custom title.

---

## 8. Contribution Snake

[Provider documentation and interactive demo](https://github.com/Platane/snk)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hellonish/hellonish/output/github-snake-dark.svg" />
    <img width="100%" src="https://raw.githubusercontent.com/hellonish/hellonish/output/github-snake.svg" alt="Nishant's contribution graph animated as a snake" />
  </picture>
</p>

**Useful controls:** `palette=github|github-dark|github-light`, `color_snake`, five `color_dots` values, GIF `color_background`, and SVG or GIF output.

Suggested branded palette:

```yaml
outputs: |
  dist/github-snake.svg?color_snake=#38bdf8&color_dots=#ebedf0,#bae6fd,#7dd3fc,#38bdf8,#0284c7
  dist/github-snake-dark.svg?color_snake=#38bdf8&color_dots=#161b22,#0c4a6e,#0369a1,#0ea5e9,#38bdf8
```

---

## 9. Readme Typing SVG

[Provider configurator](https://readme-typing-svg.demolab.com/demo/)

### Terminal-style rotation

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=22&amp;duration=3200&amp;pause=900&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=720&amp;lines=AI+systems+engineer;Multi-agent+research+platforms;Async+backends+%2B+real-time+interfaces" alt="Animated typing introduction" />
</p>

### Green terminal prompt

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;size=18&amp;duration=2600&amp;pause=700&amp;color=27C93F&amp;background=0D111700&amp;center=true&amp;width=720&amp;lines=%24+building+reliable+AI+systems;%24+shipping+research+into+products" alt="Animated green terminal prompt" />
</p>

### Multiline, one-pass variant

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=18&amp;duration=2400&amp;color=38BDF8&amp;center=true&amp;multiline=true&amp;repeat=false&amp;width=720&amp;height=90&amp;lines=Research+%E2%86%92+systems+%E2%86%92+products;Python+%C2%B7+TypeScript+%C2%B7+LLMs+%C2%B7+distributed+backends" alt="One-pass multiline typing introduction" />
</p>

**Useful controls:** lines, font family, font size, text and background colors, dimensions, duration, pause, centering, multiline mode, repeat, separator, and letter spacing.

---

## 10. GitHub Streak Stats

[Provider configurator](https://streak-stats.demolab.com/demo/)

### Personalized light/dark card

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=hellonish&amp;theme=github-dark-blue&amp;hide_border=true&amp;ring=38BDF8&amp;fire=27C93F&amp;currStreakLabel=38BDF8&amp;timezone=America%2FNew_York" />
    <img src="https://streak-stats.demolab.com?user=hellonish&amp;theme=default&amp;hide_border=true&amp;ring=0969DA&amp;fire=1A7F37&amp;currStreakLabel=0969DA&amp;timezone=America%2FNew_York" alt="Nishant's contribution streak" />
  </picture>
</p>

### Provider-owned theme references

| Default | Dark | Transparent |
|:---:|:---:|:---:|
| ![Default streak reference](https://user-images.githubusercontent.com/107488620/183304039-a1fcf05c-0112-493a-9188-778708dc9e8f.png) | ![Dark streak reference](https://user-images.githubusercontent.com/107488620/183304038-2788ab5d-4c02-45e9-a724-990f27061c54.png) | ![Transparent streak reference](https://user-images.githubusercontent.com/20955511/221571948-1b69a2cc-87af-4e96-83fa-f01278c22c33.png) |

**Useful controls:** theme, detailed colors for ring/fire/numbers/labels/dates, gradient background, border and radius, locale, timezone, date format, daily or weekly mode, excluded days, card dimensions, sections, starting year, and animation.

---

## 11. GitHub Profile Trophy

[Provider documentation and themes](https://github.com/ryo-ma/github-profile-trophy)

### Wide terminal-friendly layout

<p align="center">
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=hellonish&amp;theme=gitdimmed&amp;no-frame=true&amp;no-bg=true&amp;column=-1&amp;margin-w=8&amp;margin-h=8" alt="Nishant's GitHub profile trophies" />
</p>

### Theme comparison

| `gitdimmed` | `tokyonight` | `matrix` |
|:---:|:---:|:---:|
| ![Gitdimmed trophies](https://github-profile-trophy.vercel.app/?username=hellonish&theme=gitdimmed&no-frame=true&column=3&row=2) | ![Tokyo Night trophies](https://github-profile-trophy.vercel.app/?username=hellonish&theme=tokyonight&no-frame=true&column=3&row=2) | ![Matrix trophies](https://github-profile-trophy.vercel.app/?username=hellonish&theme=matrix&no-frame=true&column=3&row=2) |

**Useful controls:** theme, rank inclusion/exclusion, row and column count, adaptive columns, title exclusion, `no-frame`, `no-bg`, and horizontal/vertical margins.

---

## 12. Capsule Render

[Provider documentation](https://github.com/kyechan99/capsule-render)

### `rect` — restrained terminal header

![Rect capsule](https://capsule-render.vercel.app/api?type=rect&height=150&color=0:0d1117,100:0c4a6e&text=Nishant%20Sharma&fontColor=38bdf8&fontSize=42&fontAlignY=42&desc=AI%20systems%20%E2%80%A2%20backend%20%E2%80%A2%20full-stack&descAlignY=68&animation=fadeIn)

### `waving` — conventional profile header

![Waving capsule](https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0d1117,50:0c4a6e,100:38bdf8&text=Nishant%20Sharma&fontColor=e6edf3&fontSize=46&desc=Building%20reliable%20AI%20systems&descAlignY=62&animation=fadeIn)

### `venom` — high-energy variant

![Venom capsule](https://capsule-render.vercel.app/api?type=venom&height=210&color=0:0d1117,50:38bdf8,100:27c93f&text=hellonish&fontColor=e6edf3&fontSize=50&animation=twinkling)

### `transparent` — minimal typography

![Transparent capsule](https://capsule-render.vercel.app/api?type=transparent&height=150&text=%24%20whoami&fontColor=38bdf8&fontSize=42&desc=Nishant%20Sharma%20%E2%80%94%20AI%20Engineer&descAlignY=68&animation=blink)

**Useful controls:** shape type, solid/automatic/gradient/custom-gradient color, theme, header or footer section, reversal, height, text, description, text background, animations, font family/color/size, and text/description alignment.

---

## 13. Lowlighter Metrics

[Provider documentation and plugin catalog](https://github.com/lowlighter/metrics)

### Personalized live classic render

<p align="center">
  <img width="480" src="https://metrics.lecoq.io/hellonish?template=classic&amp;config.timezone=America%2FNew_York&amp;base=header%2Cactivity%2Ccommunity%2Crepositories%2Cmetadata" alt="Live personalized Lowlighter Metrics card" />
</p>

### Provider-owned classic reference

<p align="center">
  <img width="480" src="https://raw.githubusercontent.com/lowlighter/metrics/examples/metrics.classic.svg" alt="Lowlighter Metrics classic template reference" />
</p>

### Provider-owned terminal reference

<p align="center">
  <img width="720" src="https://raw.githubusercontent.com/lowlighter/metrics/examples/metrics.terminal.svg" alt="Lowlighter Metrics terminal template reference" />
</p>

**Useful controls:** classic/repository/Markdown/community templates, base sections, display size, timezone, repositories, and plugins for languages, isometric calendar, recent activity, habits, achievements, notable contributions, lines changed, stars, topics, code snippets, WakaTime, LeetCode, Steam, music, and many more. Advanced configurations are normally generated through GitHub Actions.

---

## 14. New community component lab — August 2026

These additions are organized by where they would sit on the profile. Personalized previews use `hellonish`; provider-owned reference renders are clearly labeled when the component is generated by a GitHub Action rather than a public URL.

### Head / hero

#### 14.1 ProfileKit Hero

[Provider and endpoint catalog](https://github.com/starter-series/ProfileKit)

| Grid | Wave |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/hero?name=Nishant%20Sharma&amp;subtitle=AI%20systems%20%E2%80%A2%20backend%20%E2%80%A2%20full-stack&amp;bg=grid&amp;theme=dark" alt="ProfileKit grid hero" /> | <img width="410" src="https://profilekit.vercel.app/api/hero?name=Nishant%20Sharma&amp;subtitle=Building%20reliable%20AI%20systems&amp;bg=wave&amp;theme=dark" alt="ProfileKit wave hero" /> |

| Particles | Gradient |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/hero?name=hellonish&amp;subtitle=Engineer%20%E2%86%92%20Researcher%20%E2%86%92%20Builder&amp;bg=particles&amp;theme=tokyo_night" alt="ProfileKit particles hero" /> | <img width="410" src="https://profilekit.vercel.app/api/hero?name=Nishant%20Sharma&amp;subtitle=Ideas%20into%20working%20systems&amp;bg=gradient&amp;theme=catppuccin_mocha" alt="ProfileKit gradient hero" /> |

**Useful controls:** name, subtitle, `bg=gradient|wave|grid|particles`, alignment, accent color, width, height, and 17 built-in themes including Tokyo Night, Nord, Dracula, Catppuccin, Kanagawa, and Rosé Pine.

#### 14.2 CoolReadme identity cards

[Provider gallery](https://github.com/yerdaulet-damir/awesome-github-readme)

| Cinematic | Hacker |
|:---:|:---:|
| <img width="410" src="https://coolreadme.xyz/api/cinematic?user=hellonish&amp;status=Building%20AI%20systems&amp;focus=Research%20%E2%80%A2%20Backend%20%E2%80%A2%20Product&amp;accent=%2338bdf8" alt="Cinematic profile card" /> | <img width="410" src="https://coolreadme.xyz/api/hacker?user=hellonish&amp;status=systems%20online&amp;accent=%2327c93f" alt="Hacker profile card" /> |

**Useful controls:** username, status, focus line, accent, and provider-specific presentation. Use these when a full banner feels too conventional.

#### 14.3 Neofetch Profile

[Provider and configuration format](https://github.com/jeantimex/neofetch-profile)

<p align="center">
  <img width="760" src="https://neofetch-profile.vercel.app/api?username=hellonish" alt="Neofetch-style GitHub profile for hellonish" />
</p>

**Useful controls:** built-in or custom ASCII image, scale and offsets, colored ASCII, background, visible sections, and a JSON template using live values such as name, bio, company, location, stars, repositories, commits, pull requests, followers, and languages.

#### 14.4 `svg-terminal`

[Generator, blocks, themes, and GitHub Action](https://github.com/williamzujkowski/svg-terminal)

<p align="center">
  <img width="820" src="https://raw.githubusercontent.com/williamzujkowski/svg-terminal/main/examples/demo.svg" alt="svg-terminal provider demo" />
</p>

This self-generated option is especially compatible with the current terminal aesthetic. Compose the screen in YAML from 48 blocks such as `neofetch`, `github-stats`, `github-languages`, `htop`, `systemctl`, `weather`, `matrix-rain`, `progress-bar`, `build-badge`, `fortune`, and custom commands.

**Useful controls:** block order and content, typing animation, terminal chrome, and 20 themes including Dracula, Nord, Tokyo Night, Gruvbox, Catppuccin, Kanagawa, GitHub Light, amber, green phosphor, cyberpunk, and Windows 95.

### Skills

#### 14.5 Go Skill Icons

[Maintained provider fork and icon catalog](https://github.com/LelouchFR/skill-icons)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://go-skill-icons.vercel.app/api/icons?i=python,ts,react,nextjs,fastapi,postgres,redis,docker&amp;theme=dark" />
    <img src="https://go-skill-icons.vercel.app/api/icons?i=python,ts,react,nextjs,fastapi,postgres,redis,docker&amp;theme=light" alt="Core skills rendered by Go Skill Icons" />
  </picture>
</p>

**Useful controls:** icon IDs and order, `theme=dark|light`, and icons per line. This is a newer maintained alternative to the original Skill Icons service.

#### 14.6 ProfileKit Tags

<p align="center">
  <img width="760" src="https://profilekit.vercel.app/api/tags?tags=Python,TypeScript,React,Next.js,FastAPI,PostgreSQL,Redis,Docker&amp;theme=dark" alt="ProfileKit technology tags" />
</p>

**Useful controls:** tag text, ordering, per-tag hexadecimal colors, global theme, and width. This works well when logos feel visually noisy or when a skill has no icon.

#### 14.7 Tech DNA

[Provider documentation](https://github.com/yerdaulet-damir/awesome-github-readme/blob/main/docs/PROFILE-CARDS.md)

> [!NOTE]
> The public Tech DNA endpoint is currently unavailable, so this option is documented without a broken inline image.

```md
![Tech DNA](https://coolreadme.xyz/api/tech-dna?stack=TypeScript,React,Next.js,Node.js,PostgreSQL&label=MY+STACK&theme=dark)
```

**Useful controls:** ordered stack, label, and dark/light theme. The result visualizes a stack as a compact identity strand rather than another icon row.

### Cards

#### 14.8 ProfileKit data cards

[Provider endpoint catalog](https://github.com/starter-series/ProfileKit)

| GitHub stats | Languages |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/stats?username=hellonish&amp;theme=dark" alt="ProfileKit GitHub stats" /> | <img width="410" src="https://profilekit.vercel.app/api/languages?username=hellonish&amp;theme=dark" alt="ProfileKit language card" /> |

| Reviews | Social proof |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/reviews?username=hellonish&amp;theme=dark" alt="ProfileKit pull request reviews" /> | <img width="410" src="https://profilekit.vercel.app/api/social?username=hellonish&amp;theme=dark" alt="ProfileKit social proof card" /> |

**Useful controls:** GitHub username, theme, dimensions, accent color, and endpoint-specific fields. The same provider also offers quote, LeetCode, section, divider, posts, and table-of-contents modules, so a whole profile can share one visual system.

#### 14.9 Profile Cards Action

[Action and card catalog](https://github.com/seijikohara/profile-cards-action)

This is a newer self-generated system: the workflow commits paired light and dark SVGs into your repository, so the result does not depend on a public rendering server.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/overview.dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/overview.light.svg" alt="Profile Cards Action overview reference" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/contributions.dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/contributions.light.svg" alt="Profile Cards Action contributions reference" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/rhythm.dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/seijikohara/profile-cards-action/main/examples/rhythm.light.svg" alt="Profile Cards Action rhythm reference" />
</picture>

**Available cards:** overview, lifetime totals, contribution streak plus 3D trailing year, contribution composition, coding rhythm, and language analysis. **Useful controls:** card selection, light/dark output, locale, timezone, include/exclude repositories, and schedule.

#### 14.10 Avatar-centric profile card

[Provider source](https://github.com/FajarKim/github-readme-profile)

<p align="center">
  <img width="760" src="https://gh-readme-profile.vercel.app/api?username=hellonish&amp;theme=dark" alt="Avatar-centric GitHub profile card for hellonish" />
</p>

**Useful controls:** theme, gradient, avatar visibility/position/quality/size, reversed layout, border, stroke, background, custom title, and excluded statistics.

### Project showcase

#### 14.11 ProfileKit repository pins

| Singularity | Finassistant |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/pin?username=hellonish&amp;repo=singularity&amp;theme=dark" alt="Singularity repository card" /> | <img width="410" src="https://profilekit.vercel.app/api/pin?username=hellonish&amp;repo=Finassistant&amp;theme=dark" alt="Finassistant repository card" /> |

**Useful controls:** username, repository, optional custom description, theme, accent, and width. Unlike a generic stats card, these make actual work the center of the profile.

#### 14.12 Linear-style project status

[Provider gallery](https://github.com/yerdaulet-damir/awesome-github-readme)

<p align="center">
  <img width="760" src="https://coolreadme.xyz/api/linear-card?id=BUILD-001&amp;title=Singularity%20research%20platform&amp;status=in-progress&amp;priority=high" alt="Linear-style Singularity project status" />
</p>

**Useful controls:** issue/project ID, title, `status`, and `priority`. This is useful for a “currently building” project rather than a finished-project archive.

#### 14.13 Project timeline

<p align="center">
  <img width="760" src="https://profilekit.vercel.app/api/timeline?items=2026%3BSingularity%3BMulti-agent%20deep%20research%7C2025%3BWand%3BAI%20career%20intelligence%7C2024%3BSnap2Caption%3BVision-language%20fine-tuning&amp;theme=dark" alt="Project timeline" />
</p>

**Useful controls:** year or date, project title, description, item order, theme, and accent. A timeline communicates progression and range better than a wall of repository cards.

#### 14.14 Auto-generated project index

[Readme Projects Display Action](https://github.com/marketplace/actions/readme-projects-display) can replace a marked section of the README with repositories carrying a chosen topic such as `project`.

| Project | What the card should prove | Best links |
|---|---|---|
| **Singularity** | Multi-agent research systems | Demo · source · architecture |
| **Wand** | AI career intelligence | Demo · case study · source |
| **Snap2Caption** | Vision-language fine-tuning | Model · results · source |

**Useful controls:** repository topic, number of projects, maximum description length, fork inclusion, and sorting by stars or forks. It produces ordinary Markdown, which is faster and more accessible than an image-only showcase.

### Activity

> [!IMPORTANT]
> The existing [Contribution Snake](#8-contribution-snake) stays in the gallery. It remains one of the best activity visuals and already has light/dark plus branded color previews.

#### 14.15 Arcade contribution games

[Generator and GitHub Action](https://github.com/abozanona/pacman-contribution-graph)

<p align="center">
  <img width="820" src="https://raw.githubusercontent.com/Puxhkar/Puxhkar/main/pacman-contribution-graph.svg" alt="Community-generated Pac-Man contribution graph reference" />
</p>

*Community-generated reference; your own Action would render `hellonish` data.*

| Game choices | Theme choices | Other controls |
|---|---|---|
| Pac-Man, Breakout, Galaga, Puzzle Bobble, Bomberman, Minesweeper | GitHub, GitHub Dark, GitLab, GitLab Dark | scenario, animation, player style, output branch |

#### 14.16 3D Contribution Calendar

[Generator and custom-theme format](https://github.com/yoshi389111/github-profile-3d-contrib)

<p align="center">
  <img width="820" src="https://raw.githubusercontent.com/yoshi389111/yoshi389111/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution calendar night rainbow reference" />
</p>

*Provider-author reference; your own Action would render `hellonish` data.*

**Useful controls:** animated or static output, green, seasonal, night view, night green, night rainbow, GitBlock, and fully custom JSON themes.

#### 14.17 Contribution City

[Generator and GitHub Action](https://github.com/mna11/contribution-city)

<p align="center">
  <img width="820" src="https://raw.githubusercontent.com/mna11/contribution-city/main/example.svg" alt="Isometric contribution city reference" />
</p>

*Provider-owned reference; your own Action would render the latest `hellonish` activity.*

The last seven days become an isometric skyline, with each building growing according to commits. This is more playful than a standard heat map while still encoding real activity.

### Extras and living modules

#### 14.18 “Now” panel

<p align="center">
  <img width="760" src="https://profilekit.vercel.app/api/now?building=Singularity%20research%20platform&amp;learning=Agent%20evaluation%20and%20retrieval&amp;reading=Distributed%20systems&amp;theme=dark" alt="What Nishant is doing now" />
</p>

**Useful controls:** building, learning, reading, status text, theme, and colors. This is a compact way to keep the profile current without rewriting the introduction.

#### 14.19 Pet streak cards

[Provider gallery and parameters](https://github.com/yerdaulet-damir/awesome-github-readme)

| Fox | Penguin |
|:---:|:---:|
| <img width="410" src="https://coolreadme.xyz/api/fox-card?user=hellonish&amp;style=compact&amp;accent=%2338bdf8&amp;bg=deep" alt="Fox contribution streak pet" /> | <img width="410" src="https://coolreadme.xyz/api/penguin-card?user=hellonish&amp;style=compact&amp;accent=%2338bdf8&amp;bg=deep" alt="Penguin contribution streak pet" /> |

**Animal choices:** fox, penguin, owl, cat, and dog. **Useful controls:** current and longest streak overrides, total, accent, `bg=dark|midnight|deep`, `style=default|compact|minimal`, breed, and total visibility. The pet evolves through nine stages as the streak grows.

#### 14.20 Ambient status animations

| Matrix identity | System heartbeat |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/matrix?text=hellonish&amp;color=27c93f&amp;theme=dark" alt="Matrix rain identity animation" /> | <img width="410" src="https://profilekit.vercel.app/api/heartbeat?text=systems%20online&amp;bpm=72&amp;color=38bdf8&amp;theme=dark" alt="System heartbeat animation" /> |

| Skills radar | Equalizer |
|:---:|:---:|
| <img width="410" src="https://profilekit.vercel.app/api/radar?labels=AI,Backend,Frontend,Cloud,Data&amp;values=95,90,78,82,86&amp;theme=dark" alt="Technical focus radar" /> | <img width="410" src="https://profilekit.vercel.app/api/equalizer?text=building%20in%20public&amp;color=38bdf8&amp;theme=dark" alt="Building in public equalizer" /> |

**Useful controls:** text, labels, numeric values, BPM, bar count, color, speed, dimensions, and theme. These are best used as small separators or status accents—not all at once.

### Three coherent combinations to try

| Direction | Head | Skills | Proof / projects | Activity | Extras |
|---|---|---|---|---|---|
| **Terminal engineer** | `svg-terminal` | ProfileKit Tags | ProfileKit Pins | Snake | Now panel |
| **Clean product builder** | ProfileKit Grid Hero | Go Skill Icons | Linear status + project timeline | Activity Graph | Profile Cards rhythm |
| **Playful open-source** | Neofetch Profile | Go Skill Icons | Auto-generated project index | Pac-Man or Snake | Evolving pet streak |

The restraint rule: use one option from each column. Multiple animated headers, multiple skill rows, and three contribution graphs together will compete rather than reinforce the story.

---

## Brand palette used in this gallery

| Role | Dark mode | Light mode |
|---|---:|---:|
| Background | `0d1117` | `f6f8fa` |
| Border | `1f2a37` | `d0d7de` |
| Primary cyan | `38bdf8` | `0969da` |
| Success green | `27c93f` | `1a7f37` |
| Muted text | `7c8fa8` | `57606a` |
| Main text | `e6edf3` | `24292f` |

This file is intentionally a gallery rather than the final profile composition. Components selected for the main README should be copied from here and reduced to one coherent visual story.
