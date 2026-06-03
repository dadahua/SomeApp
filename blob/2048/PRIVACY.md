# Privacy Policy

**WatchGameHub – Offline Mini Game**  
*Last updated: June 3, 2026*

---

## 1. Overview

WatchGameHub ("we", "our", or "the App") is an Apple Watch game collection developed by an independent developer. We take your privacy seriously. This policy explains what information we collect, how we use it, and your rights.

---

## 2. Information We Collect

### 2.1 Information Stored Locally on Your Device

We store the following data **only on your device** using Apple's `UserDefaults` and Keychain APIs:

| Data | Purpose |
|---|---|
| Game high scores and best records | Display personal bests in-game |
| Game progress and level completion | Resume where you left off |
| In-app purchase trial usage count | Enforce free trial limits (stored in Keychain) |
| App settings and preferences | Remember your personalization choices |

This data never leaves your device except through your own iCloud/iTunes backup, which is controlled entirely by you.

### 2.2 Anonymous Usage Analytics (CloudKit)

When you open a game, we record a minimal anonymous event to Apple's CloudKit public database containing:

- **Game ID** – which game was opened (e.g., "tetris", "chess")
- **Timestamp** – when the game was opened
- **Watch model** – your Apple Watch model name (e.g., "Apple Watch")

**This data is:**
- Not linked to your Apple ID, name, email, or any personal identifier
- Not shared with any third-party analytics services
- Used solely to understand which games are most popular so we can prioritize updates
- Stored in Apple's CloudKit infrastructure and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)

### 2.3 In-App Purchases

Subscription and one-time purchase transactions are handled entirely by Apple's App Store. We do not see or store your payment information. Purchase status is verified locally using Apple's StoreKit 2 framework via `Transaction.currentEntitlements`.

---

## 3. Information We Do NOT Collect

We do **not** collect:

- Your name, email address, or any contact information
- Your location or GPS data
- Photos, camera, or microphone access
- Health or fitness data
- Device advertising identifier (IDFA)
- Browsing history or behavior outside this app
- Any information from users under 13 years of age

---

## 4. How We Use Your Information

| Purpose | Data Used |
|---|---|
| Display personal bests and progress | Local device data only |
| Understand which games are popular | Anonymous CloudKit analytics |
| Verify your subscription status | Apple StoreKit (no data stored by us) |
| Improve app stability and performance | No personal data used |

We do not sell, rent, or trade your data to any third parties.

---

## 5. Data Sharing

We share data with:

- **Apple Inc.** – CloudKit infrastructure for anonymous game open events; App Store for purchase processing. Apple's handling is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

We do not share data with any other third parties.

---

## 6. Data Retention

- **Local device data**: Retained until you delete the app or clear app data.
- **CloudKit analytics events**: Retained for up to 12 months, then automatically deleted.

---

## 7. Children's Privacy

This app is rated 4+ on the App Store. The App does not knowingly collect any personal information from children under 13. The anonymous analytics we collect contain no personal identifiers and cannot be used to identify any individual, including children.

---

## 8. Your Rights

Depending on your location, you may have rights including:

- **Access**: Request information about data we hold about you. (Note: our anonymous analytics cannot be linked to an individual.)
- **Deletion**: Delete app data by uninstalling the app.
- **Opt-out**: You may disable iCloud sync in your device Settings to prevent CloudKit analytics from being uploaded.

---

## 9. Security

- All local data is stored using Apple's standard iOS/watchOS security model
- CloudKit communications use TLS encryption
- We do not operate any servers outside of Apple's infrastructure

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 11. Contact Us

If you have questions about this Privacy Policy, please contact us:

- **Email**: apprenticedahua@gmail.com  
- **GitHub**: [https://github.com/dadahua/SomeApp](https://github.com/dadahua/SomeApp)

---

*This Privacy Policy applies to the WatchGameHub app available on the Apple App Store for Apple Watch and iPhone.*
