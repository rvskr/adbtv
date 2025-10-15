# Privacy Policy for ADB TV

**Last updated: January 15, 2025**

## Introduction

ADB TV ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our Android application handles information when you use ADB TV to manage your Android TV devices.

## Information We Collect

ADB TV is designed to work entirely locally on your device. **We do not collect, store, or transmit any personal information to external servers.**

### Data Stored Locally on Your Device

The app stores the following information locally on your device only:

- **Device Connection Information**: IP addresses and ports of Android TV devices you connect to
- **Connection Settings**: Saved device configurations and connection preferences
- **Device List**: List of your saved Android TV devices
- **Voice Command Preferences**: Your custom voice command settings and app launch preferences
- **App Settings**: Your application preferences (language, theme, etc.)

All this data remains on your device and is never transmitted to us or any third party.

## Permissions Used

The app requests the following Android permissions to function:

### Required Permissions

**INTERNET**
- **Purpose**: Required to establish ADB connections to Android TV devices over your local network
- **Data Access**: Only used to communicate with devices you explicitly connect to
- **No External Servers**: Does not connect to any external servers or services

**ACCESS_NETWORK_STATE**
- **Purpose**: Used to check network availability before attempting device connections
- **Data Access**: Only checks if network is available, does not access network data

**ACCESS_WIFI_STATE**
- **Purpose**: Used to discover Android TV devices on your local WiFi network
- **Data Access**: Only accesses WiFi connection state, not network traffic

**CHANGE_WIFI_MULTICAST_STATE**
- **Purpose**: Used for device discovery on local network
- **Data Access**: Only enables multicast for device discovery

### Optional Permissions

**RECORD_AUDIO** (Optional - only if device has microphone)
- **Purpose**: Used only for voice input feature to control your TV
- **Data Processing**: Audio is processed by Google's system speech recognition service (Android's built-in SpeechRecognizer)
- **No Recording**: Audio is NOT recorded, stored, or transmitted by our app
- **System Service**: All voice processing is handled by Android's system service
- **Can Be Disabled**: Voice features are optional and can be avoided if you don't want to use them

**READ_EXTERNAL_STORAGE / WRITE_EXTERNAL_STORAGE** (Android 12 and below only)
- **Purpose**: Used to select APK files and other files to transfer to your Android TV
- **Data Access**: Only accesses files you explicitly select
- **No Automatic Scanning**: Does not scan or access your files without your action

## How We Use Information

All data stored by ADB TV is used solely for the following purposes:

- **Device Management**: Storing connection information to reconnect to your Android TV devices
- **User Preferences**: Remembering your settings and preferences
- **Voice Commands**: Storing your custom voice command configurations
- **App Functionality**: Enabling the core features of the application

## Data Sharing and Transmission

**We do not share, sell, or transmit any data to third parties.**

- ❌ No data is sent to our servers (we don't have any servers)
- ❌ No data is shared with third-party services
- ❌ No analytics or tracking services are used
- ❌ No advertisements or ad networks
- ✅ All data remains on your device

### Third-Party Services

The only external service used is:

**Google Speech Recognition** (when you use voice features)
- Used only when you explicitly activate voice input
- Handled entirely by Android's system service
- Subject to Google's privacy policy
- Audio is not stored by our app

## Data Security

- **Local Storage**: All data is stored locally on your device using Android's standard secure storage mechanisms
- **No Cloud Sync**: No data is synchronized to cloud services
- **No Account Required**: The app does not require any account or login
- **Device Security**: Data security depends on your device's security (screen lock, encryption, etc.)

## Your Rights and Data Control

You have complete control over your data:

### Delete All Data
You can delete all app data at any time by:
1. Going to Android Settings → Apps → ADB TV → Storage
2. Tap "Clear Data" or "Clear Storage"
3. Or simply uninstall the application

### Manage Permissions
You can revoke any permission at any time through:
- Android Settings → Apps → ADB TV → Permissions

### Export Data
All data is stored in standard Android formats and can be accessed through Android's backup mechanisms.

## Children's Privacy

ADB TV is not directed to children under the age of 13. We do not knowingly collect information from children under 13. The app is designed for technical users managing Android TV devices.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by:
- Posting the new Privacy Policy on this page
- Updating the "Last updated" date at the top
- Notifying users through the app (for significant changes)

We encourage you to review this Privacy Policy periodically for any changes.

## Open Source

ADB TV is open source software. You can review the source code to verify our privacy practices:
- GitHub Repository: https://github.com/rvskr/adbtv

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

- **Email**: rvskr.dev@gmail.com
- **GitHub Issues**: https://github.com/rvskr/adbtv/issues
- **GitHub Profile**: https://github.com/rvskr

## Legal Compliance

This Privacy Policy complies with:
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Google Play Store Data Safety requirements
- Android privacy best practices

## Summary

**In simple terms:**
- ✅ All your data stays on your device
- ✅ No servers, no tracking, no ads
- ✅ You control your data completely
- ✅ Open source - you can verify everything
- ✅ Voice input uses Android's system service only
- ✅ You can delete all data anytime

---

**ADB TV - Your privacy is our priority.**
