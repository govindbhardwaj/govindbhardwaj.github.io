# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Two primary audiences, weighted equally (confirmed):

- **Recruiters and hiring managers** evaluating Govind for a full-time role.
- **Prospective freelance / consulting clients** looking to hire him for DevOps, cloud or app work.

The site has to work for both at once; neither audience gets a separate track.

Secondary: people who use Govind's mobile apps and arrive at `/privacy-policy/` or `/delete-account/` from a Google Play or App Store listing or an in-app link. They come to read a policy or request deletion, not to evaluate Govind.

## Product Purpose

The personal site of Govind Bhardwaj, a full-stack DevOps engineer. Confirmed goals:

1. **Land a new role.** His listed experience ends in Aug 2025 (Altimetrik).
2. **Win consulting / freelance work.**
3. **Build a personal brand through writing.** This is wanted but does not exist yet: there are no posts, and no format or platform has been chosen.

Success means a qualified recruiter or client gets in touch. This is inferred from the site's primary call to action ("Email me", and the closing "Next station: your team" sign), not stated by the user.

The site also hosts the privacy policy and account-deletion pages that the app stores require for Govind's mobile apps. These are an obligation, not a goal. The user did **not** pick "home for my apps" as a purpose, so keep these pages working and reachable, but don't grow them into an app showcase without asking.

## Positioning

One person who both builds software (Java / Spring Boot, Flutter, AngularJS) and runs and secures the infrastructure it ships on (AWS, Docker, Jenkins, monitoring, security hardening). He has production experience on Airbnb's payments platform (70+ microservices, via Altimetrik) and on Indian state-government digital systems (HARTRON, Invest Haryana). The user confirmed that the homepage should lead with "runs systems at scale" (Airbnb payments, 70+ microservices). The rest of this positioning is derived from site copy.

## Operating Context

- **Contact channels:** email `govindbhardwaj@outlook.com` (primary, with a copy-email button), LinkedIn (`/in/govindbhardwaj`) and GitHub (`govindbhardwaj`). Twitter (`kumargovind88`) exists but is not currently linked on the site. There is no contact form.
- **Store-registered URLs:** the legal pages are entered in Google Play Console and App Store Connect, and the apps link to them.

## Capabilities and Constraints

- **Hosting:** static HTML/CSS served by GitHub Pages from `master` of `govindbhardwaj/govindbhardwaj.github.io`. `.nojekyll` is set, so there is no build step and no framework; a push to `master` deploys.
- **Files:** the homepage is a single self-contained `index.html` with inline CSS and a small script. The legal pages (`privacy-policy/index.html`, `delete-account/index.html`) share `assets/legal.css`. The visual system is recorded in `DESIGN.md` and `.impeccable/design.json`.
- **Canonical address:** `https://govindbhardwaj.github.io` (confirmed); there is no custom domain.
- **Fixed URLs:** `/privacy-policy/` and `/delete-account/` must not move, because store compliance depends on them.
- **Everything committed is public.** Any file pushed to `master` is served, including this one at `/PRODUCT.md` and `/DESIGN.md`.
- **Legal page commitments:** the policy makes specific promises: deletion within 30 days, backups purged within 90 days, crash reports kept 90 days, analytics kept at most 14 months, no data sold, and no collection of contacts, SMS, background location, health or biometric data. Any change to the apps or the pages must keep those promises true.
- **Third-party assets:** every page loads the Mukta web font (`@fontsource/mukta@5.2.8`) from `cdn.jsdelivr.net`. There are no other third-party scripts or assets.
- **Résumé:** the homepage has résumé links in place but hidden. They go live once `resume.pdf` is added at the site root and `hidden` is removed from both links.
- **Undecided:** the format and platform for writing (blog section, external platform, etc.).

## Brand Commitments

Existing identity:
- The name **Govind Bhardwaj**, which the site's signs also show in Devanagari (गोविंद भारद्वाज).
- The title **"Full-Stack DevOps Engineer"**.
- The site mark in the header: a station capsule on two line stripes.

Copy is written in the first person. The user has not declared any of these binding beyond the name. The visual identity is recorded in `DESIGN.md`.

## Evidence on Hand

- **Experience** (`index.html` #experience):
  - Altimetrik, Product and Platform Engineer, Jan 2022 – Aug 2025 (Airbnb payments engineering)
  - HSEDC / HARTRON, DevOps Lead, Jan 2021 – Jan 2022
  - SRIT, DevOps and Full-Stack Developer, 2020
  - HSEDC / HARTRON, Full-Stack Developer, Jul 2017 – Jan 2020
  - DRDO intern, 2016
- **Projects:**
  - Airbnb (platform work)
  - Ritam news app (~400K monthly active users; Flutter + Spring Boot)
  - Invest Haryana / HEPC single-window clearance platform
  - The Hacker News Flutter client (Google Play)

  Ritam, Invest Haryana and Airbnb belong to employers or clients. The site describes Govind's contribution, not ownership.
- **Education:** B.Tech, Computer Science and Engineering, GJUS&T Hisar, 2013 – 2017.
- **Open source featured on the homepage:**
  - `monitor-ritam`: an Upptime status page for the Ritam app.
  - `sample-nhipster`: a gateway plus two services, in TypeScript.
  - `samjhi`: a JHipster 6.10.5 app.
- **Numbers used on the homepage:**
  - 70+ microservices (Airbnb payments).
  - ~400K monthly active users (Ritam).
  - Eight years, "in service since 2017".
  - Invest Haryana "ranked 3rd in Ease of Doing Business in India", carried over from the old site's copy.
- **Image assets:**
  - `images/profile.jpg` is the homepage portrait and the social-share image.
  - `images/favicon.ico` is used on every page.
  - `images/profile_old.jpg` is unused.
  - Both photos carry an embedded note on where they came from.
- **Absent, so do not fabricate:** testimonials, client logos, case studies with outcomes beyond the facts above, blog posts, a résumé PDF.

## Product Principles

1. **One story, two audiences.** "Builds and runs production systems" has to read as both hireable and contractable, without splitting the site into separate tracks.
2. **Proof over adjectives.** Claims tie to named companies, systems and numbers already on hand. Never invent metrics, clients or testimonials.
3. **Contact is the conversion.** The path to email or LinkedIn stays obvious from anywhere on the site.
4. **Legal pages are infrastructure.** They keep stable URLs and plain language, stay always reachable, and never compete with the portfolio.
