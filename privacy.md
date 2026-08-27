---
title: Privacy Policy
---

# Privacy Policy for Jimbo's Pick'Em Challenge

Effective date: **August 27, 2026**

Operator: **Jim Hand**

Privacy contact: **jpc.app.support@gmail.com**

This policy describes how Jimbo's Pick'Em Challenge (the “App”) handles
information when you create an account or use the App. Do not publish this
document until the bracketed owner information is completed and the operator
has confirmed it accurately reflects the deployed services.

## Information we handle

We handle the following information to operate the App:

- Your email address and authentication account information, including an
  account identifier managed through Supabase Auth.
- Your profile information: display name, selected preset avatar, and age
  division. The App does not request a date of birth.
- Your private-group information: group names, membership and role, join code,
  and passcode verification data. Group passcodes are stored as bcrypt hashes,
  not as readable passcodes.
- Your game activity: team selections, confidence points, submission status,
  and the weekly and season standings produced from those selections.
- Operational information reasonably needed to run and secure the service, such
  as service request and error information processed by our infrastructure
  providers. Our infrastructure provider currently retains API and database logs for up to 7 days under our production service plan.

The current App does not include advertising, cross-app tracking, analytics,
crash-reporting, push notifications, or collection of location, contacts,
health information, payment information, advertising IDs, photos, or audio.

## How we use information

We use information to create and secure accounts, authenticate users, provide
private groups, save and lock picks, calculate standings, enforce group and
pick-visibility rules, respond to support requests, prevent misuse, and operate
and secure the App.

Confidence points are game-scoring points used only for private-group
standings. They have no monetary value and cannot be exchanged for money or
anything of value.

## Service providers and disclosures

We use Supabase to provide authentication, database, server-side functions, and
related infrastructure. Supabase processes the account, profile, private-group,
and game information described above on our behalf.

The App's server-side service obtains public college-football schedule, ranking,
and scoreboard data from CollegeFootballData.com (CFBD). The implementation
does not send your email address, account identifier, profile, group,
selections, or device data to CFBD.

We do not sell personal information or share it for targeted advertising. We
may disclose information where required by law or to protect the security,
rights, or operation of the App.

## Retention and account deletion

You can permanently delete your account in the App from **More → Delete
Account**. The App asks you to reauthenticate and confirm the deletion. When
the deletion completes, your authentication account and associated profile,
memberships, picks, submissions, and other Auth-linked App data are removed.

To preserve legitimate completed standings in a private group that remains
active, we may retain an anonymous, frozen aggregate completed-game result. It
is displayed only as `Deleted player`. This archive does not retain your
account identifier, email address, profile, display name, raw pick, or selected
team. We do not retain unfinished, live, or simulation history in that archive.

If you owned a group with other members, the App transfers ownership under its
server-side group rule so the group can continue. If you were the sole member,
the group is removed.

Operational logs are generally retained for up to 7 days. Daily database backups are retained for up to 7 days. Information may be retained longer when reasonably necessary to comply with legal obligations, resolve disputes, enforce agreements, or protect the security and integrity of the service.

## Security

We use access controls, authentication, server-side authorization, and
transport security designed to protect App information. No security system is
perfect, so please use a unique password and keep your account credentials
private.

## Children and age considerations

The App asks users to select an age division but does not collect a date of
birth. The App is intended for users age 13 and older and is not directed to children under 13. Users under 13 should not create an account or provide personal information through the App. Do not represent the App as a Kids Category app unless its
actual features, data practices, and App Store configuration meet that
category's requirements.

## Your questions and choices

For privacy questions or to exercise applicable privacy rights, contact
**jpc.app.support@gmail.com**. You can also
delete your account in the App as described above.

## Changes to this policy

We may update this policy when our practices or the App change. We will post
the current version at the public Privacy Policy URL and update the effective
date.

## Publication requirements

Before release, publish this content at a stable, public, unauthenticated HTTPS
URL, configure that URL as `EXPO_PUBLIC_PRIVACY_POLICY_URL` for the release
build, and enter the same URL in App Store Connect. The public support page
must contain real operator contact information and be configured as
`EXPO_PUBLIC_SUPPORT_URL`.




