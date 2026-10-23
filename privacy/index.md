---
permalink: /privacy/
title: Sceen Privacy Policy
---

# Sceen Privacy Policy

**Last updated: October 23, 2026**

This is the privacy policy for Sceen, a movie and TV-show rating app
(the "App", "we", "us", "our"). Sceen is run by an independent developer, reachable at
jackgerlach1@gmail.com. This policy
explains what information we collect, why we collect it, who sees it, and
the choices you have.

If anything in this policy is unclear, email **jackgerlach1@gmail.com** and
we will explain it in plain English.

---

## 1. What we collect

When you create an account, we collect:

- **Email address** (used to sign in and recover your account)
- **Display name and username** (shown on your profile). If you sign in
  with Apple or Google, they may share your name with us, and we use it as
  your starting display name; you can change it.
- **Birth year** (used to set your age bracket and tune AI recommendations)
- **Gender**, only if you choose to give it (used to tune AI
  recommendations)
- **Optional profile picture** (only if you upload one)

When you use the App, we collect:

- **Your ratings, watchlist, and "not interested" picks**
- **The titles you search for and the movies you compare**
- **Comments and reactions** you post on other people's ratings, when
  that feature is available
- **Follow / friend relationships** with other users
- **Reports and blocks** — if you report someone, we keep your report: who
  you reported, the reason you chose, and the post, if you reported one. If
  you block someone, we keep that block so the App can hide them from you.
- **Push notification token** (only if you allow notifications)
- **Approximate device timezone** (used to send notifications at a sensible hour)
- **Server error logs** — our servers log errors, with your user ID, so we
  can fix bugs. The App itself does not include a crash reporter.
