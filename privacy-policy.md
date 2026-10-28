---
title: Hydrorep — Privacy Policy
permalink: /privacy-policy
---

<!--
  Approved by the owners for publishing on 2026-10-27. A lawyer's review (KVKK and GDPR:
  training, body and sleep data as health-related data, explicit consent, transfers abroad) is
  still to come; the "Lawyer review" notes below are its checklist. Keep it in sync with the
  app: section 4's shared fields and the in-app sharing consent say the same, section 6 matches
  the coach's consent (m.coach.consent, COACH_CONSENT_VERSION) and section 2 the Health Connect
  permissions in the manifest. Health Connect's "why" links open this page.
-->

# Privacy Policy

**Effective date:** 2026-10-28

Hydrorep ("the app") is provided by **Noronaru** ("we", "us"). Noronaru is the data controller for the personal data described in this policy. You can reach us at **noronaru@proton.me**.

## In short

- Your training log — workouts, sets, programs, body weight, measurements, photos and profile — is stored **on your phone**. It leaves your phone only for features you turn on: cloud backup, sharing with your other apps, Health Connect and the AI coach.
- Signing in with Google is **optional**. You need it for cloud backup, for connecting Hydrorep with our InnerWeather and Dozelight apps, and for Plus.
- **The AI coach and the AI-written program are optional.** When you ask for one, what it needs is sent to **Anthropic**, the maker of Claude, in the United States. We do not keep it.
- There are **no ads, no analytics and no tracking**, and we do not sell your data.
- Hydrorep is **not a medical service**.

## 1. Information on your phone

The following is stored in the app's storage on your phone:

- Your profile: age, sex, height, weight, activity level and fitness goal, which the app uses to estimate calories burned
- Your programs, exercises, exercise notes, weekly schedule and training blocks
- Your workouts: exercises, sets, weights, reps, times, distances, difficulty ratings and notes, and your personal records
- Your body weight log, body measurements and progress photos
- Your water log
- The AI coach's reviews you received
- Reminder times, your language and other app preferences

We have no access to this information unless you turn on one of the features below that sends it. Uninstalling the app, clearing its data, or **Settings → Data → Reset all data** deletes it from your phone.

**Android's own backup.** If backup is on for your phone, Android may include Hydrorep's data in your phone's backup to your Google account, a Google service under your own account. Progress photos are always left out of it; a phone-to-phone transfer that you start yourself moves them straight to your new phone.

**Files you create.** When you export a backup or a CSV of your workouts, or share a workout, record or week as a picture, the app creates a file and opens your phone's share menu. Where it goes is your choice, and that service's own privacy terms apply to it. Importing a file from Strong or Hevy reads it on your phone.

**Your other apps.** To show our other apps in its app bar, Hydrorep asks Android whether InnerWeather and Dozelight are installed on your phone. The answer stays on your phone.

## 2. Health Connect (optional)

If you turn on Health Connect in **Settings → Health Connect** and give permission, Hydrorep:

- **writes** each workout you finish from then on as an exercise session — its name, note, start and end time, the kind of workout, the estimated calories burned and, for cardio, the distance — and deletes it there when you delete the workout in Hydrorep;
- **reads** your body weight measurements, to add them to your body weight log.

Hydrorep asks for exactly these permissions: write exercise sessions, active calories burned and distance, and read weight. The data stays between Health Connect and the app on your phone. Hydrorep's use of information received from Health Connect adheres to the [Health Connect Permissions policy](https://support.google.com/googleplay/android-developer/answer/12991134), including its Limited Use requirements. Health Connect data is never sold, never used for advertising, and never used for anything other than the features described here. You can turn it off in the app or take back the permissions in Health Connect at any time.

## 3. Your account and cloud backup (optional)

**Signing in with Google.** Sign-in is handled by Firebase Authentication, a Google service. When you sign in, it receives your Google account's email address, name and a unique account identifier. To protect sign-in from abuse, it also processes your IP address and information about your phone. We use this only to identify your account, for cloud backup, to connect Hydrorep with our other apps and for Plus. Signing in to them with the same Google account gives you **one account for all three**, so deleting it in any of them deletes it for all (section 13).

**Cloud backup.** If you turn on cloud backup in **Settings → Data**, a copy of your training log — your profile and settings, programs and schedule, workouts, body weight, measurements, exercise notes, records, custom exercises, training blocks and water — is kept in your account in **Google Cloud Firestore (Firebase), in the European Union**, and updated as you train. Progress photos and the AI coach's reviews are never backed up. You can restore the backup on a new phone. Turning backup off, or signing out, stops it and keeps the copy in your account; deleting your account deletes it, or write to us and we will delete only the backup.

