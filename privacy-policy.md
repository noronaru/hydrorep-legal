---
title: Hydrorep — Privacy Policy
permalink: /privacy-policy
---

<!--
  DRAFT — have a lawyer review this before publishing, especially the KVKK (Turkish Personal
  Data Protection Law) sections on health-related data, explicit consent and transfers abroad.
  Written for the version with optional Google sign-in and sharing a daily workout summary
  with InnerWeather. Keep it in sync with the app: if the shared fields change (for example,
  body weight starts being shared), update section 2 and the in-app consent text together.
-->

# Privacy Policy

**Effective date:** 2026-09-26

Hydrorep ("the app") is provided by **Noronaru** ("we", "us"). Noronaru is the data controller for the personal data described in this policy. You can reach us at **noronaru@proton.me**.

## In short

- Your training log — workouts, sets, weights, body weight and profile — is stored **on your device**. We do not upload it.
- Signing in with Google is **optional**. You only need it to share a daily workout summary with our InnerWeather app.
- If you turn sharing on, only a **daily summary** (for example, how long you trained and the total weight you lifted) is stored in our cloud database in the European Union. Your individual sets, notes, body weight and profile stay on your device.
- There are **no ads, no analytics and no tracking** in Hydrorep, and we do not sell your data.
- Hydrorep is **not a medical service**.

## 1. Information that stays on your device

The following is stored only in the app's storage on your device:

- Your profile: age, sex, height, weight, activity level and fitness goal, which the app uses to estimate calories burned
- Your programs, exercises and weekly schedule
- Your workouts: exercises, sets, weights, reps, difficulty ratings and set notes
- Personal records and your body weight log
- Reminder times and app preferences, such as units and theme

We have no access to this information. Uninstalling the app or clearing its data deletes it from your device.

**Exporting a backup.** When you export a backup, the app creates a file and opens your device's share menu. Where the file goes — a cloud drive, an email, another app — is your choice, and that service's own privacy terms apply to it.

## 2. Optional: Google sign-in and sharing with InnerWeather

InnerWeather is our mood journal app, with its own [privacy policy](https://noronaru.github.io/innerweather-legal/privacy-policy). If you use both apps with the same Google account, Hydrorep can share a summary of your training with InnerWeather, so you can see your workouts next to your mood.

**Signing in with Google.** Sign-in is handled by Firebase Authentication, a Google service. When you sign in, it receives your Google account's email address, name and a unique account identifier. To protect sign-in from abuse, it also processes your IP address and information about your device. We use this only to identify your account and to connect Hydrorep with InnerWeather.

**What is shared, and only after you agree.** Nothing is shared until you turn on sharing in Settings and confirm it. From then on, for each day you train, Hydrorep stores:

- the date
- the number of workouts
- the total training time
- the total volume lifted
- the estimated calories burned
- the average difficulty you rated your sets

This summary is stored in Google Cloud Firestore, in the European Union, under your account. Security rules allow only your signed-in account to read or change it, and our InnerWeather app reads it when you are signed in there with the same account. **Not shared:** your individual exercises and sets, your notes, your body weight and your profile.

**Stopping.** You can turn sharing off or sign out at any time in Settings. Hydrorep then stops sending summaries. Summaries already shared stay in your account until you ask us to delete them (see section 8).

Because training data can be considered health-related data, we share it only with your explicit consent, which you give when you turn sharing on and can withdraw at any time.

<!-- Lawyer review: confirm the in-app sharing consent satisfies KVKK explicit consent
     requirements for health-related data and for transferring it abroad. -->

## 3. Purchases

If Hydrorep offers optional in-app purchases, they are processed by Google Play. We never receive your card or payment details. To confirm which purchases belong to you, we use **RevenueCat**, a service provider that receives your purchase history and an app user identifier.

## 4. Reminders

Workout reminders are scheduled on your device. We do not operate a notification server.

## 5. What we do not do

Hydrorep shows no ads, contains no analytics or advertising SDKs, does not track you across other apps or websites, and we do not sell your personal data.

## 6. Children

Hydrorep is not directed at children under 13, and we do not knowingly collect personal data from them. If you are under 18, please use the app only with permission from a parent or guardian.

## 7. Transfers outside your country

Shared workout summaries are stored in the European Union. Firebase Authentication (Google) and RevenueCat may process data in the **United States** and other countries where they operate. If you live in Türkiye or another country outside these regions, this means your data is transferred abroad when you sign in, share summaries or make a purchase.

## 8. Your rights

Depending on where you live — including under the Turkish Personal Data Protection Law (KVKK) and the EU General Data Protection Regulation (GDPR) — you may have the right to access, correct, or delete your personal data, to object to or restrict its processing, and to withdraw consent.

- **Data on your device:** you can edit or delete entries in the app, or delete everything by uninstalling it.
- **Your account and shared summaries:** email **noronaru@proton.me** from the address of your Google account and ask us to delete your account. We will delete your sign-in account, every shared summary and any related purchase record held by RevenueCat within 30 days. Purchases themselves stay on record with Google Play under its own terms.

For any other request or question, contact **noronaru@proton.me**.

## 9. Security

Data sent from the app is encrypted in transit (HTTPS). Access to our database is restricted by security rules and to our own administrative accounts.

## 10. Not a medical service

Hydrorep does not provide medical advice. Calorie figures are estimates, not measurements. Talk to a doctor before starting a new training program, especially if you have a health condition.

## 11. Changes to this policy

When we update this policy, we change the effective date above. If a change affects how your data is used, the app will let you know.

## 12. Contact

Noronaru — **noronaru@proton.me**
