---
layout: default
title: Delete Your Account
permalink: /account-deletion/
---

# Delete your Vibely account and data

**App:** Vibely (`com.vibely.vibelyspace`)
**Developer:** Aryan Mehta (Vibely Space) — spacevibely@gmail.com

This page explains how to delete your Vibely account and what happens to your data. It is
published so you can request deletion **without needing the app installed**.

---

## Option 1 — Delete from inside the app (fastest)

1. Open Vibely and sign in.
2. Go to the **Profile** tab.
3. Choose **Delete account**.
4. Confirm.

Your account is deleted immediately. This is a permanent deletion, not a deactivation — you
cannot sign back in to recover it.

## Option 2 — Request deletion by email

If you have uninstalled the app or cannot sign in, email **spacevibely@gmail.com** from the email
address on your Vibely account with the subject **"Delete my account"**.

We will verify the request and complete deletion within **30 days**. We may ask you for
information to confirm you own the account before acting.

---

## What gets deleted

**Every field that identifies you is overwritten in our database and cannot be recovered:**

- your name, username, email address, phone number, date of birth, and gender;
- your friends, friend requests, and block list;
- your push notification (FCM) token, so notifications stop;
- messages in any group chat **you created**, which are erased outright;
- your hosted events, which are cancelled — along with the bookings and attendance on them.

Anywhere your name used to appear to other people, it now reads **"Deleted user"**. Your
username is released, so somebody else may later choose it.

## What remains, and why

What is left behind is an **anonymous account number** carrying no personal data. We keep it
because other people's records point at it — a booking on someone else's event, a message in a
group still in use, a report someone filed about conduct. Deleting the number outright would
corrupt or destroy data belonging to those other people.

This is what the law asks for. The GDPR (Art. 17) and the DPDP Act (§12) require that data stop
being attributable to an identifiable person; they do not require a row to be destroyed.

Specifically retained:

- **Messages in other people's groups.** Deleting one side of a conversation would leave the
  rest unreadable for everyone still in it, so those messages stay — attributed to
  "Deleted user", not to you.
- **Server request logs.** Routine logs (IP address, timestamps) written before you deleted the
  account age out on their normal cycle, up to **12 months**. They are not linked back to a
  profile once the profile is gone.
- **Crash reports.** Crashlytics keeps crash data for **90 days**, then deletes it.
- **Legal records.** Where law requires us to keep certain records, we keep them for the
  legally required period and nothing longer.
- **Moderation and ban records.** If your account was banned, or was the subject of upheld
  reports, we keep the minimum record needed to enforce that ban and prevent immediate
  re-registration. That record is held against the account number, not against your name or
  email address. Reports you filed about other people survive in a form that no longer
  identifies you as the reporter, so that other users' safety is not undermined by your
  departure.
- **Copies already delivered to others.** Messages you sent that other people have already
  received are not retrievable from their devices.

Deletion reaches our live systems immediately. Encrypted backups are overwritten on their
normal rotation.

The full retention table is in the [Privacy Policy]({{ '/privacy-policy/' | relative_url }}) §5.2, and §5.3
explains the overwrite in more detail.

---

## This is your erasure right

Deleting your account is how you exercise the right to erasure under the EU/UK GDPR
(Art. 17), the right to erasure under India's DPDP Act (§12), and the right to delete under
the California CCPA (§1798.105). You do not need to cite any of that — just use the flow
above. If you would rather have a copy of your data before it goes, ask us first and we will
send it in a machine-readable format.

---

## Questions

**spacevibely@gmail.com**
