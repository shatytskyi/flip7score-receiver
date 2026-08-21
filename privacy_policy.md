# Privacy Policy — Flip 7 Score Tracker

**Effective date:** August 21, 2026

This privacy policy applies to the **Flip 7 Score Tracker** app for Android (package
`com.shatytskyi.flip7score`), developed by Serhii Hatytskyi ("I", "me"). It describes what data
the app handles, what little of it leaves your device, and the choices you have.

## The short version

- Everything you enter in the app — player names, scores, groups, settings — **stays on your
  device**. It is never uploaded to me or to any server. Two optional features send it straight to
  another device you or your fellow players own: casting the scoreboard to a TV, and sharing score
  entry with other phones at the same table.
- The app collects **anonymous usage statistics and crash reports** to help me improve it. This
  data contains no names, no accounts, no precise location, and no advertising identifiers.
- You can **turn usage statistics off** at any time in Settings → "Share anonymous usage data".
- The app shows **no ads** and sells no data.

## Data stored only on your device

Player names, scores, round history, saved player groups, and app settings are stored in a local
database on your device. **None of it is ever transmitted to me, and none of it goes to any
server.** Deleting the app's data or uninstalling the app removes it permanently.

Two optional features do send some of it off your phone, and only to a device in the room with
you: casting the scoreboard to a TV, and sharing score entry with another phone. Both are
described below.

When you cast the scoreboard to a TV, the score data is sent directly to the Chromecast device on
your local network for display. It is not sent to my servers.

## Sharing score entry with other phones

The app can let other phones at your table enter scores for the same game ("co-judging") — usually
one, but there is no fixed limit. One phone hosts the game and the others join it. While such a
session is running:

- The phones talk **directly to each other** over Bluetooth and Wi-Fi, using Google's Nearby
  Connections service. The connection is encrypted and does not go through my servers or the
  internet.
- The hosting phone sends the game as it stands: **the game name, each player's name, total score,
  number of rounds played and current position, who has won, and the game settings** (game mode,
  target score and the two Mixed-mode rules). This is the same information everyone at the table is
  already looking at. Round-by-round history is **not** sent.
- A joining phone sends back **the rounds it enters** (the cards picked, or a manually typed
  score) and **its device model name** (for example "Pixel 7"), which the host sees when deciding
  whether to let it in. While that phone is entering a score for a player, its device model is also
  shown to the other phones in the session, so everyone can see the player is taken.
- A joining phone keeps the game only in memory, for as long as the session lasts. It is not
  saved to that phone's own game database.
- Nothing else is transmitted: no contacts, no accounts, no files, no location.
- A session only exists while you start one, and only with a phone whose join request you accept
  by hand. Either side can end it at any time, and closing the app ends it too.
- While you are sharing a game, your phone advertises **the game name** you chose to any nearby
  phone running this app and looking for a game to join. It does not advertise your device name.
  Pick a different game name if you would rather not show it.

### Why the app asks for Bluetooth, Wi-Fi and (on older Android) location permission

Nearby Connections finds the other phones over Bluetooth and Wi-Fi, and Android guards those radios
with permissions:

- **Nearby devices / Bluetooth** (Android 12 and newer) — to discover and connect to the other
  phones. The app declares these as "never used for location".
- **Location** (Android 12L and older only) — on those versions Android required location
  permission before any app could scan for nearby devices, so the app has to ask for it to offer
  the feature at all. **The app never reads, stores or transmits your location**, and the
  permission is not requested on newer Android versions.

These permissions are used only while you are setting up or running a co-judging session.

## Anonymous usage statistics (analytics)

To understand which features are used and how the app can be improved, the app sends anonymous
usage events (for example: "a game was completed", "the TV casting dialog was opened", "a setting
was changed") to **PostHog**, an analytics service, hosted in the **European Union**
(PostHog Cloud EU).

- Events are tied to a **random identifier** generated inside the app. It is not your name, not
  your email, and not an advertising ID; it cannot be used to identify you.
- Events never include player names, scores you enter, or any content you create.
- Your **IP address is discarded** by the analytics service and is not stored with events; only
  a coarse country-level location derived from it is kept.
- If you make a donation inside the app, an anonymous event records which donation tier was
  purchased (never payment details — payments are processed entirely by Google Play).
- **Opt out any time**: Settings → "Share anonymous usage data". When disabled, no usage events
  leave your device.

## Crash reports

The app uses **Firebase Crashlytics** (a Google service) to collect crash reports: stack traces,
the state of the app at the moment of the crash, device model and OS version, and a random
installation identifier. Crash reports help me find and fix bugs. This data is not used for
advertising. See [Google's privacy documentation](https://firebase.google.com/support/privacy)
for details on how Firebase processes this data.

## Purchases

Optional donations are one-time purchases processed by **Google Play**. I never receive or store
your payment details. Google's handling of payment data is described in the
[Google Play Terms of Service](https://play.google.com/about/play-terms/) and Google's privacy
policy.

## Children

The app is a family-friendly score keeper and complies with the Google Play Families Policy. It
collects no personal information from any user, children included: no names, no contact details,
no precise location, and no advertising identifiers. The anonymous identifiers described above
are random, app-scoped, and used solely for aggregate statistics and crash reporting. The location
permission that older Android versions require for finding a nearby phone is an exception only on
paper: as described above, no location is ever read, stored or sent.

## Data retention and deletion

Analytics events and crash reports are anonymous and cannot be linked back to you, which also
means I cannot locate and delete "your" records on request. Analytics data is retained by PostHog
according to its standard retention policy, and crash data by Firebase according to Google's
retention policy. All locally stored data is under your control and disappears when you clear the
app's data or uninstall it. Nothing is retained from a co-judging session: the copy of the game on
each joining phone is held in memory only and is gone when the session ends.

## Changes to this policy

If the app's data practices change, this policy will be updated and the effective date above
revised. Material changes will be reflected in the app's Play Store data safety section as well.

## Contact

Questions about privacy in Flip 7 Score Tracker: **serhii.hatytskyi@gmail.com**
