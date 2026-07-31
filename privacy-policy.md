---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy — Vibely

- **Effective date:** 30 July 2026
- **Last updated:** 31 July 2026

Vibely ("Vibely", "we", "us") is operated by Aryan Mehta, an individual operating as
"Vibely Space" and based in New Delhi, India, who is the **data controller** (EU/UK GDPR),
**data fiduciary** (India DPDP Act 2023), and **business** (California CCPA/CPRA) for the
purposes of this policy.

This policy explains what the Vibely mobile app collects, why, who it goes to, and how you
get rid of it.

Vibely is available worldwide. India, the United States, and the EU/EEA are our primary
markets, and this policy carries specific supplements for each — see §14.

**Contact for any privacy question, request, or complaint:** `spacevibely@gmail.com`.
Aryan Mehta personally answers these. For India he is the designated **Grievance Officer**
under the IT Rules 2021 and the person who can answer questions about processing under the
DPDP Act (§14.2); elsewhere he is the contact point for data-protection queries.

Grievances are acknowledged **within 24 hours**; general questions get a reply within 2
business days. Everything is resolved within the period the applicable law requires (§11).

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
| Date of birth | **Required**, when you set up your profile | Proving you meet the 18+ age requirement |
| Gender | Optional, in profile | Optional profile detail |

Date of birth is required — Vibely is 18+, and we check the date you give rather than simply
asking you to tick a box (§8). Gender is optional; the app works without it and your profile
is simply less complete.

We do **not** collect phone numbers.

### 1.2 Information created by using the app

- **Events you host** — title, description, time, and the location you choose.
- **Group chat messages** — messages you send in an event's group chat.
- **Bookings and attendance** — the events you join.
- **Social graph** — friend requests, friendships, and the list of users you have blocked.
- **Place searches** — when you search for a place to host an event, the text you type and an
  approximate area to bias the results are sent to our backend, which queries Google's Places
  service on our behalf and returns suggestions (see §4).
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
- Coordinates are used to run that one search and are **not stored as a location history.**
  The only location we keep is the one you deliberately attach to an event you host, which is
  shown to people browsing that event.
- You can refuse or revoke the permission in system settings at any time. The app remains
  usable; you will need to search or pan the map manually instead of centring on you.

Some laws — notably California's CPRA — classify precise geolocation as **sensitive personal
information**. We treat it that way: it is used to provide the feature you asked for and for
nothing else. See §14.3.

### 1.4 Device and technical data

- A **Firebase Cloud Messaging (FCM) registration token** — an identifier for your app
  install, used solely to deliver push notifications. It is not your advertising ID and is
  not used to track you across apps.
- Standard server-side request data (IP address, timestamps) logged by our backend for
  security and abuse prevention.
- **Crash reports**, via Firebase Crashlytics. When the app crashes we receive a stack trace
  plus basic device and OS details, so we can find and fix the fault. Crash reporting is
  disabled in development builds and is not used to measure your behaviour — there is no
  analytics SDK in the app.

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
advertising, use it to build advertising profiles, or use it to train machine-learning models.

---

## 3. Legal bases (GDPR / India DPDP)

| Purpose | Basis |
|---|---|
| Creating and running your account | Performance of a contract |
| Showing nearby events (location) | Consent — the OS permission prompt; withdrawable at any time |
| Push notifications | Consent — the OS permission prompt; withdrawable at any time |
| Optional profile fields (DOB, gender) | Consent — you choose whether to supply them |
| Moderation, safety, abuse prevention | Legitimate interests, and legal obligation where applicable |
| Security logging and fraud prevention | Legitimate interests |
| Responding to legal process | Legal obligation |

Where we rely on **legitimate interests**, the interest is keeping the service safe for people
who meet strangers in person through it. We have weighed that against your interests and
consider it proportionate because the processing is limited to what moderation and security
require, and because you can object at any time (§7).

Withdrawing consent for location or notifications does not affect the lawfulness of
processing before withdrawal.

---

## 4. Who we share it with

