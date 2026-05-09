---
permalink: /privacy/
title: Sceen Privacy Policy
---

# Sceen Privacy Policy

**Last updated: May 1, 2026**

This is the privacy policy for Sceen, a movie and TV-show rating app
(the "App", "we", "us", "our"). It explains what information we collect,
why we collect it, who sees it, and the choices you have.

If anything in this policy is unclear, email **jackgerlach1@gmail.com** and
we will explain it in plain English.

---

## 1. What we collect

When you create an account, we collect:

- **Email address** (used to sign in and recover your account)
- **Display name and username** (shown on your profile)
- **Birth year** (used to set your age bracket and tune AI recommendations)
- **Optional profile picture** (only if you upload one)

When you use the App, we collect:

- **Your ratings, watchlist, and "not interested" picks**
- **The titles you search for and the movies you compare**
- **Comments and reactions** you post on other people's ratings
- **Follow / friend relationships** with other users
- **Push notification token** (only if you allow notifications)
- **Approximate device timezone** (used to send notifications at a sensible hour)
- **Crash and error logs** (used to fix bugs)

We do **not** collect:

- Your real name (unless you put it in your display name)
- Your address, phone number, or government ID
- Your contacts list, calendar, or location

---

## 2. Why we collect it

| What we collect | What we use it for |
| --- | --- |
| Email + password / OAuth | Authenticate you |
| Username + display name + profile picture | Show your profile to people who follow you |
| Birth year | Map you into an age bracket for AI recommendations; enforce a 13+ age gate |
| Ratings, watchlist, comparisons | Run the rating engine and show you titles you might like |
| Push token + timezone | Send you re-engagement notifications at a reasonable local time |
| Crash logs | Diagnose bugs |

We do not use your data for advertising, and we do not sell it.

---

## 3. Who sees it

- **You** — everything in your account
- **People who follow you on Sceen** — your username, display name, profile
  picture, ratings, comments, and watchlist (subject to your visibility
  settings)
- **The Sceen operators (us)** — for support, abuse handling, and
  troubleshooting

**Birth year is private.** We never display it on your profile and we never
share it with other users.

---

## 4. Third-party services we use

Sceen runs on top of these services, which receive only the data needed for
their job:

- **Supabase** — hosts our database, authentication, and storage (your
  account, ratings, profile picture). Data is stored on Supabase's managed
  Postgres.
- **TMDB (The Movie Database)** — title metadata and posters. Searches you
  perform in the App are routed through our server, which queries TMDB on
  your behalf. TMDB does not see your account.
- **AI providers** — used by our server to generate AI movie and TV
  recommendations. Requests do not include your email or username — only
  an opaque user ID and the prompt context (your tier picks, recent
  ratings, and the recommendation request). Our server tries providers in
  cascade order until one succeeds: **Groq, NVIDIA, Cerebras, Cohere,
  SambaNova, Google (Gemini), and OpenRouter**. A given request reaches
  one of these; we do not broadcast the same request to all of them. Each
  provider acts as a data processor under our instructions and does not
  use your prompts to train their models.
- **Apple / Google** — sign-in providers, if you choose them.
- **Expo Push Notifications** — delivers push notifications to your device.
- **RevenueCat** — manages subscription purchases (only used if you subscribe).
- **Apple App Store / Google Play** — handle payments. We do not see your
  card number.

---

## 5. How long we keep it

- **Account and profile** — kept until you delete your account.
- **Ratings, watchlist, comments** — kept until you delete them or your
  account.
- **Push notification token** — replaced when your device reinstalls;
  removed when you sign out.
- **Crash and error logs** — retained for up to 90 days, then discarded.

If you delete your account, we delete your profile, ratings, watchlist,
comments, and notification settings within 30 days.

---

## 6. Your rights

You can:

- **See your data** — most of it is visible in the App. For anything else,
  email us.
- **Correct your data** — edit your display name, username, profile picture,
  bio, and preferences in the App.
- **Delete your data** — use the "Delete Account" option in the App, or
  email **jackgerlach1@gmail.com** and we will delete your account within 30
  days.
- **Export your data** — email us and we will send you a JSON export of your
  ratings, watchlist, and profile.

These rights apply globally. If you live in the EU, UK, or California, you
also have the legal rights described in GDPR and CCPA — including the right
to object to processing and the right to lodge a complaint with your local
data protection authority.

---

## 7. Children

Sceen is for users **13 and older**. We ask for your birth year when you
sign up and reject accounts under 13. If we learn that we have collected
data from a child under 13, we will delete it.

If you believe a child has signed up using a false birth year, email
**jackgerlach1@gmail.com**.

---

## 8. International transfers

Our servers are operated by Supabase. Depending on the Supabase region your
data is provisioned in, your data may be stored in the United States or
another country. Where required, transfers rely on Supabase's standard
contractual clauses.

---

## 9. Security

- Passwords are hashed by Supabase Auth. We never see the plain text.
- API keys for third parties (TMDB, AI providers, Apple, Google) live on
  our server, not in the App.
- Connections to the App use TLS.
- We use database row-level security so you can only read and write your
  own data.

No system is perfectly secure. If you spot a security issue, please email
**jackgerlach1@gmail.com** before disclosing publicly.

---

## 10. Changes and contact

If we change this policy in a way that affects how we use your data, we
will bump the version date at the top of this page and re-prompt you to
agree on next sign-in.

Questions, requests, or complaints:

**Email:** jackgerlach1@gmail.com