<!-- Lawyer review: the backup switch has a hint naming what is kept and where, but no separate
     consent dialog - confirm that is enough for health-related data under KVKK and GDPR art. 9. -->

## 4. Sharing with your other apps (optional)

InnerWeather is our mood journal, with its own [privacy policy](https://noronaru.github.io/innerweather-legal/privacy-policy), and Dozelight is our sleep app, with its own [privacy policy](https://noronaru.github.io/dozelight-legal/privacy-policy). If you use them with the same Google account, you can see your workouts next to your mood and your sleep.

**What Hydrorep shares, and only after you agree.** Nothing is shared until you turn on **Share with my other apps** in **Settings → Account** and confirm it. From then on, for each day you train, Hydrorep stores:

- the date
- the number of workouts
- the total training time
- the total volume lifted
- the estimated calories burned
- the average difficulty you rated your sets
- the time your last workout of the day finished

With **Share water too**, a separate switch under it with its own consent, it also stores each day's water total and goal.

This summary is stored in Google Cloud Firestore, in the European Union, under your account. Security rules allow only your signed-in account to read or change it, and our InnerWeather and Dozelight apps read it when you are signed in there with the same account. InnerWeather's AI insights can include the training part, if you turn that on in InnerWeather. **Not shared:** your individual exercises and sets, your notes, your body weight, measurements, photos and your profile.

**Stopping.** You can turn sharing off or sign out at any time in **Settings → Account**. Hydrorep then stops sending summaries and deletes the ones it shared from your account. Turning sharing off needs a connection and stays on when it fails; signing out without a connection leaves them there until you delete your account (section 13). When what sharing covers changes, it pauses until you agree to the new terms.

**What Hydrorep reads.** When you are signed in, Hydrorep reads what you chose to share from our other apps:

- InnerWeather's **daily mood score** (the number only). Hydrorep shows it on a past workout's page and in **Training & mood**, and with Plus takes it into account in today's readiness and training block advice.
- Dozelight's **nights**: how well and how long you slept, your bed and wake times and the night's tags. Hydrorep shows them on a past workout's page and in **Sleep & training**, and with Plus takes them into account in today's readiness.

Hydrorep reads them from your account when it needs them and does not store them, apart from the offline copy the app keeps on your phone. Both can go to the AI coach only as described in section 6.

Because training, mood and sleep data can be considered health-related data, we share and use them only with your explicit consent, which you give when you turn sharing on — in Hydrorep for your training, in InnerWeather and Dozelight for theirs — and can withdraw at any time.

<!-- Lawyer review: confirm the in-app sharing consents satisfy KVKK explicit consent
     requirements for health-related data and for transferring it abroad. -->

## 5. App security

When Hydrorep talks to our server (sections 6 and 13), **Firebase App Check with Google Play Integrity** (Google) checks that the request comes from the genuine app on a genuine device. Requests to our server are encrypted in transit (HTTPS) and carry your account's identifier.

## 6. The AI coach and the AI-written program (optional)

Both come with Plus and need Google sign-in.

**The AI coach.** When you ask for a week's review, Hydrorep sends that week's workouts to our server: exercise names, sets, weights, reps, times, distances and difficulty, your plan, records, training block week and goal — and, if you share them from your other apps, the week's mood scores from InnerWeather and nights from Dozelight (how long and how well you slept, bed and wake times and the night's tags). Never your body weight, age, sex, notes, measurements, photos or name. Hydrorep asks for your agreement before the first review, and again whenever what is sent changes; you can turn the coach off in **Settings → Workout**.

**The AI-written program.** When you ask for one, Hydrorep sends your answers — goal, level, training days, minutes per workout, equipment and focus muscles — and the list of built-in exercises it may use. Nothing of your workouts.

**How it is processed.** The data travels encrypted to our server, which runs on Google Cloud in the United States and forwards it to **Anthropic** in the United States, whose Claude models write the review or program. Our server asks RevenueCat whether your account has Plus (section 7). We do not store the data you send or the result on our servers; the review is kept on your phone. According to Anthropic's published commercial terms at the time of writing, data sent through its API is not used to train its models by default and may be retained for a limited period, among other things for abuse monitoring.

**Usage limits.** To prevent abuse and keep costs in check, our database (Google Cloud Firestore, United States) stores your account's identifier with how many reviews and programs you asked for each day, week and month. Daily counts are deleted after 2 days, weekly and monthly ones after 60 days. These records contain no training data.

**Reporting.** If you report a review or a program as harmful, wrong or inappropriate, we store its text, your account's identifier and the time of the report, only to review it. Reports are **deleted automatically after 90 days**.

<!-- Lawyer review: confirm the coach's consent dialog satisfies KVKK and GDPR explicit consent
     for health-related data (and InnerWeather's mood and Dozelight's sleep in it) and for
     transferring it to the United States. -->

