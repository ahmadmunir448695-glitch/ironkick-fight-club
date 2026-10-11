# Ironkick Fight & Fitness Club — Website

A fast, static website for a Taekwondo, Boxing and Fitness club, with a separate Ladies section and a Special Kids (Autism & ADHD) program.

## Pages

| Page | File | What's on it |
|---|---|---|
| Home | `index.html` | Hero, Taekwondo, Boxing, Fitness (yoga / cardio / strength), weekly schedule, membership plans, contact + free-trial form |
| Ladies section | `ladies.html` | Ladies-only programs, female trainers, ladies timings, booking form |
| Special Kids | `special-kids.html` | Program for children with autism and ADHD, command-following method, research summary, assessment booking form |
| Thank you | `thanks.html` | Shown after any form is submitted |

## Contact

- WhatsApp / call: **0305 4486950** (`https://wa.me/923054486950`)

## Deploy on Netlify

1. Go to [app.netlify.com](https://app.netlify.com) → **Add new site → Import an existing project → GitHub**.
2. Pick this repository. Leave the build command empty and set the publish directory to `/`.
3. Click **Deploy**.

The three booking forms use **Netlify Forms** — submissions appear in the Netlify dashboard under **Forms**, where you can switch on email notifications.

## Still to fill in

Search the HTML for `[` placeholders and replace them with real details:

- Club address and opening hours
- Membership prices (`[PRICE]`)
- Trainer names and ranks (`[Coach name]`)
- Real class times (the schedule tables use example times)

## Tech

Plain HTML + CSS, no build step. Fonts: Archivo Black and Space Grotesk (Google Fonts). Scroll animations use CSS scroll-driven animations and fall back gracefully in browsers that don't support them, and respect "reduce motion" settings.
