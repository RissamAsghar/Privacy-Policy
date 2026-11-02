# Privacy Policy for Med Folio

**Effective Date:** October 14, 2026
**Last Updated:** November 2, 2026
**Developer:** Effitron
**Contact Email:** effitron.official@outlook.com

---

## Overview

Effitron operates the Med Folio mobile application (the "App"). This Privacy Policy explains what
information the App handles, where it is stored, who it is shared with, and how you can delete it.
It covers the medicine directory, package scanner, medication reminders and dose log, health
calculators, Nearby pharmacies and clinics, Pomodoro timer, and study notebooks and flashcards.

Med Folio is built offline-first. **We (Effitron) do not run our own servers that collect your
personal or health information, we do not have user accounts, and we never sell your data.** What
you enter stays on your phone unless you choose to back it up to your own Google Drive.

---

## 1. Information Stored on Your Device

Everything below is stored only in the App's private storage on your phone. The App's personal
database is encrypted (SQLCipher), and sensitive values are protected with a key held in the
Android Keystore.

- **Your medications, reminders and dose history:** the medicines you add, their schedules, stock
  and refill counts, and the doses you mark as taken, skipped or snoozed.
- **Your profile (optional):** your name, blood group, allergies and a profile photo, if you choose
  to enter them.
- **Body measurements (optional):** sex, age, height, weight, waist and activity level that you
  enter in the calculators, saved so you don't have to type them again. They are used on your
  device to calculate BMI, BMR, daily calories, ideal body weight, hydration and heart-rate zones.
- **Notebooks and flashcards:** notes, checklists, flashcard decks, voice recordings and images
  (chosen with the Android Photo Picker or taken with the camera).
- **Saved items and settings:** bookmarked medicines and formulas, recent searches, Pomodoro
  sessions, the medicine databases you downloaded, and your app preferences.

We have no access to any of this information.

---

## 2. Device Permissions and How We Use Them

Med Folio asks for each permission only when you use the feature that needs it.

- **Camera:** only when you open the Medicine Scanner or take a photo for a note. Text and barcode
  recognition run entirely on your device (Google ML Kit, on-device). Camera frames are not saved
  or uploaded.
- **Microphone:** only when you tap the microphone for Voice Search or record a Voice Note. Voice
  Notes are saved in the App's private storage. Voice Search uses your phone's speech recognition
  service (usually Google), which converts your speech to text under that provider's privacy
  policy. The App never records in the background.
- **Location (precise or approximate):** only when you open **Nearby** to find pharmacies and
  clinics. While you use the App, a search you started may finish even if you switch to another
  tab. Location is never used when the App is closed or in the background, is not stored, and is
  not sold. The App does not request background location.
- **Biometrics / screen lock:** used through Android's BiometricPrompt to lock private notes. The
  App only receives a pass or fail result. It never sees or stores your fingerprint or face data.
- **Notifications, exact alarms and start at boot:** used on your device to ring your medication
  and note reminders at the times you set, and to restore them after your phone restarts.
- **Internet and network state:** used to download medicine databases, show ads to free users,
  process purchases, run Nearby searches and make the optional Google Drive backup.

---

## 3. Backups

- **Android Auto Backup is turned off.** The App does not use Android's automatic backup to your
  Google account.
- **Optional Google Drive backup:** if you choose "Back up to Google Drive", the App asks you to
  sign in with Google and requests only the `drive.appdata` permission. Your backup (profile,
  medications, reminders, dose history, notebooks with their images and recordings) is saved as a
  file in a hidden, app-only folder in **your own** Google Drive.
  - Med Folio cannot see or change any of your other Drive files.
  - The backup goes directly from your phone to Google. It never passes through our servers.
  - The backup file is protected by your Google account and Google's encryption in transit and at
    rest. The App does not add its own extra encryption to it.
