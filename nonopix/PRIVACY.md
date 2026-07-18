# NonoPix — Privacy Policy

_Last updated: 2026-07-18_

NonoPix is a daily nonogram (picross) puzzle game. This policy explains what
data the app collects, why it's collected, and how to contact us about it.

## What we collect

- **Solve history** — when you complete a puzzle, the app stores your solve
  time, error count, hint count, and the date in our Supabase database. This
  powers your streak counter, personal-best stats, and leaderboards.
- **Anonymous account id** — on first launch we create an anonymous Supabase
  user so your progress can survive a reinstall. If you sign in with Google
  or Apple later, that same id is upgraded to a real account — your data
  carries over.
- **Name and email from your sign-in provider (optional)** — only if you
  choose to sign in with Google or Apple, we receive the basic profile
  (name, email) they share. It identifies your account and syncs progress
  across devices. We never use it for marketing.
- **Display name and friend groups (optional)** — if you set a display name
  or join a friend leaderboard, those are stored with your profile.
- **Usage events** — the app records gameplay events (e.g. puzzle started,
  puzzle completed) with your platform and app version in our own database
  to understand how features are used. No third-party analytics SDKs are
  involved; this data never leaves our infrastructure.
- **Push token (optional)** — if you opt in to the daily reminder, we store
  the device's Expo push token so we can send the notification. Toggle the
  reminder off to stop deliveries.
- **RevenueCat customer id** — premium status (the shared "Fat Mika Pro"
  entitlement) is managed by RevenueCat. Their customer id is a
  deterministic hash of your account so the same purchase unlocks across
  NonoPix, SumDoku, and future FatMika apps.

## What we don't collect

- No advertising identifiers.
- No location.
- No microphone, camera, contacts, or calendar access.
- No third-party analytics SDKs (Firebase / Mixpanel / Amplitude etc.).
- No third-party data sharing for marketing.

## How long we keep it

Solve rows, profile rows, usage events, and push tokens stay in our database
until you ask us to delete them — see the account-deletion page or email the
address below and we'll wipe everything tied to your account. Anonymous
accounts that haven't been used in 12 months may be deleted automatically.

## Where it lives

- **Supabase** (Postgres + Auth + Edge Functions) — see
  [supabase.com/privacy](https://supabase.com/privacy).
- **RevenueCat** for purchase / entitlement state — see
  [revenuecat.com/privacy](https://www.revenuecat.com/privacy).
- **Expo / EAS** for OTA updates and (if opted-in) push delivery — see
  [expo.dev/privacy](https://expo.dev/privacy).

## Children

NonoPix's content rating is Everyone / 4+. We don't knowingly collect data
from children under 13. If you believe a child has created an account,
email us and we'll delete it.

## Your rights

Email **contact@fatmika.com** to:

- Request a copy of all data tied to your account.
- Delete your account and every row tied to it.
- Ask any other question about how NonoPix handles your data.

Replies typically arrive within a few business days.

## Changes

When this policy changes we'll update the date at the top of this page and
bump the in-app revision so a fresh update carries the new policy URL.

---

NonoPix is part of [FatMika Games](https://github.com/maxbegin) — the same
team behind SumDoku. Premium ("Fat Mika Pro") unlocks across the whole
FatMika puzzle family.
