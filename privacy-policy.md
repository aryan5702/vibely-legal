---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy — Vibely

- **Effective date:** 30 July 2026
- **Last updated:** 30 July 2026

Vibely ("Vibely", "we", "us") is operated by Aryan Mehta, an individual operating as
"Vibely Space" and based in New Delhi, India, who is the data controller (GDPR) / data
fiduciary (India DPDP) for the purposes of this policy.

This policy explains what the Vibely mobile app collects, why, who it goes to, and how you
get rid of it.

Questions, requests, or complaints: **spacevibely@gmail.com**.

---

## 1. What we collect

We collect only what the app needs to work. There is no advertising SDK, no analytics SDK,
and no third-party tracker in the app.

### 1.1 Information you give us

| Data | When | Why |
|---|---|---|
| Name | At sign-in, from Google or Apple | Shown to other users on your profile and on events you host |
| Email address | At sign-in, from Google or Apple | Identifies your account; used for service notices |
| Username | You choose it | Your public handle |
| Date of birth | Optional, in profile | Age eligibility |
| Gender | Optional, in profile | Optional profile detail |

Name, date of birth, and gender are optional. The app works without them; your profile is
simply less complete.

We do **not** collect phone numbers.

### 1.2 Information created by using the app

- **Events you host** — title, description, time, and the location you choose.
- **Group chat messages** — messages you send in an event's group chat.
- **Bookings and attendance** — the events you join.
- **Social graph** — friend requests, friendships, and the list of users you have blocked.
- **Reports you submit** — the reported content, the reason you selected, and your identity as
  reporter (see §6).

### 1.3 Location

With your permission, the app reads your device's **precise location** to show events near
you and to set the location of an event you are hosting.

- Location is read **only while the app is open and in the foreground.** The app requests
  only "when in use" permission and does not declare background-location capability, so it
  cannot read your location when closed or backgrounded.
- Each read is a **one-off request at the moment you open the events or explore screen.**
  There is no continuous tracking, no location history, and no background location stream.
- You can refuse or revoke the permission in system settings at any time. The app remains
  usable; you will need to search or pan the map manually instead of centring on you.

### 1.4 Device and technical data

- A **Firebase Cloud Messaging (FCM) registration token** — an identifier for your app
  install, used solely to deliver push notifications. It is not your advertising ID and is
  not used to track you across apps.
- Standard server-side request data (IP address, timestamps) logged by our backend for
  security and abuse prevention.

### 1.5 What we do **not** collect

- No advertising identifiers (IDFA / AAID) and no ad networks.
- No phone number.
- No contacts, photo library, camera, microphone, calendar, or health data.
- No background location.
- No cross-app or cross-site tracking. Our iOS privacy manifest declares
  `NSPrivacyTracking = false` with no tracking domains.
- We do not collect payment information. The app is free and `pricingEnabled` is off.

---

## 2. How we use it

We process your information to:

- create and operate your account and authenticate you;
- show you events near you and let you host, browse, book, and attend events;
- run group chats for events;
- send push notifications you have opted into (event updates, chat messages, friend requests);
- operate the reporting, blocking, and moderation systems described in §6;
- keep the service secure, investigate abuse, and enforce our Terms;
- comply with law.

We do **not** sell your personal information, share it for cross-context behavioural
advertising, or use it to build advertising profiles.

---

## 3. Legal bases (GDPR / India DPDP)

| Purpose | Basis |
|---|---|
| Creating and running your account | Performance of a contract |
| Showing nearby events (location) | Consent — the OS permission prompt; withdrawable at any time |
| Push notifications | Consent — the OS permission prompt; withdrawable at any time |
| Optional profile fields (DOB, gender) | Consent — you choose whether to supply them |
| Moderation, safety, abuse prevention | Legitimate interests, and legal obligation where applicable |
| Responding to legal process | Legal obligation |

Withdrawing consent for location or notifications does not affect the lawfulness of
processing before withdrawal.

---

## 4. Who we share it with

We use a small number of processors. We do not sell data to anyone.

| Recipient | What they receive | Purpose |
|---|---|---|
| **Google — Firebase Cloud Messaging** | FCM token, notification payloads | Delivering push notifications |
| **Google — Sign-In / Identity** | Authentication assertion | Signing you in |
| **Google — Maps & Places SDK** | Map interactions and place queries | Rendering maps, place search |
| **Apple — Sign in with Apple** | Authentication assertion | Signing you in |
| Our hosting provider | Data stored by the backend at `api.vibelyspace.com` | Running the service |

Google's and Apple's own privacy policies govern their handling of that data.

**Other users** see: your name or username, your profile details you chose to fill in, events
you host, and messages you send in group chats. Treat anything you post as visible to other
participants.

We may disclose information where legally required, or where necessary to investigate fraud,
abuse, or threats to safety.

---

## 5. Storage, security, and retention

- All traffic between the app and our backend is encrypted with HTTPS/TLS. The app's iOS
  App Transport Security configuration permits cleartext only to private local-network
  addresses used during development; public traffic is always encrypted.
- Authentication tokens are stored on your device using the platform secure storage
  (iOS Keychain / Android Keystore), not in plain files.
- We keep your data for as long as your account exists. When you delete your account
  (§7) we delete or irreversibly anonymise your personal data.
- Limited records may be retained after deletion where we are legally required to keep them,
  or where necessary to enforce a ban and prevent a banned user from immediately returning.
  Retained moderation records are kept to the minimum needed for that purpose.

---

## 6. Reporting, blocking, and moderation

Vibely carries user-generated content, so it has active moderation.

- **Report** — any event, message, or user can be reported from the app, with a reason:
  spam or scam, harassment or bullying, hate speech, nudity or sexual content, violence or
  threats, fake or fraudulent, impersonation, self-harm or suicide, illegal activity, or
  something else.
- **Block** — you can block any user. Blocking is available directly from the report flow.
- **Enforcement** — we review reports and may remove content, suspend, or permanently ban
  accounts. Banned users are shown a notice and lose access.

Reports include the reported content and your identity as the reporter. We do not disclose
your identity to the person you reported, but we may need to act on the report in ways that
make the subject aware something was reported.

---

## 7. Your rights and choices

You can, at any time:

- **Delete your account and data — from inside the app.** Profile → account deletion. This
  is a real deletion request to our backend, not a deactivation. See
  [Delete Your Account](/account-deletion/) for the web-accessible instructions and for
  requesting deletion by email if you no longer have the app installed.
- **Access, correct, or export** your data — edit your profile in the app, or write to
  spacevibely@gmail.com.
- **Withdraw location or notification consent** — revoke the permission in system settings.
- **Object to or restrict processing**, and **lodge a complaint** with your local data
  protection authority (EEA/UK) or the Data Protection Board of India.

We respond to rights requests within the period required by applicable law (30 days in most
jurisdictions). We may need to verify your identity first.

---

## 8. Children

Vibely is not directed at children and is intended for users aged **18** and over.
We do not knowingly collect personal information from anyone under that age. If you believe a
child has created an account, contact spacevibely@gmail.com and we will remove it.

---

## 9. International transfers

Our infrastructure and our processors (Google, Apple) may process data outside your country.
Where data leaves the EEA/UK we rely on appropriate safeguards, including the European
Commission's Standard Contractual Clauses.

---

## 10. Changes

We will update this policy when the app changes. Material changes will be notified in the app
or by email before they take effect, and the "Last updated" date above will change. Continuing
to use Vibely after an update means you accept the revised policy.

---

## 11. Contact

Aryan Mehta
New Delhi, India
**spacevibely@gmail.com**

A postal address is available on request.
