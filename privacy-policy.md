# Privacy Policy for BreakRot

**Last Updated:** February 21, 2026

## Introduction
BreakRot ("we," "our," or "us") is a digital wellness application designed to help you manage screen time, block distracting apps, and build healthier usage habits. This Privacy Policy explains how we collect, use, store, and share information when you use the app.

## Information We Collect

### 1) App Usage Data (Usage Access)
We access Android Usage Stats to provide core features such as screen time summaries, monitored apps, daily limits, and break reminders. This includes:
- App names and package identifiers
- Time spent in each app
- App launch times and usage timestamps

**Important:** Usage data is processed and stored **locally on your device**. We do not upload raw usage stats to our servers.

### 2) Installed Apps List
To let you select monitored apps, the app reads the list of installed applications (package names and labels). This list is used locally for display and selection.

### 3) Account & Profile Data (if you sign in)
If you sign in with Google, we store:
- Display name
- Email address
- User ID

This data is used for authentication and to associate your cloud data with your account.

### 4) App Settings & Preferences (local)
We store your preferences locally on your device, including:
- Monitored apps selection
- Daily limits
- Notification settings and sound selection
- Focus timer settings and history
- Language preference
- Onboarding status

### 5) Cloud Data (Firebase Firestore)
If signed in, we sync limited data to Firebase Firestore for backup and multi‑device access. This may include:
- Monitored apps configuration and limits
- Focus activities (description, duration, timestamp)
- Daily quest templates and streak data
- User goals
- User settings (daily limit, notifications, focus reminders, sound choice)
- Subscription status (if applicable)
- Basic profile data (name/email)

### 6) Ads & Monetization
We use Google Mobile Ads (AdMob) to show interstitial and rewarded ads. AdMob may collect device identifiers (such as the Advertising ID) and ad interaction data according to Google’s policies. Interstitial ads may be shown when navigating between screens (e.g., returning from detail screens or stopping a focus timer) for non‑Pro users. Rewarded ads may unlock features (e.g., filters or music) for the session.

### 7) Help/Support Submissions
If you submit a help/support request, we store the content you provide and basic metadata (timestamp). In current builds, help requests are stored locally.

### 8) Analytics
We do **not** use analytics SDKs in the current build.

## How We Use Your Information
We use your information to:
- Show your screen time and usage summaries
- Enforce monitored app limits, send reminders, and optionally block apps that exceed limits
- Save and display focus sessions and quests
- Provide account features and cloud sync (if signed in)
- Serve ads and unlock ad‑gated features
- Improve stability and user experience

## Data Sharing
We do **not** sell your personal data. We may share data only with:
- **Google/Firebase** for authentication and cloud storage
- **Google Mobile Ads (AdMob)** for ad delivery and measurement

We do not share your raw usage statistics with third parties.

These providers process data under their own policies.

## Permissions We Request
- **Usage Access (PACKAGE_USAGE_STATS):** required for screen time tracking.
- **Notification Permission:** required for reminders and focus alerts.
- **Foreground Service:** required for background monitoring, timers, and app‑blocking overlay.
- **Display Over Other Apps (SYSTEM_ALERT_WINDOW):** required for the Block Apps feature to show a fullscreen overlay when a monitored app exceeds its time limit.
- **Query All Packages:** required to list installed apps for monitoring.
- **Read Media Audio / Storage (Android 13+ / older):** required for custom notification sounds.
- **Receive Boot Completed:** to restart monitoring after device reboot.

## Data Storage & Security
- **Local storage:** Stored in DataStore/SharedPreferences on your device.
- **Cloud storage:** Firestore data is protected by Firebase security rules and only accessible to authenticated users.

## Data Retention
- **Local data:** Kept until you uninstall the app or clear app data.
- **Cloud data:** Kept while your account is active. You can request deletion by contacting us.

## Your Choices
- You can disable notifications and change monitoring preferences anytime.
- You can stop using the app and clear local data via Android settings.
- You can contact us to request deletion of cloud‑stored data.

## Children’s Privacy
BreakRot is not intended for children under 13. We do not knowingly collect personal information from children under 13.

## Changes to This Policy
We may update this policy and will update the “Last Updated” date accordingly.

## Contact Us
Email: [muhamadwildanfaz@gmail.com](mailto:muhamadwildanfaz@gmail.com)

## Consent
By using BreakRot, you consent to this Privacy Policy.