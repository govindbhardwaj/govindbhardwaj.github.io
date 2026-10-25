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

Success means a qualified recruiter or client gets in touch. This is inferred from the site's primary "Get in Touch" call to action, not stated by the user.

The site also hosts the privacy policy and account-deletion pages that the app stores require for Govind's mobile apps. These are an obligation, not a goal. The user did **not** pick "home for my apps" as a purpose, so keep these pages working and reachable, but don't grow them into an app showcase without asking.

## Positioning

One person who both builds software (Java / Spring Boot, Flutter, AngularJS) and runs and secures the infrastructure it ships on (AWS, Docker, Jenkins, monitoring, security hardening). He has production experience on Airbnb's payments platform (70+ microservices, via Altimetrik) and on Indian state-government digital systems (HARTRON, Invest Haryana). *This is derived from existing site copy and was not separately confirmed.*

## Operating Context

- **Contact channels:** email `govindbhardwaj@outlook.com`, LinkedIn (`/in/govindbhardwaj`), GitHub (`govindbhardwaj`), Twitter (`kumargovind88`). There is no contact form.
- **Store-registered URLs:** the legal pages are entered in Google Play Console and App Store Connect, and the apps link to them.

## Capabilities and Constraints

- **Hosting:** static HTML/CSS served by GitHub Pages from `master` of `govindbhardwaj/govindbhardwaj.github.io`. `.nojekyll` is set, so there is no build step and no framework; a push to `master` deploys.
- **Files:** the homepage is a single self-contained `index.html` with inline CSS. The legal pages (`privacy-policy/index.html`, `delete-account/index.html`) share `assets/legal.css`.
- **Canonical address:** `https://govindbhardwaj.github.io` (confirmed); there is no custom domain. The homepage nav label currently says "govindbhardwaj.dev", which is wrong and needs fixing.
- **Fixed URLs:** `/privacy-policy/` and `/delete-account/` must not move, because store compliance depends on them.
- **Everything committed is public.** Any file pushed to `master` is served, including this one at `/PRODUCT.md`.
- **Legal page commitments:** the policy makes specific promises: deletion within 30 days, backups purged within 90 days, crash reports kept 90 days, analytics kept at most 14 months, no data sold, and no collection of contacts, SMS, background location, health or biometric data. Any change to the apps or the pages must keep those promises true.
- **Third-party assets:** technology logos load from `cdn.jsdelivr.net` (simple-icons).
- **Undecided:** the format and platform for writing (blog section, external platform, etc.).

## Brand Commitments

Existing identity: the name **Govind Bhardwaj**, the title **"Full-Stack DevOps Engineer"**, and the monogram **"GB"** in the nav. Existing copy is written in the first person. The user has not declared any of these binding beyond the name.

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
- **Homepage stats:** 8+ years, 70+ microservices managed, 4 companies.
- **Image assets:** `images/profile.jpg`, `images/profile_old.jpg`, `images/favicon.ico`. The current homepage uses none of them; only the legal pages use the favicon.
- **Absent, so do not fabricate:** testimonials, client logos, case studies with outcomes beyond the facts above, blog posts, a résumé PDF.

## Product Principles

1. **One story, two audiences.** "Builds and runs production systems" has to read as both hireable and contractable, without splitting the site into separate tracks.
2. **Proof over adjectives.** Claims tie to named companies, systems and numbers already on hand. Never invent metrics, clients or testimonials.
3. **Contact is the conversion.** The path to email or LinkedIn stays obvious from anywhere on the site.
4. **Legal pages are infrastructure.** They keep stable URLs and plain language, stay always reachable, and never compete with the portfolio.
