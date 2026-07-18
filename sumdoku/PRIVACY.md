# SumDoku — Privacy Policy

_Last updated: 2026-07-17_

SumDoku is a daily Killer Sudoku puzzle game. This policy explains what
data the app collects, why it's collected, and how to contact us about it.

## What we collect

- **Solve history** — when you complete a daily or weekly puzzle, the app
  stores your solve time, error count, hint count, and the date in our
  Supabase database. This powers your streak counter, personal-best stats,
  and the weekly leaderboard.
- **Anonymous account id** — on first launch we create an anonymous Supabase
  user so your progress can survive a reinstall. If you sign in later with
  an email one-time code, that same id is upgraded to a real account — your
  data carries over.
- **Email address (optional)** — only if you choose to sign in. It's used
  to send the one-time sign-in code and to sync progress across devices.
  We never use it for marketing.
- **Push token (optional)** — if you opt in to the daily reminder, we store
  the device's Expo push token so we can send the morning notification.
  Toggle the reminder off in Settings to stop deliveries.
- **RevenueCat customer id** — premium status (the shared "Fat Mika Pro"
  entitlement) is managed by RevenueCat. Their customer id is a deterministic
  hash of your account so the same subscription unlocks across NonoPix,
  SumDoku, and Plotto.

## What we don't collect

- No advertising identifiers.
- No location.
- No microphone, camera, contacts, or calendar access.
- No analytics SDKs (Firebase / Mixpanel / Amplitude etc.).
- No third-party data sharing for marketing.

## How long we keep it

Solve rows, profile rows, and push tokens stay in our database until you
ask us to delete them — email the address below and we'll wipe everything
tied to your account. Anonymous accounts that haven't been used in 12
months may be deleted automatically.

## Where it lives

- **Supabase** (Postgres + Auth + Edge Functions) — see
  [supabase.com/privacy](https://supabase.com/privacy).
- **RevenueCat** for subscription / entitlement state — see
  [revenuecat.com/privacy](https://www.revenuecat.com/privacy).
- **Expo / EAS** for OTA updates and (if opted-in) push delivery — see
  [expo.dev/privacy](https://expo.dev/privacy).

## Children

SumDoku's content rating is Everyone / 4+. We don't knowingly collect data
from children under 13. If you believe a child has created an account,
email us and we'll delete it.

## Your rights

Email **maxime.begin@gmail.com** to:

- Request a copy of all data tied to your account.
- Delete your account and every row tied to it.
- Ask any other question about how SumDoku handles your data.

Replies typically arrive within a few business days.

## Changes

When this policy changes we'll update the date at the top of this file and
bump the in-app revision so a fresh OTA carries the new policy URL.

---

SumDoku is part of [FatMika Games](https://github.com/maxbegin) — the same
team behind NonoPix and Plotto. Premium ("Fat Mika Pro") unlocks across
all three apps.
