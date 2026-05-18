# Taskist Privacy Policy

_Last updated: 18 May 2026_

This policy describes what Taskist ("the app", "we") collects, how it uses that information, and the choices you have. It applies to the Taskist mobile app on Google Play and the App Store.

## TL;DR

- Your tasks, lists, notes, and habits **stay on your device** unless you choose to sign in for cloud sync.
- Taskist contains **no ads, no analytics, and no third-party tracking pixels**.
- AI features and voice transcription are **opt-in** and use Google services. We send the minimum data needed to make them work.
- Subscriptions are processed by **Google Play** and validated through **RevenueCat**.

## What Taskist stores on your device

When you use Taskist, the following stay locally on your phone in an encrypted-at-rest SQLite database managed by the OS:

- Tasks, lists, notes, subtasks, tags, attachments
- Habits, streaks, and completion history
- Focus / Pomodoro session preferences
- App settings (theme, language, notification preferences, etc.)
- Onboarding state, AI usage counters

You can export this data at any time (Settings → Integrations & Import → Export) or wipe it by uninstalling the app or clearing app storage in Android Settings.

## What we send to third parties — and why

Taskist contacts the internet **only when you opt in** to a feature that needs it.

### Cloud sync (optional, off by default)

If you sign in via Settings → Sign In, Taskist syncs your tasks to **Supabase** servers so you can access them across devices. We store only the task content you create — no contacts, no location, no analytics. You can sign out and delete your cloud data from inside the app at any time.

### AI features (optional, off by default)

If you enable AI features in Settings → AI Assistant, Taskist sends short pieces of text (e.g. a phrase you typed in Quick Add, a list of your overdue tasks for re-scheduling) to the **Google Gemini API**. We send the minimum context needed to fulfil your request and never include credentials, contacts, or unrelated data. Google's terms apply to data sent to Gemini.

### Voice add-task (optional)

When you tap the microphone icon, Android's system speech recognizer captures audio on-device and sends it to **Google's speech-to-text service** for transcription. Taskist does not record, store, or upload raw audio itself — only the text Google returns to us. The microphone permission is requested only when you use this feature.

If you turn on "AI Mode" in the voice screen, the resulting transcript is then sent to Gemini for multi-task extraction (see above). A consent dialog asks for your agreement the first time.

### Subscriptions

In-app subscriptions and the lifetime plan are processed by **Google Play Billing**. Purchase receipts are validated through **RevenueCat**, which gives us your entitlement status (Pro / Free) but no payment details. We never see or store your credit card.

### Calendar integration (optional)

If you enable "Local Calendar Notifications" in Settings → Sounds & Notifications, Taskist will read from and write to your device's local calendar. No calendar data leaves the device.

## What Taskist does NOT do

- We do **not** sell your data.
- We do **not** include advertising or ad SDKs.
- We do **not** track which screens you visit, how long you use the app, or which features you use.
- We do **not** access your contacts, location, photos, or other apps' data.
- We do **not** scan your tasks for keywords, ads, or behavioural targeting.

## Permissions we request and why

| Permission | Used for |
|---|---|
| Internet | Cloud sync, AI features, subscription validation |
| Microphone | Voice add-task (only when you tap the mic) |
| Notifications | Reminders for tasks and habits |
| Calendar | Optional sync of task reminders to your local calendar |
| Exact alarm / Wake | Precise reminder delivery on Android 12+ |
| Foreground service / Overlay | Quick Ball floating shortcut (Tier 3 feature, off by default) |
| Receive boot completed | Re-scheduling reminders after device restart |
| Vibrate | Optional vibration on notification |

## Children

Taskist is a productivity tool for general audiences. It is not directed at children under 13 and we do not knowingly collect data from them.

## Your rights

- **Access**: All your local data is on your device — open the app to view it.
- **Export**: Settings → Integrations & Import.
- **Delete (local)**: Uninstall the app, or clear app data in Android Settings.
- **Delete (cloud)**: If you're signed in for cloud sync, Settings → Sign In → Delete account.
- **Disable AI**: Settings → AI Assistant → toggle off.
- **EU / California residents**: You have additional rights to access, correct, and delete personal data under GDPR / CCPA. Contact us at the email below to exercise them.

## Changes to this policy

If we materially change what we collect or how we use it, we will update this page and bump the "Last updated" date. Continued use after a change means you accept the new policy.

## Contact

Questions, concerns, or data requests:

- Email: **support@taskist.pro**
- App: Settings → Help & Support

If you believe we are not meeting our obligations under this policy, please contact us first — we'll respond within a reasonable time.
