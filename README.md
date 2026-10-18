# Youth Finance Focus

An interactive financial-literacy learning platform designed to make essential money concepts approachable for young people.

**Live site:** [youthfinancefocus.netlify.app](https://youthfinancefocus.netlify.app/)

## What it does

Youth Finance Focus turns a nine-week personal-finance curriculum into an interactive web experience. Learners can sign in, work through structured lessons, complete quizzes and activities, and track their progress.

### Curriculum

1. Why money matters
2. Earning money and valuing skills
3. Needs versus wants
4. Creating a budget
5. Understanding taxes and take-home pay
6. Evaluating financial risk
7. Good debt, bad debt, and interest
8. Retirement and compound growth
9. Putting the full financial plan together

### Interactive activities

- Money decision scenarios
- Income and earning simulations
- Needs-versus-wants sorting
- Budget building
- Tax and take-home-pay calculations
- Risk/reward comparisons
- Debt and interest calculators
- Compound-growth projections
- Financial goal tracking

## Product highlights

- Responsive lesson experience for desktop and mobile
- Authentication through Clerk
- Personalized quiz scores and lesson progress
- Immediate feedback in quizzes and interactive exercises
- Friendly visual design focused on clarity rather than financial jargon

## Technical overview

- React 18 single-page application
- Vite production build
- Utility-first responsive styling
- Clerk authentication and user metadata
- Static deployment on Netlify

## Run locally

This repository contains the deployable production build recovered from the live site.

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Repository notes

- The checked-in JavaScript and CSS are production build artifacts, so they are minified.
- The Clerk publishable key is intentionally browser-visible; no private authentication keys or user sessions are stored here.
- The live deployment remains the best place to experience the project.

## Why I built it

Financial concepts are often introduced after young people have already begun making consequential money decisions. I built Youth Finance Focus to make those concepts concrete through small simulations, clear explanations, and feedback-driven practice.

