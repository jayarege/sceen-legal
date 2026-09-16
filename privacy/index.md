---
permalink: /privacy/
title: Sceen Privacy Policy
---

# Sceen Privacy Policy

**Last updated: September 16, 2026**

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
- **Product-analytics events** — a small set of usage events (for example:
  which tabs and Home sections you open, where you are in onboarding, when you
  complete or abandon a rating, whether you allow notifications, and
  subscription actions). These are tied to an opaque user ID and your age
  bracket — not your name, email, or the specific titles you rate. See §4
  (Amplitude).
- **Session replays** — a recording of how you move through the App: which
  screens you open, where you tap and scroll, and the layout and images on
  screen at the time. Images are not masked: movie posters, and any profile
  picture on screen — yours, or another user's if you view their profile —
  can appear in a replay. Text shown by the App's standard text and input
  components is masked on your device before anything is uploaded, so your
  email, username, birth year, search terms, and the names of titles as
  written on screen are not included. Not recorded for users aged 13–17.
  See §4 (Amplitude).

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
| Product-analytics events | Understand how the App is used — which features earn their place and where people get stuck — so we can improve it |

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
  recommendations. Requests do not include your email, username, or
  contact info. They do include an opaque user ID, your tier picks,
  recent ratings, the recommendation request, and your selected age
  bracket and gender (used to tailor recommendations). Our
  server tries providers in cascade order until one succeeds: **Groq,
  NVIDIA, Cerebras, Cohere, SambaNova, Google (Gemini), and OpenRouter**.
  A given request reaches one of these; we do not broadcast the same
  request to all of them. Whether a provider uses your prompts to
  improve their service or train their models is governed by that
  provider's own terms — we encourage you to review them. We do not
  share data with these providers beyond what is needed to generate a
  recommendation.
- **Apple / Google** — sign-in providers, if you choose them.
- **Expo Push Notifications** — delivers push notifications to your device.
- **Amplitude** — product analytics and session replay. We send a small set
  of usage events (see §1) to Amplitude to understand how the App is used and
  where to improve it. These events are tied to an **opaque user ID** and
  your **age bracket** — never your email, name, username, or birth year. We
  do **not** send the specific titles you rate, search for, or add to your
  watchlist as event data. The events are behavioural (for example "a rating
  was completed", "the Popular section was opened", or a session starting or
  ending); where an event carries a value it is a non-identifying attribute
  such as the numeric rating, the sentiment tier, the number of comparison
  rounds, or the subscription plan. Events also carry basic device
  information — device model and manufacturer, operating system and version,
  platform, and language — so we can reproduce device-specific bugs. We
  switch off the advertising identifier, Apple's vendor identifier, Android's
  App Set ID, and carrier in Amplitude's SDK, and we do not ask Amplitude to
  record your IP address or derive a location from it. This applies to all
  users, including those aged 13–17, and it describes the structured event
  data only —
  Session Replay, described next, is a separate channel that captures
  images.

  We also use Amplitude **Session Replay** to record how you move through the
  App so we can find confusing screens and fix them. A replay captures screen
  layout, taps, scrolls, navigation, and the images on screen at the time —
  including movie posters, and any profile picture visible on screen (yours,
  or another user's if you view their profile) — which means a replay can
  show which titles were on your screen. Text is masked: text shown by the
  App's standard text and input components is obscured on your device before
  upload, so your email, username, birth year, search terms, and title names
  as written on screen are not included. The Settings screen and all consent
  screens are excluded from recording entirely. The masking rules
  are fixed in the App and cannot be loosened remotely. Replays are tied to
  the same opaque user ID as the events and are **never recorded for users
  aged 13–17**.
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
- **Product-analytics events and session replays** — held by Amplitude and
  linked only to an opaque user ID. When you delete your account (or email
  us), we delete the events and replays associated with your opaque ID from
  Amplitude within 30 days.
- **Subscription event records** — if you ever subscribed, the webhook
  records we receive from RevenueCat (transaction identifiers and
  store-receipt fragments) are retained indefinitely after you delete your
  account, with your user ID nulled out, so the rows can no longer be
  linked back to you. We keep them in this anonymized form to power
  aggregate product analytics (see our Terms §7.2 Studio Insights program).

If you delete your account, we delete your profile, ratings, watchlist,
comments, and notification settings within 30 days. The anonymized
subscription event records described above are the only data we retain
beyond that window.

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

For users aged 13–17, the product-analytics data we send to Amplitude is
minimized: it is limited to an opaque user ID, your age bracket, and
behavioural usage events (never your name, email, or the specific titles you
rate), and Session Replay is never turned on for this age group. Where the
law in your region requires it, we can disable analytics for this age group
entirely.

---

## 8. International transfers

Our servers are operated by Supabase. Depending on the Supabase region your
data is provisioned in, your data may be stored in the United States or
another country. Where required, transfers rely on Supabase's standard
contractual clauses.

Our product-analytics provider, **Amplitude**, is based in the United States,
so the usage events described in §4 are processed there. Where required,
transfers to Amplitude rely on standard contractual clauses.

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
