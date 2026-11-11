# Privacy Policy — Zhongwen Android App

**Effective date:** 2026-11-11

**Developer / controller:** Setu — contact: **lovlesh@setu.world**
**App:** Zhongwen (`com.setu.zhongwen`), Android, version 1.0

Zhongwen is a local-first Chinese character learning app. "Local-first" is a product
commitment, not a slogan: the app works with no internet connection and this policy
explains exactly what that means for your data.

## 1. Summary

- Zhongwen **does not collect personal data**. No account, no email, no phone number,
  no name, no identifiers.
- Zhongwen **does not transmit data**. The app does not even request the Android
  `INTERNET` permission, so it cannot send your data anywhere.
- Zhongwen **does not share data** with third parties, because it has none to share.
- There are **no ads, no analytics SDKs, no tracking** and no third-party services in
  the app.
- Everything the app stores lives **only on your device** and disappears when you
  uninstall it.

## 2. Information the app stores on your device

The following data is created as you use the app and stored in the app's private,
on-device database (SQLite/Room) and files. This is *your* study data, not data
collected *about* you, and it never leaves the device:

| Stored locally | Purpose |
| --- | --- |
| Review schedule (`cards_srs`) | Your FSRS-6 spaced-repetition state: cards, due times, difficulty/stability values |
| Review history (`review_logs`) | Timestamps and grades of reviews you performed — used locally to tune your schedule |
| Course progress (`course_progress`) | Which lessons/stages are unlocked, available or completed |
| Dictionary / mnemonic annotations | Any study state derived from the bundled dictionary and course content |

Bundled reference data (dictionary entries from CC-CEDICT, character frequency ranks
from SUBTLEX-CH, decomposition/stroke data from MakeMeAHanzi, the community HSK 3.0
list, course content) ships inside the app package. It contains no user data. All
sources are credited on the in-app **About** screen with their licenses.

## 3. Device backup (Android Auto Backup)

The app allows Android's system backup (`android:allowBackup="true"`), which may copy
the app's private data to the Google account backup controlled **by your Android
device/Google account**, under Google's terms. This is OS-level backup infrastructure:
neither the developer receives nor can access that copy. You can disable it in Android
system settings (Settings → Google → Backup, or per-app backup options on your
device).

## 4. No collection, no transmission, no sharing

- **No data is collected** as Play's Data Safety defines "collection".
- **No data is transmitted**, so the questions about encryption in transit are
  not applicable: there is no traffic at all.
- **No data is sold, rented, shared or brokered.** No advertising identifiers are used
  or read.
- The app contains **no third-party SDKs** (no analytics, no crash reporters, no ad
  networks, no social logins).

## 5. Deletion of your data

Because nothing is stored on our servers, there is nothing for us to delete — we
never received it. To delete everything the app holds **on your device**:

1. Uninstall the app (Settings → Apps → Zhongwen → Uninstall), or
2. Settings → Apps → Zhongwen → Storage → Clear storage (removes the database while
   keeping the app installed).

After either action your review history, schedule and course progress are gone.

## 6. Children's privacy

Zhongwen is not directed at children under 13. Because the app collects no personal
information from anyone — including children — no personal data is knowingly collected
from children. If we ever learn that a child provided personal information (which
cannot happen through the app as built), we will delete it on request.

## 7. Permissions

The app requests **no Android runtime permissions** (no internet, location, microphone,
camera, storage, contacts, phone). It reads and writes only its own private app
storage. Future versions that add permissions or connectivity will update this policy
and the Play Data Safety form **before** those builds ship.

## 8. Changes to this policy

Any change will be published in this file in the source repository with an updated
effective date, and reflected in the Play listing. Continued use after an update means
you accept the revised policy.

## 9. Contact

Questions, or requests about this policy: **lovlesh@setu.world**
(GitHub: https://github.com/setu-world/zhongwen-privacy — issues are monitored).

---