We use a small number of processors. We do not sell data to anyone.

| Recipient | What they receive | Purpose |
|---|---|---|
| **Google — Firebase Cloud Messaging** | FCM token, notification payloads | Delivering push notifications |
| **Google — Sign-In / Identity** | Authentication assertion | Signing you in |
| **Google — Maps SDK** | Map tile and interaction requests from your device | Rendering the map |
| **Google — Places API** | Your place-search text and a bias area, sent from **our backend**, not from your device | Returning place suggestions when you set an event's location |
| **Apple — Sign in with Apple** | Authentication assertion | Signing you in |
| **Google — Firebase Crashlytics** | Crash stack traces, device and OS details | Diagnosing and fixing crashes |
| Our hosting provider | Data stored by the backend at `api.vibelyspace.com` | Running the service |

Google's and Apple's own privacy policies govern their handling of that data.

**Other users** see: your name or username, your profile details you chose to fill in, events
you host, and messages you send in group chats. Your email address is never shown to other
users. Treat anything you post as visible to other participants.

We may disclose information where legally required, or where necessary to investigate fraud,
abuse, or threats to safety.

---

## 5. Storage, security, and retention

### 5.1 Security

- All traffic between the app and our backend is encrypted with HTTPS/TLS. The app's iOS
  App Transport Security configuration permits cleartext only to private local-network
  addresses used during development; public traffic is always encrypted.
- Authentication tokens are stored on your device using the platform secure storage
  (iOS Keychain / Android Keystore), not in plain files.
- Access to the production database is restricted to the operator.

No system is perfectly secure, and we cannot guarantee absolute security.

### 5.2 How long we keep things

| Category | Retention |
|---|---|
| Profile — name, username, email, phone, date of birth, gender | Life of your account. **Overwritten when you delete it** — see §5.3. |
| Events you hosted, bookings, attendance | Cancelled and hidden when you delete your account. The records remain linked to the anonymised account id, not to you. |
| Group chat messages | Messages in a group **you created** are erased outright. Messages you sent in **someone else's** group stay, so the conversation still makes sense to the people in it — but the sender resolves to "Deleted user", not to you. Copies already delivered to other people's devices are outside our control either way. |
| Friends, friend requests, block list | Removed when you delete your account. |
| FCM push token | Deleted outright when you sign out, uninstall, or delete your account. |
| Precise location used for a nearby-events search | Not retained. Used for the request and discarded. |
| Location you attach to an event you host | Life of that event. Cancelled with your account, and no longer linked to you. |
| Server request logs (IP, timestamps) | Up to **12 months**. |
| Crash reports (Crashlytics) | **90 days** — Google's default retention for crash data. |
| Reports you filed about other users | Kept while needed for safety enforcement. Once your account is gone they no longer identify you as reporter. |
| Reports filed **against** you | Kept as an abuse record. Free text and the copy of the reported content are stripped 90 days after the report is settled. |
| Moderation and ban records | The minimum needed to enforce a ban and prevent immediate re-registration. Held as an account identifier, not as your name or email. |
| Records we are legally required to keep | The legally required period, and nothing longer. |

When a retention period ends, or when you withdraw consent and we have no other basis to
keep processing, the data is deleted or irreversibly anonymised.

### 5.3 What "deleting your account" actually does

We are specific about this because "we delete everything" is usually not true, and we would
rather tell you exactly where the line is.

Your account is not simply hidden. When you delete it — or if we remove it — every field that
identifies you is **overwritten in our database**: name, username, email address, phone number,
date of birth, and gender. They are not recoverable, by us or by anyone else.

What remains is an **anonymous account number** with no personal data attached to it. We keep
it because other people's records point at it: a booking on someone else's event, a message in
a group still in use, a report someone filed about conduct. Removing the number outright would
corrupt or destroy those other people's data. Under the GDPR and the DPDP Act this satisfies
your right to erasure — the requirement is that the data stop being attributable to an
identifiable person, which it does.