- **Export to a file:** you can save a full copy of your data as a file you choose ("Export all my
  data"). That file is yours to keep or delete.

---

## 4. Third-Party Services

These services have their own privacy policies:

- **Google Play Billing:** processes Pro subscriptions (Monthly, Yearly) and the Lifetime purchase.
  We never see or store your card or wallet details.
  Policy: https://policies.google.com/privacy
- **Google AdMob and the User Messaging Platform (free version only):** shows ads to free users.
  AdMob may collect your device's advertising ID, IP address and diagnostic data to show ads and
  prevent fraud. Where the law requires it, you are asked for consent first, and you can change
  your choice at any time in **Privacy & Security → Your data → Privacy choices for ads**. Med
  Folio Pro removes all ads. Ads are not shown on medication screens.
  Policy: https://policies.google.com/privacy
- **Google ML Kit (on-device):** reads medicine names and barcodes on your phone for the scanner.
  Policy: https://policies.google.com/privacy
- **Google Sign-In:** used only for the optional Google Drive backup.
  Policy: https://policies.google.com/privacy
- **Cloudflare (R2):** stores the medicine databases you download, such as Pakistan, Canada and
  USA. To download a file, your phone connects to Cloudflare, which sees your IP address like any
  website would. No personal or health information is sent.
  Policy: https://www.cloudflare.com/privacypolicy/
- **OpenStreetMap (map tiles, Nominatim and Overpass):** used by Nearby to show the map and find
  nearby pharmacies and clinics. The search area around your location is sent directly to these
  public services to get results. We do not log or keep it.
  Policy: https://wiki.osmfoundation.org/wiki/Privacy_Policy

---

## 5. Data Retention and How to Delete Your Data

Your data stays on your phone until you delete it. You can delete it at any time, in any of the
following ways. **Med Folio has no user accounts, so there is no account to close.** Deleting your
data in the App removes everything we could ever hold about you.

### A. Delete everything from inside the App (recommended)

1. Open **Med Folio**.
2. Tap the **⋮ menu** (top right of the Home screen) → **Privacy & Security**.
3. Under **Your data**, tap **Delete all my data**.
4. To remove your cloud copy too, tick **Also delete my Google Drive backup**. This also signs the
   App out of Google.
5. Tap **Delete everything**.

This permanently removes from your phone:
- reminders and dose history;
- medications;
- profile and photo;
- body measurements;
- saved medicines;
- notebooks and flashcards, with their images and recordings;
- all settings.

All alarms and notifications are cancelled, and the App restarts as if newly installed. This
cannot be undone, so tap **Export a copy first** if you want to keep a copy.

### B. Delete individual items

You can delete any single medication, reminder, note, recording, image, flashcard, deck or
bookmark from its own screen in the App.

### C. Delete with Android settings or by uninstalling

Go to **Android Settings → Apps → Med Folio → Storage → Clear storage**, or uninstall the App.
Either way, all data on your phone is erased. Your Google Drive backup, if you made one, is kept
until you delete it with option A or D.

### D. Delete your Google Drive backup without the App

- Open **https://drive.google.com** → **Settings** (⚙) → **Manage apps** → **Med Folio** →
  **Options** → **Delete hidden app data**.
- To remove the App's access to your Google account, go to
  **https://myaccount.google.com/permissions**, choose **Med Folio** and remove access.

### E. Ad and purchase data

- Reset or delete your advertising ID in **Android Settings → Google → Ads** (or **Privacy → Ads**).
- Purchase records are kept by Google Play under Google's policy. You can see them in the Play
  Store under **Payments & subscriptions**.

### F. Ask us

If you need help, email **effitron.official@outlook.com** with the subject "Data deletion". We hold
no personal data on our side, so we will guide you through the steps above. We reply within 30
days.

---

## 6. Educational and Medical Disclaimer

Med Folio is an educational reference and study tool. It is not a medical device and does not
give medical advice, diagnosis or treatment. Always follow your doctor's or pharmacist's
instructions. Please do not store other people's identifiable patient records in your notebooks.

---

## 7. Children's Privacy

Med Folio is meant for a general audience, students and adults. It is not directed at children
under 13, and we do not knowingly collect personal information from children.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy when the App changes or when the law requires it. Changes are
posted on this page with a new "Last Updated" date.

---

## 9. Contact Us

- **Developer:** Effitron
- **Email:** effitron.official@outlook.com
- **Privacy Policy page:** https://github.com/RissamAsghar/Privacy-Policy