- **Basic usage records in our own database** — when you last used the
  App, app sessions, how many AI recommendations you have used, shares you
  start, and notifications we sent you
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
- **Connected-service usage log** — only if you connect Sceen to a
  third-party app such as an AI assistant (see §3, "Services you
  connect"): the name of the tool the app called, when, which connected
  app called it, how long it took, and how many rows it returned. Never
  the titles returned, the question you asked, or anything else the app
  was told.
- **AI score-save log** — only if you let a connected app save scores
  (see §3): which title, the old and new score, which app saved it, and
  when, plus a daily count used to enforce the limit.
- **How each score was made** — whether you rated a title through
  comparisons, by entering a number, or through a connected app.

We do **not** collect:

- Your real name (unless you put it in your display name, or Apple or
  Google shares it when you sign in — see above)
- Your address, phone number, or government ID
- Your contacts list, calendar, or location

---

## 2. Why we collect it

| What we collect | What we use it for |
| --- | --- |
| Email + password / OAuth | Authenticate you |
| Username + display name + profile picture | Show your profile to people who follow you |
| Birth year | Map you into an age bracket for AI recommendations; enforce a 13+ age gate |
| Gender (optional) | Tune AI recommendations |
| Ratings, watchlist, comparisons | Run the rating engine and show you titles you might like |
| Push token + timezone | Send you notifications at a reasonable local time |
| Server error logs | Diagnose bugs |
| Basic usage records | Run daily limits, measure how the App is used, avoid sending duplicate notifications |
| Product-analytics events | Understand how the App is used — which features earn their place and where people get stuck — so we can improve it |
| Connected-service usage log | Rate-limit and monitor the apps you connect; detect abuse |
| AI score-save log | Show and undo what a connected app changed; enforce the 100-a-day limit |
| How each score was made | Understand how people use each way of rating |

We do not use your data for advertising, and we do not sell it.

---

## 3. Who sees it

- **You** — everything in your account
- **Other Sceen users** — if your profile is public, which is the
  default, any signed-in user can see your username, display name, profile
  picture, ratings, and watchlist. If you make your profile private, other
  users cannot see your ratings or watchlist, and only people who follow
  you can see your profile.
- **Your friends, in notifications** — a weekly notification to a friend
  (someone you follow who follows you back) can show your display name and
  a rating you gave. See "Notifications" in §4.
- **The Sceen operators (us)** — for support, abuse handling, and
  troubleshooting
- **Reports and blocks** — only the Sceen operators see reports, and the
  person you report is not told who reported them. Only you can see who
  you have blocked. A blocked user is not notified, but they can no longer
  follow you.
- **Apps you connect (for example, an AI assistant)** — only if you
  connect one: your own library, your friends' names, and, when you ask
  for something to watch together, limited information about that friend.
  See "Services you connect" below.
- **Apps you send your export to** — only if you export your library and
  share the file. See "Exporting your library" below.

**Birth year is private.** We never display it on your profile and we never
share it with other users.

### Services you connect (optional)

You can connect Sceen to your own account with a third-party app so that
it can read your Sceen library. Any app that supports the open connector
standard we use (MCP) can ask to connect; the consent page shows you that
app's name and where it will return you. The App offers one-tap setup for
**Claude** (Anthropic), **ChatGPT** (OpenAI), **Grok** (xAI), and
**Gemini** (Google). Approve only apps you trust — we do not vet apps that
ask to connect. Nothing is connected unless you do this yourself.

**How it works.** You start the connection from inside the app you are
connecting, or from the link the Sceen app gives you. That app sends you
to our consent page at `https://legal.getsceen.com/oauth/consent`, where
you sign in to Sceen and approve the connection. Approval gives that app
a credential tied to your Sceen account, and only to yours. The
credential does not expire on its own — it renews automatically until
you disconnect or we revoke it. This is a disclosure you direct: we make
the data below available to that app because you told us to, under your
own account with that app — not under any arrangement between us and
them.

**What a connected app can read:**

- The titles you have rated and the score you gave each one
- Your watchlist
- Your "not interested" list
- The streaming services you selected in your preferences
- Your age bracket (never for users aged 13–17)
- Summary statistics derived from the above (for example, your genre and
  decade breakdown)

A connected app can also search for title metadata (names, years,
posters, where to stream) through our server, the same way the App does.

**Your friends.** When you ask, a connected app can also see the username
and display name of each of your Sceen friends (people who follow you and
whom you follow back), the same names the App already shows you. If you
ask it to pick something to watch with one friend, it can also see, for
that friend only: their 15 highest-rated titles with the scores they
gave, their favorite genres, titles on both your watchlists, and, for
titles it asks about, whether that friend has rated, saved, or passed on
each one. This works only for friends who are 18 or older and whose
profiles are public. A connected app never sees anything else about your
friends.

**What our connector tools never return:** your email address, birth
year, password, comments, your full lists of followers and people you
follow, or any other user's data beyond the friend information described
just above. To identify your account, however, the
sign-in credential we issue to the app carries your email address, your
display name, and — if you signed in with Google or Apple — the name and
picture from that provider (the standard OpenID "email" and "profile"
scopes); the app receives those when you connect, from the credential
rather than from our tools.

**Saving scores — only if you turn it on.** By default a connected app
can only read. If you switch on "Let AI apps save scores" in Settings ›
Connect to AI, a connected app can also save your score for a movie or
show when you ask it to: a new score, or a change to one you already
gave. That is the only change it can make. Our database rejects
connector credentials that try to remove ratings or change your
watchlist, "not interested" list, profile or anything else, and allows
at most 100 saves per day. Scores saved this way work like any other
score: they show everywhere your other scores do, including your
friends' feed for a new rating, and saving a score for a title on your
watchlist takes it off your watchlist. You can turn the switch off at
any time.

**Their rules apply on their side.** Once data reaches the app you
connected, it is handled under that app's own privacy policy and terms —
including whether your conversations are kept or used to improve their
models. We do not control that. Review their policy before you connect.

### Exporting your library (optional)

In Settings › Connect to AI you can export your library as a text file and
share it with any app you choose, such as an AI assistant. The file holds
your ratings with your scores, your watchlist, your "not interested" list,
your streaming services, and the usernames and display names of your
friends. It never includes your email, birth year, or user ID. Once you
share the file, the app you send it to handles it under its own terms; we
do not see or control what happens to it.

**Disconnecting.** Remove the connection in the connected app's settings
(for Claude: Customize → Connectors). You can also email
**jackgerlach1@gmail.com** and we will revoke every connection on your
account. Deleting your Sceen account revokes all connections.

**18 and over only.** You must be 18 or older to connect an app.
Accounts in the 13–17 age bracket are not eligible.

**What we log.** For each request a connected app makes, we record the
tool name, the time, which connected app made it, how long it took, and
how many rows it returned. We never record the titles returned or the
question you asked the app. When a connected app saves a score, we also
keep a record of which title it was, the old and new score, which app
saved it and when, so you can see and undo what an app changed. See §1
and §5.

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
  recommendations. Requests do not include your email, username, user
  ID, or contact info. They do include: your age bracket and gender (if
  you set them); whether you asked for movies or TV shows; the titles
  you have rated, with the scores you gave them — for the type you asked
  about (movies or TV), your whole list if you have rated fewer than
  100, or a sample of your highest- and lowest-rated titles otherwise;
  for a custom request, your 15 highest-rated titles — candidate titles
  our server fetched from TMDB for the model to rank; and — if you typed
  a custom request — the text you typed. Our server tries providers in
  cascade order until one
  succeeds: **Groq, NVIDIA, Cerebras, and Google (Gemini)**. A request
  goes to one provider at a time and moves to the next only if the
  previous one fails; we do not broadcast the same request to all of
  them at once. Whether a provider uses your prompts to
  improve their service or train their models is governed by that
  provider's own terms — we encourage you to review them. We do not
  share data with these providers beyond what is needed to generate a
  recommendation.
- **Apple / Google** — sign-in providers, if you choose them.
- **Cloudflare Turnstile** — checks that a real person is signing up. It
  receives your IP address and basic device and browser signals for that
  check.
- **Notifications (Expo, Apple, and Google)** — Expo's push service, with
  Apple's and Google's, delivers notifications to your device. They
  receive your device's push token and the notification's text. A weekly
  notification can include a friend's display name, a title, and the
  rating that friend gave it.
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

The apps you may choose to connect to your account (see §3, "Services
you connect") are not on this list. We do not send them anything; you
authorize them to read from your account, and you can disconnect them at
any time.

---

## 5. How long we keep it

- **Account and profile** — kept until you delete your account.
- **Ratings, watchlist, comments** — kept until you delete them or your
  account.
- **Push notification token** — replaced when your device reinstalls;
  removed when you sign out.
- **Server error logs** — kept by our hosting provider (Supabase) for a
  limited period set by that provider, then discarded.
- **Basic usage records** — kept while your account exists; deleted with
  your account.
- **Product-analytics events and session replays** — held by Amplitude and
  linked only to an opaque user ID. When you delete your account (or email
  us), we ask Amplitude to delete the events and replays associated with
  your opaque ID within 30 days.
- **Connected-service usage log** — kept while your account exists, so we
  can enforce rate limits and investigate abuse; deleted with your
  account.
- **Reports you file** — kept while your account exists, so we can act on
  repeated abuse; deleted with your account. If the person you reported
  deletes their account, the report stays without their account ID.
- **Blocks** — kept until you unblock, or until either account is deleted.
- **AI score-save log and daily counts** — kept while your account exists,
  so you can see and undo what a connected app changed; deleted with your
  account.
- **Subscription event records** — if you ever subscribed, we keep the
  purchase records we receive from RevenueCat (such as transaction
  identifiers and store-receipt details) after you delete your account,
  for accounting, refunds, and disputes. When you delete your account we
  remove your account ID from these records. We do not sell or share them.
- **Failed sign-out record** — if you signed in with Apple and we could
  not cancel your Apple sign-in when you deleted your account, we keep a
  short note of that failure, with your user ID, so we can finish it.

If you delete your account, we delete your profile, ratings, watchlist,
comments, notification settings, usage records, connected-service usage
log, AI score-save log, the reports you filed, and your blocks within 30
days. The subscription event records
and any failed sign-out record described above are the only data we keep
after that.

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
- **Export your data** — export your library as a text file in Settings ›
  Connect to AI (see §3), or email us and we will send you a JSON export
  of your ratings, watchlist, and profile.
- **Disconnect apps you connected** — in that app's settings, or email
  us and we will revoke every connection on your account (see §3,
  "Services you connect").

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

Accounts in the 13–17 age bracket are not eligible to connect Sceen to a
third-party app (see §3, "Services you connect"); you must be 18 or
older to use that feature.

---

## 8. International transfers

Our servers are operated by Supabase. Depending on the Supabase region your
data is provisioned in, your data may be stored in the United States or
another country. Where required, transfers rely on Supabase's standard
contractual clauses.

Our product-analytics provider, **Amplitude**, is based in the United States,
so the usage events described in §4 are processed there. Our AI providers
(Groq, NVIDIA, Cerebras, and Google), Cloudflare, and Expo are also based
in the United States, so the data §4 says they receive is processed
there. Where required, these transfers rely on standard contractual
clauses.

---

## 9. Security

- Passwords are hashed by Supabase Auth. We never see the plain text.
- API keys for third parties (TMDB, AI providers, Apple, Google) live on
  our server, not in the App.
- Connections to the App use TLS.
- We use database row-level security. You can only write your own data,
  and you can only read your own data plus what other users have chosen
  to make visible (the ratings and watchlists of public profiles — see
  §3). Credentials issued to apps you connect (§3) can read only your own
  library, plus the friend information described in §3 through narrow,
  checked requests. They can change only one thing — your own scores, and
  only if you turn that on — and our database rejects every other write
  from those credentials.

No system is perfectly secure. If you spot a security issue, please email
**jackgerlach1@gmail.com** before disclosing publicly.

---

## 10. Changes and contact

If we change this policy in a way that affects how we use your data, we
will bump the version date at the top of this page and ask you to agree
again the next time you open the App.

Questions, requests, or complaints:

**Email:** jackgerlach1@gmail.com
