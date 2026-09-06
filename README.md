# FocusBoard

FocusBoard is a productivity web app that helps users plan their work and take mindful breaks — combining a task/board management system with a built-in meditation feature, all wrapped in a simple onboarding-to-subscription flow.

🔗 **Live app:** [focusboard-wine.vercel.app](https://focusboard-wine.vercel.app)

## What it does

FocusBoard gives users a single place to:
- **Create and manage tasks/boards** to organize their work
- **Take guided meditation breaks** to reset focus between work sessions
- **Manage their account and subscription** for continued access
- Go through a simple **onboarding flow** for new users

It's structured as a multi-page experience rather than a single-page app — each core feature lives in its own dedicated page/module.

## Project Structure

| Folder | Purpose |
|---|---|
| `Get-Started/` | Onboarding entry point — first screen new users see (default landing via `index.html`) |
| `Home/` | Main dashboard after login |
| `Login/` | User authentication |
| `Account/` | Account settings and profile management |
| `Create/` | Task/board creation flow |
| `Data/` | Handles storage/persistence of user data (tasks/boards) |
| `Meditate/` | Guided meditation / focus-break feature |
| `Product/` | Product overview/marketing page |
| `Subcription/` | Subscription plans and billing |
| `Contact-us/` | Contact/support page |

## Tech

Built with plain **HTML/CSS/JavaScript** (static multi-page site), deployed on **Vercel**.

## Getting Started

```bash
git clone https://github.com/thisIsAyushFr/FocusBoard.git
cd FocusBoard
```

Open `index.html` in a browser (it auto-redirects to the Get-Started page), or serve the folder with any static file server:

```bash
npx serve .
```

## Status

This is a fork of [AgrimJoshi1/FocusBoard](https://github.com/AgrimJoshi1/FocusBoard).