Two consequences worth stating plainly:

- Anywhere your name used to appear to other users, it now reads **"Deleted user"**.
- Your username is released, so somebody else may later choose it.

Deletion reaches our live systems immediately. Encrypted backups are overwritten on their
normal rotation.

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

**No solely automated decisions.** Content removals, suspensions, and bans are decided by a
person reviewing the report — there is no automated scoring, profiling, or algorithmic
banning. You are therefore not subject to a decision based solely on automated processing
that produces legal or similarly significant effects (GDPR Art. 22). If your account is
actioned you are told why, and you can appeal to `spacevibely@gmail.com`.

---

## 7. Your rights and choices

You can, at any time:

- **Delete your account and data — from inside the app.** Profile → account deletion. This
  is a real deletion request to our backend, not a deactivation. See
  [Delete Your Account]({{ '/account-deletion/' | relative_url }}) for the web-accessible instructions and for
  requesting deletion by email if you no longer have the app installed.
- **Delete part of your data and keep your account.** Most of it you can remove yourself in
  the app — cancel an event, leave one, remove a friend, clear a profile field. For anything
  else, ask us. See [Delete Your Data]({{ '/delete-data/' | relative_url }}).
- **Access, correct, complete, or update** your data — edit your profile in the app, or write
  to `spacevibely@gmail.com`.
- **Get a copy of your data (portability)** — ask us and we will send it in a structured,
  machine-readable format.
- **Withdraw location or notification consent** — revoke the permission in system settings.
  Withdrawal is as easy as giving it.
- **Object to or restrict processing** carried out on the basis of legitimate interests.
- **Lodge a complaint** with your local data protection authority. See §14 for the specific
  route in your region.

We respond to rights requests within the period required by applicable law — see §11 — and
we do not charge for them or treat you differently for making one. We may need to verify
your identity first, and we may decline a request that is manifestly unfounded or excessive,
telling you why.

---

## 8. Children

Vibely is not directed at children and is intended for users aged **18** and over. This is
enforced rather than merely declared: you must give a date of birth to finish setting up a
profile, and **our servers reject any date under 18** — on account creation and on every
later profile edit — so the check cannot be bypassed by altering the app.

We do not knowingly collect personal information from anyone under that age, we do not
profile or behaviourally advertise to anyone, and we do not process children's data at all.
If you believe a child has created an account, contact `spacevibely@gmail.com` and we will
remove it.

---

## 9. International transfers

Our infrastructure and our processors (Google, Apple) may process data outside your country.

- Where data leaves the **EEA or UK**, we rely on appropriate safeguards, including the
  European Commission's Standard Contractual Clauses and the UK International Data Transfer
  Addendum, together with the transfer terms in our processors' data-processing agreements.
- Where data leaves **India**, we transfer only to countries not restricted by the Central
  Government under the DPDP Act.

You can ask us for details of the safeguards that apply to a particular transfer.

---

## 10. Data breaches

If a personal data breach occurs we will investigate it, take steps to contain it, and:

- notify the relevant **EEA/UK supervisory authority within 72 hours** where the breach is
  likely to result in a risk to your rights and freedoms, and notify you directly where the
  risk is high (GDPR Arts. 33–34);
- notify the **Data Protection Board of India and every affected Data Principal**, as the
  DPDP Act requires for any personal data breach;
- notify affected residents and regulators in the United States and elsewhere as the
  applicable state or national law requires.

---

## 11. Response times

| Regime | We respond within |
|---|---|
| EU/UK GDPR | 1 month, extendable by 2 further months for complex requests (we will tell you) |
| **India — IT Rules 2021 grievances** | **Acknowledged in 24 hours, resolved in 15 days** (§14.2) |
| India DPDP | Promptly, and in any case within the period prescribed under the Act |
| California CCPA/CPRA | 45 days, extendable once by a further 45 days |
| Other US states | 45 days, extendable as that state's law allows |
| Everywhere else | 30 days |

The 24-hour acknowledgement is the shortest clock we are held to, so in practice it is the one
we work to for any grievance, wherever you are.

