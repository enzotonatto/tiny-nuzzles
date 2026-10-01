---
layout: default
lang: en
title: Privacy policy
permalink: /en/privacy/
alt: /privacidade/
---

# Privacy policy

**Version of September 28, 2026.**

Tiny Nuzzles is a family connection app: the adult uses an iPhone, the child
uses an Apple Watch, and they exchange voice messages, photos and game matches.
This policy explains what data the app keeps, why, where and for how long.

## Who is responsible

The Tiny Nuzzles team. Contact for any privacy matter, including requests under
Brazil's LGPD: **enzotonatto@gmail.com**.

## Children

- An account always belongs to an **adult**. The adult creates the family, adds
  the child and pairs the child's watch, and in doing so consents, as the
  child's legal guardian, to the processing of the child's data described here.
- The child has **no login, email or password**. The watch receives a credential
  when the adult's iPhone pairs it.
- A child's data is only visible to the adults and children of their own
  family. There are no public profiles, no people search and no contact with
  anyone outside the family.
- The app shows no ads and uses nobody's data for advertising.

## What we keep

**About the adult**
- Email, name, date of birth and, if uploaded, a profile photo.
- Password, stored only as a hash (argon2id). Nobody can read it back.
- Relationship to the children (for example, "Mom").

**About the child** (entered by the adult)
- Name or nickname, date of birth, avatar character or photo, and relationship.

**About the family**
- Family name, photo and time zone.
- **Voice messages** recorded by adults and children, and a record of who has
  played each one.
- Photos uploaded by adults (one per day per family).
- Game matches and the family's history of moments.

**About devices**
- Push notification token of the iPhone and of the watch, to announce new
  messages.
- The watch credential (stored only as a hash on the server) and temporary
  invite and pairing codes.
- Sign-in sessions (the refresh token is stored only as a hash).

The app does **not** collect location, contacts, health data or advertising
identifiers. The microphone is only used while you record a message, and the
camera only while scanning the QR code of someone joining your family.

## What we use it for

Only to make the app work: signing in, building the family, delivering
messages, photos and matches to the right people, and notifying you when
something new arrives. We do not sell, rent or share data for marketing.

## Where the data lives

- **Supabase**: database and file storage (audio and photos).
- **Railway**: API server.
- **Apple Push Notification service**: notification delivery.
- **Apple TestFlight**: during testing, Apple may collect crash reports and the
  feedback you send through the TestFlight app, under Apple's own privacy
  policy.

These services process data on our behalf and may be located outside Brazil.
Traffic between the app and the server is always encrypted (HTTPS).

## How long we keep it

- For as long as the account exists.
- Items removed from the timeline can be restored for 30 days and are then
  erased.
- Invites and pairing codes expire within minutes. Sessions expire after 30
  days without use.

## Deleting your account

In **Settings → Account → Delete account**, with your password. Deletion is
immediate and cannot be undone:

- If you are the **only adult** in the family, the whole family goes with it:
  children, messages, photos, matches and paired watches.
- If there are other adults, the family stays with them, and the messages and
  photos you sent are erased with your account. If you own the family,
  transfer ownership first, in Family.

## Your rights

You can ask us to confirm whether we process your data, and for access,
correction, deletion and information about who it is shared with. Write to
enzotonatto@gmail.com; we answer within 15 days.

## Changes to this policy

When it changes, the version and date at the top change too. Changes that affect
children's data will be announced inside the app before they take effect.