## 7. Plus

Plus is one subscription for Hydrorep, InnerWeather and Dozelight, sold through **Google Play**, which handles payment; we never see your payment details. It belongs to your Google account, so buying it needs Google sign-in.

To check and restore Plus in all three apps, the apps and our server use **RevenueCat** (United States). RevenueCat receives your account's identifier, your purchases and subscription status from Google Play (such as the product, price and dates), and basic information about your phone and the app, such as the Android version, app version, country and IP address. Learn more in [RevenueCat's privacy policy](https://www.revenuecat.com/privacy).

## 8. No ads

Hydrorep shows no ads and contains no advertising SDK; it does not use your phone's advertising ID.

## 9. Reminders, the widget and notifications

Workout reminders, rest alerts and the weekly recap are scheduled on your phone, and the home-screen widget is drawn from the app's data on your phone. We do not operate a notification server.

## 10. What we do not do

Hydrorep contains no analytics, does not track you across other apps or websites, and we do not sell your personal data.

## 11. Children

Hydrorep is not directed at children under 13, and we do not knowingly collect personal data from them. If you are under 18, please use the app only with permission from a parent or guardian.

## 12. Where your data is processed

- **European Union:** cloud backup, the summaries you share and what you read from our other apps (Google Cloud Firestore).
- **United States:** Google sign-in and App Check (Firebase), our server and its usage records (Google Cloud), the AI coach and program (Anthropic) and purchases (RevenueCat).

If you live in Türkiye, the European Union or another country, this means some of your data is transferred abroad. We rely on the safeguards the law requires for these transfers.

<!-- Lawyer review: name the transfer mechanism for each provider - KVKK art. 9 as amended in
     2024 and GDPR chapter V - and whether the EU storage needs one, given Firebase is a US
     company. -->

## 13. Legal bases and your rights

<!-- Lawyer review: confirm each basis under both KVKK (arts. 5 and 6) and GDPR (arts. 6 and 9). -->

**Legal bases.** We rely on **your explicit consent** for sharing with your other apps, the AI coach and Health Connect; on **your consent** for cloud backup; on **providing the service you ask for** (our contract with you) for Google sign-in, the AI-written program, Plus and deleting your account; and on **our legitimate interests** in keeping the service secure and preventing abuse (App Check, usage limits and reviewing reports).

**Your rights.** Depending on where you live — including under the Turkish Personal Data Protection Law (KVKK) and the EU General Data Protection Regulation (GDPR) — you may have the right to access, correct or delete your personal data, to receive a copy in a portable format, to object to or restrict its processing, and to withdraw consent at any time.

- **Data on your phone:** you can edit or delete entries in the app, export it, use **Settings → Data → Reset all data**, or uninstall the app.
- **Your account and cloud data:** in Hydrorep, go to **Settings → Account → Delete account**. This deletes your sign-in account, your cloud backup and every shared summary right away, and asks our server to delete what it keeps on your account (your subscription record at RevenueCat, usage counts and reports). Because Hydrorep, InnerWeather and Dozelight share one account, it also deletes what those apps keep in your account, such as InnerWeather's cloud backup of your journal and the nights Dozelight shares. It does not cancel a subscription in Google Play. Your workouts stay on your phone.
- **Without the app:** email **noronaru@proton.me** from the address of your Google account and ask us to delete your account. We will delete your sign-in account, everything stored under it and any related purchase record held by RevenueCat within 30 days. Purchases themselves stay on record with Google Play under its own terms. Step-by-step instructions: [Delete your account](./delete-account).

For any other request or question, write to **noronaru@proton.me**. We will answer within 30 days. You also have the right to lodge a complaint with a data protection authority — in Türkiye, the Personal Data Protection Authority (KVKK); in the EU, the authority where you live or work.

## 14. How long we keep data

- **On your phone:** until you delete it.
- **Cloud backup and shared summaries:** until you delete them as described in sections 3 and 4, or delete your account.
- **Your Google account:** until you delete your account.
- **Usage counts:** daily ones 2 days, weekly and monthly ones 60 days. **Reports:** 90 days.

## 15. Security

Data sent from the app is encrypted in transit (HTTPS). Access to our server and database is restricted by security rules and to our own administrative accounts.

## 16. Not a medical service

Hydrorep does not provide medical advice. Calorie figures are estimates, not measurements, and the AI coach's advice is written automatically and can be wrong. Talk to a doctor before starting a new training program, especially if you have a health condition or an injury.

## 17. Changes to this policy

When we update this policy, we change the effective date above. If a change affects how your data is used, the app will let you know.

## 18. Contact

Noronaru — **noronaru@proton.me**