---

## 12. Changes

We will update this policy when the app changes. Material changes will be notified in the app
or by email before they take effect, and the "Last updated" date above will change. Continuing
to use Vibely after an update means you accept the revised policy.

---

## 13. Contact

Aryan Mehta
New Delhi, India
**spacevibely@gmail.com**

A postal address is available on request.

---

## 14. Regional supplements

The policy above applies to everyone. These sections add what specific regimes require.

### 14.1 EEA and United Kingdom

- **Controller:** Aryan Mehta, New Delhi, India — `spacevibely@gmail.com`.
- **Data Protection Officer:** none appointed. We are not required to appoint one: we are a
  sole operator, our core activity is not large-scale systematic monitoring, and we do not
  process special categories of data at scale. The controller above answers data-protection
  questions directly.
- **Your rights** under GDPR Arts. 15–22: access, rectification, erasure, restriction,
  portability, objection, and not to be subject to solely automated decision-making (§6).
- **Withdrawing consent** (Art. 7(3)) does not affect processing already carried out.
- **Transfers** out of the EEA/UK rely on Standard Contractual Clauses and the UK Addendum (§9).
- **Complaints:** you can complain to the supervisory authority in the EU/EEA state where you
  live, work, or where the issue arose — the list is at
  <https://edpb.europa.eu/about-edpb/about-edpb/members_en>. In the UK, to the Information
  Commissioner's Office at <https://ico.org.uk/make-a-complaint/>. We would rather you came to
  us first, but you are not required to.

### 14.2 India — DPDP Act 2023 and the IT Rules 2021

Two regimes apply to us in India, and this section covers both: the **Digital Personal Data
Protection Act, 2023** (how we handle your data) and the **Information Technology
(Intermediary Guidelines and Digital Media Ethics Code) Rules, 2021** (our duties as a platform
that hosts what users post).

#### Grievance Officer

Required by Rule 3(2) of the IT Rules 2021, and the same person handles DPDP grievances:

| | |
|---|---|
| **Name** | Aryan Mehta |
| **Designation** | Grievance Officer, Vibely |
| **Email** | `spacevibely@gmail.com` |
| **Address** | New Delhi, India — full postal address on request |

**Write with "Grievance" in the subject line.** We will **acknowledge your complaint within 24
hours** and **resolve it within 15 days** of receipt, as Rule 3(2)(a) requires. If a complaint
concerns content you want removed, tell us what it is and where to find it.

This channel is for grievances specifically — anything about your personal data, content you
believe breaches our Terms or the law, or a decision we have taken about your account. General
support questions go to the same address and get a reply within 2 business days.

#### DPDP roles

- **Data Fiduciary:** Aryan Mehta, New Delhi, India.
- **Person who can answer questions about processing:** Aryan Mehta, `spacevibely@gmail.com` —
  the Grievance Officer named above. We are not a notified Significant Data Fiduciary and so are
  not required to appoint a Data Protection Officer, nor a Chief Compliance Officer or nodal
  contact under the IT Rules, which apply to significant social media intermediaries only. If
  that changes, this section will name them.
- **This policy is the notice** required by §5 of the Act. The itemised description of the
  personal data we process is in §1, the purposes are in §2, how to exercise your rights is in
  §7, and how to complain to the Board is below.
- **Your rights as a Data Principal:**
  - *Access* (§11) — a summary of the personal data we process, our processing activities, and
    the identities of every other Data Fiduciary and Data Processor we have shared it with,
    plus a description of what was shared. §4 lists these; ask us and we will confirm what
    applies to your account specifically.
  - *Correction, completion, updating and erasure* (§12) — edit your profile in the app, or
    ask us. Erasure is the in-app **Delete account** flow.
  - *Grievance redressal* (§13) — write to the Grievance Officer named above. Acknowledged
    within 24 hours, resolved within 15 days.
  - *Nomination* (§14) — you may nominate another individual to exercise your rights on your
    behalf if you die or become incapacitated. Email us the nominee's name and contact details
    and we will record it against your account.
- **Withdrawal of consent** is as easy as giving it: revoke the OS permission for location or
  notifications, clear an optional profile field, or delete your account. On withdrawal we
  erase the data unless a law requires us to keep it (§5.2).
- **Complaints to the Board:** if our grievance response does not resolve the matter, you may
  complain to the **Data Protection Board of India**. The Act requires you to exhaust our
  grievance process first.
- **Children:** Vibely is 18+ and enforces that at sign-up, so we do not process the personal
  data of a child under §9, and we do not carry out tracking or behavioural advertising at all.
- **Language:** this notice is published in English. Write to us and we will provide it in any
  language in the Eighth Schedule to the Constitution.

### 14.3 United States

#### California (CCPA / CPRA)

**We have not sold or shared personal information for cross-context behavioural advertising
in the preceding 12 months, and we do not do so now.** We have never sold the personal
information of anyone, including minors under 16. Because we do not sell or share, there is
no "Do Not Sell or Share My Personal Information" opt-out to operate — but if that ever
changes, we will add one and tell you before it takes effect.

Categories collected in the preceding 12 months, in the statute's own terms:

| CCPA category | Collected? | What | Source | Purpose | Disclosed to |
|---|---|---|---|---|---|
| A — Identifiers | Yes | Name, email, username, account ID, IP address, FCM token | You; Google/Apple sign-in; your device | Account, notifications, security | Processors in §4 |
| B — Cal. Civ. Code §1798.80(e) records | Yes | Name, email | You | Account | Processors in §4 |
| C — Protected classifications | Yes, optional | Age (from date of birth), gender | You | Age eligibility; optional profile detail | Processors in §4 |
| D — Commercial information | No | — | — | — | — |
| E — Biometric information | No | — | — | — | — |
| F — Internet or network activity | Limited | Server request logs | Your device | Security, abuse prevention | Hosting provider |
| G — Geolocation data | Yes | Precise location while the app is open; the location you attach to an event | Your device, with permission | Nearby events; hosting | Processors in §4 |
| H — Audio, visual, or similar | No | — | — | — | — |
| I — Professional or employment | No | — | — | — | — |
| J — Education information | No | — | — | — | — |
| K — Inferences / profiles | No | — | — | — | — |
| L — Sensitive personal information | Yes | **Precise geolocation** only | Your device, with permission | Providing the nearby-events and hosting features | Processors in §4 |

We use sensitive personal information **only** to perform the service you asked for. We do not
use or disclose it to infer characteristics about you, so the right to limit its use under
§1798.121 is not engaged — but you can still switch location off in system settings at any
time, which stops the collection entirely.

**Your California rights:** to know and access, to delete, to correct, to opt out of sale or
sharing (not applicable — see above), to limit use of sensitive PI (not engaged — see above),
and to **non-discrimination** for exercising any of them. We do not offer financial incentives.
Exercise any of these at `spacevibely@gmail.com`; we respond within 45 days (§11). An
**authorised agent** may act for you with written permission, and we will verify both.

Retention is set out in §5.2 rather than as a single period, because it differs by category.

**Shine the Light** (Cal. Civ. Code §1798.83): we do not disclose personal information to
third parties for their own direct marketing purposes.

#### Other US states

Residents of Virginia, Colorado, Connecticut, Utah, Texas, Oregon, Montana, and other states
with comprehensive privacy laws have broadly equivalent rights — access, correction, deletion,
portability, and opting out of targeted advertising, sale, and profiling with legal or
similarly significant effects. **We do not conduct targeted advertising, sell personal data, or
profile anyone**, so those opt-outs have nothing to apply to; the access, correction, deletion,
and portability rights work exactly as described in §7.

If we refuse a request, you may **appeal** by replying to our decision with "Appeal" in the
subject line. We will respond to the appeal within 45 days with a written explanation, and if
we still refuse we will tell you how to contact your state Attorney General.
