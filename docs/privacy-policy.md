# QRScannerPro - Privacy Policy

**Effective Date**: June 9, 2026  
**Last Updated**: June 9, 2026  
**Version**: 1.3.0

## 1. Overview

QRScannerPro ("App", "we", "us", "our") is committed to protecting your privacy. This Privacy Policy explains our practices regarding data collection, usage, and your rights as a user of the QRScannerPro Android application.

The App is designed with privacy as a core principle. We collect minimal data necessary to provide core functionality and comply with platform requirements.

---

## 2. Data Collection & Usage

### 2.1 Data We Collect

#### A. Scan History (Local Storage)
- **QR/Barcode Content**: Text, URLs, and decoded barcode data
- **Scan Metadata**: Timestamp, scan format type, scan result
- **Storage**: Stored locally on your device using Room Database with SQLCipher encryption
- **Purpose**: Allow you to view, search, and organize your scan history
- **User Control**: You can delete scan history anytime from the app settings; delete individual scans or clear all history

#### B. App Preferences & Settings
- **Language Preference**: Your selected app language
- **Theme Preference**: Your UI theme selection
- **Feature Settings**: Your app configuration choices (batch mode, notifications, etc.)
- **Storage**: DataStore Preferences with encryption
- **Purpose**: Personalize your app experience
- **User Control**: Modify settings anytime in app preferences

#### C. Biometric Data (Pro Features)
- **Biometric Lock**: Fingerprint/Face Recognition for app security
- **Storage**: Never leaves your device; processed by Android's BiometricPrompt API
- **Purpose**: Secure app access with Pro features
- **User Control**: Optional feature - enable/disable in app settings

#### D. Device Information
- **Device Model**: Android device name and model
- **OS Version**: Android version number
- **API Level**: For crash reporting and compatibility
- **Purpose**: Improve app compatibility and performance
- **Sharing**: Only shared with Google services when errors occur

### 2.2 Data We Don't Collect
- ❌ **Personal Identification**: No names, emails, phone numbers collected
- ❌ **Location Data**: No GPS or location tracking (except approximate country for consent purposes)
- ❌ **Contact Lists**: No access to contacts or call logs
- ❌ **App Usage Analytics**: No user behavior tracking (only aggregate metrics via Google Analytics)
- ❌ **Browsing History**: No tracking of websites you visit after scanning
- ❌ **Profile Information**: No profile creation or login required
- ❌ **Credential Storage**: No passwords or sensitive authentication data stored

---

## 3. Third-Party Integrations & Data Sharing

### 3.1 Google Safe Browsing API
**Purpose**: Detect malware and phishing URLs when scanning QR codes

**Data Shared**:
- URL content from scanned QR codes (only URLs, not user identity)
- Device information for error reporting

**Privacy**:
- HTTPS encrypted transmission
- Google operates with privacy-first principles
- No personal data associated with URL checks
- API key stored in local.properties and never exposed

**Opt-Out**: 
- Users can disable scanning of URLs in app settings
- Safe Browsing check only runs when URL is detected

**Google Privacy**: See [Google Privacy Policy](https://policies.google.com/privacy)

### 3.2 Google Mobile Ads (Free Version)
**Purpose**: Display non-intrusive advertisements to free version users for app monetization

**Data Shared** (v23.6.0):
- **Advertising ID**: Anonymized identifier for ad targeting (can be reset in device settings)
- **General Location**: Approximate country/region (from IP address)
- **Ad Interaction Data**: Which ads are clicked/viewed
- **User Consent Status**: Whether user has opted into personalized ads

**User Consent**:
- UMP consent flow shows detailed information on first app launch
- Users can manage ad preferences in Google settings
- Users can opt-out or limit ad personalization
- Consent preferences stored locally and can be withdrawn

**Removed in Pro Version**: No ads shown to Pro version subscribers (one-time purchase)

**Ad Quality**: 
- Ads comply with Google Play Store policies
- Non-intrusive placement (minimal disruption to app experience)
- Easy dismiss option for interstitial ads

**Google Ads Privacy**: See [Google Ads Privacy & Safety](https://policies.google.com/technologies/ads)

### 3.3 Google User Messaging Platform (UMP) - NEW in v1.3.0
**Purpose**: Manage GDPR/CCPA compliance for users in regulated regions

**Data Shared**:
- **Consent Status**: Whether user has consented to personalized ads or analytics
- **Geographic Location**: Approximate country to determine if consent is required
- **Timestamp**: When consent was given/withdrawn

**User Control**:
- Transparent consent prompts with easy-to-understand options
- Option to opt out or limit data usage
- Can withdraw consent anytime via app settings
- Re-consent flow if policies change

**Consent Storage**:
- Stored locally on device via DataStore
- No transmission of consent data to external servers
- User has full control over preferences

**Privacy Protection**:
- Consent management performed locally-first
- No personal data used for targeting without consent
- Compliant with GDPR Articles 6-7 and CCPA requirements

**UMP Privacy**: See [Google UMP Documentation](https://developers.google.com/admob/ump/android)

### 3.4 Google Play Billing (Pro Features)
**Purpose**: Process in-app purchases for Pro membership (one-time purchase model)

**Data Shared**:
- **Purchase Information**: Minimal transaction data for billing
- **Google Play Account**: Associated with user's Google Play Store account
- **No Payment Details**: App never handles credit card information

**Security**:
- Google Play Billing Client handles all sensitive data
- Encrypted communication with Google Play Services
- Compliant with PCI DSS standards
- No payment data stored locally

**User Control**: 
- Manage subscriptions/purchases through Google Play Store app
- View purchase history and receipts
- Request refunds via Google Play Store (within policy window)

**Privacy**: Only your Google Play account association is stored

**Google Play Privacy**: See [Google Play Privacy Policy](https://policies.google.com/privacy)

---

## 4. GDPR & Data Subject Rights

### 4.1 If You're in the EU/EEA
You have the following rights under GDPR Articles 15-22:

#### Right to Access (Article 15)
- You can request what personal data we hold about you
- Local data only: All your data is stored on your device
- **How to exercise**: Use Settings → Data → Export to CSV/JSON

#### Right to Deletion (Article 17)
- Delete your scan history anytime via: Settings → Data → Clear History
- Delete app data completely: Settings → Apps → QRScannerPro → Clear Data
- Upon uninstall, all local data is deleted automatically

#### Right to Rectification (Article 16)
- Correct any inaccuracies in your data
- App preferences can be modified anytime in app settings
- Edit scan history entries

#### Right to Restrict Processing (Article 18)
- Disable personalized ads: Settings → Advertising → Manage Ads
- Disable analytics: Settings → Privacy → Analytics
- Opt out of UMP consent: Contact us (see Section 8)

#### Right to Object (Article 21)
- Opt-out of personalized advertising anytime
- Disable biometric features in app settings
- Request to not receive promotional content

#### Right to Data Portability (Article 20)
- Export your scan history as CSV/JSON from app settings
- All data is stored locally in standard formats
- Easy migration to other apps

#### Right to Lodge Complaint
- Contact your local data protection authority
- See list at [EDPB Website](https://edpb.europa.eu/)
- Contact us first so we can address your concern

### 4.2 If You're in California (CCPA)
You have the following rights under CCPA and CalOPPA:

- **Right to Know**: What personal information is collected (see Section 2.1)
- **Right to Delete**: Request deletion of personal data - use app settings to delete locally
- **Right to Opt-Out**: Opt out of "sale" or "sharing" of personal data
- **Right to Non-Discrimination**: Equal service without data sharing requirement
- **Right to Correct**: Correct inaccurate personal information in app settings

**California Residents Note**: We do not sell or share personal information as defined by CCPA. Advertising ID sharing with Google Ads is necessary for free app functionality and complies with CCPA regulations.

**Your Rights**: 
- These rights can be exercised by using in-app settings or contacting us
- No login or account needed to exercise rights

### 4.3 If You're in Other Regions
We comply with applicable privacy laws in your jurisdiction:
- **China (PIPL)**: Minimal data collection; all data stored locally
- **Brazil (LGPD)**: Transparent consent management via UMP
- **South Korea (PIPA)**: Data protection compliance
- **Canada (PIPEDA)**: Privacy practices aligned with Canadian standards

Contact us for specific requests or region-specific guidance.

---

## 5. Data Retention & Deletion

### 5.1 Scan History
- **Default**: Stored indefinitely on your device until deleted
- **Deletion**: You can manually delete individual scans or clear all history anytime
- **Auto-Deletion**: Optional feature to auto-delete scans after X days (configurable)
- **App Uninstall**: All local data deleted automatically when app is uninstalled

### 5.2 App Preferences
- **Duration**: Stored while app is installed
- **Deletion**: Cleared when app data is cleared via device settings
- **Backup**: Android backup may include settings (can be disabled in system settings)

### 5.3 Ad Targeting Data (Google Ads)
- **Duration**: Retained by Google according to their policies (typically 13 months)
- **Deletion**: Request at [Google Account Settings](https://myaccount.google.com)
- **Reset Advertising ID**: Change at Settings → Google Ads Settings

### 5.4 UMP Consent Data
- **Duration**: Until user withdraws consent or data expires
- **Deletion**: Clear via app settings or Google UMP interface
- **Re-consent**: Consent can be re-given anytime

### 5.5 Google Safe Browsing Cache
- **Duration**: Temporary cache of URL checks (not stored long-term)
- **Google's Retention**: Google retains according to their policy
- **Your Data**: No personal data retained with URL checks

---

## 6. Data Security

### 6.1 Local Data Protection
- **Encryption**: Room Database uses SQLCipher for AES-256 encryption
- **Secure Storage**: DataStore uses encrypted SharedPreferences
- **Biometric Lock**: Optional biometric protection for app access (fingerprint/face)
- **ProGuard**: Code obfuscation prevents reverse engineering

### 6.2 API Communication
- **HTTPS**: All external API calls use HTTPS encryption (TLS 1.2+)
- **Certificate Pinning**: Implemented for production releases
- **No Sensitive Data**: Personal data not sent to external services
- **API Key Security**: Safe Browsing API key never exposed in client code

### 6.3 Code Security
- **ProGuard**: Code obfuscation in release builds
- **Resource Shrinking**: Minimal attack surface
- **Regular Updates**: Security patches applied promptly
- **Dependency Management**: Monitored for known vulnerabilities

### 6.4 Device Security
- **Android Security**: Compliant with Android security best practices
- **Permission Model**: Minimal permissions requested
- **Runtime Permissions**: Requests permissions only when needed
- **Sandbox**: Runs within Android's security sandbox

### 6.5 Limitations
While we implement industry-standard security measures, no system is 100% secure. Users are responsible for:
- Keeping their Android device updated and patched
- Using strong device PIN/password
- Not installing from unofficial sources
- Maintaining physical device security
- Clearing app data if concerned about privacy

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect:
- Changes in our data practices
- Updates to comply with new regulations (GDPR, CCPA, etc.)
- App feature updates
- Legal requirements
- Third-party service updates

**Notification**: 
- Material changes will be notified via in-app notification
- Update to Privacy Policy URL on app release
- Users can review changes anytime

**Your Responsibility**: 
- Review this policy periodically for updates
- Continued use after changes constitutes acceptance
- If you disagree, stop using the app and uninstall

---

## 8. Contact & Data Subject Requests

### 8.1 Privacy Inquiries
For questions about this Privacy Policy or our privacy practices:

**Email**: nexeldor@gmail.com  
**GitHub**: [QRScannerPro Issues](https://github.com/panosgdev/QRScannerPro/issues)  
**Response Time**: 14-30 days depending on request complexity

### 8.2 Data Subject Access Requests (DSAR)
GDPR Article 15 & CCPA Section 1798.100 requests:

1. Send written request to: nexeldor@gmail.com
2. Include: App version, approximate usage period, device info
3. Timeline: Response within 30 days (or as required by law)
4. Note: Most data is stored locally on your device - use app export feature first
5. Verification: We may request proof of identity

### 8.3 Deletion Requests
GDPR Article 17 & CCPA Section 1798.105 requests:

1. You can delete all local data via: Settings → Data → Clear All
2. For cloud/server data: Contact nexeldor@gmail.com
3. Note: This app primarily stores data locally
4. Deletion confirmation: Provided within 14 days

### 8.4 Other Requests
- **Opt-Out Requests**: Use in-app settings first (Settings → Privacy)
- **Marketing Opt-Out**: Not applicable (we don't market via email)
- **Complaint Requests**: See Section 14 (Grievance Redressal)

---

## 9. User Rights Summary

### For All Users
- ✅ Delete your scan history anytime
- ✅ Modify app preferences and settings
- ✅ Export data in standard formats (CSV/JSON)
- ✅ Disable optional features (ads, biometrics, notifications)
- ✅ Uninstall and remove all app data
- ✅ Request removal from analytics
- ✅ Update consent preferences

### For EU/EEA Users (GDPR)
- ✅ Right to know what data we hold
- ✅ Right to access your data
- ✅ Right to rectify inaccuracies
- ✅ Right to restrict processing
- ✅ Right to object to processing
- ✅ Right to data portability
- ✅ Right to lodge a complaint with DPA
- ✅ Right to be informed about our practices

### For California Users (CCPA)
- ✅ Right to know personal information collected
- ✅ Right to delete personal information
- ✅ Right to opt-out of data sharing/sale
- ✅ Right to non-discrimination
- ✅ Right to correct inaccurate data
- ✅ Right to limit use of sensitive information

### For All Other Users
- ✅ Same rights as above per local regulations
- ✅ Privacy protection as strong as GDPR/CCPA standards

---

## 10. App Permissions Explained

### Core Permissions
- **CAMERA**: For QR code and barcode scanning. No recordings, transfers, or background access.
- **INTERNET**: For Google Safe Browsing (threat detection), ads delivery, UMP consent, and crash reporting
- **VIBRATE**: For haptic feedback on successful scan completion

### Optional Permissions (Modern Android)
- **Gallery Access**: Using modern photo picker - no explicit permission needed on Android 13+
- **Biometric**: Optional for Pro app lock feature - only for local authentication

### Not Requested (Protected by Android)
- ❌ Phone number or call logs
- ❌ Contacts or SMS
- ❌ Location or GPS (only approximate country for consent)
- ❌ Calendar or reminders
- ❌ Social media accounts
- ❌ Payment methods (handled by Google Play)

---

## 11. Children's Privacy (COPPA)

This app is **not targeted at children under 13** in the United States or equivalent age in other jurisdictions.

**COPPA Compliance**:
- We do not knowingly collect data from children
- If we discover we've collected data from a child, we will delete it immediately
- No third-party analytics collection from children's data
- Parents/guardians: If your child has used this app, contact us for data deletion

**For EU**: Children's data (under 16) requires parental consent in some cases. See GDPR Article 8.

**Recommendation**: Parents should monitor app usage and disable ads if needed for child safety.

---

## 12. California Online Privacy Protection Act (CalOPPA)

QRScannerPro does not track users over time and across different websites/apps for targeted advertising purposes. However, Google Ads may use data for behavioral advertising within the app.

**CalOPPA Compliance**:
- We have a privacy policy (this document)
- We honor "Do Not Track" browser signals where applicable
- We don't sell personal information as defined by CalOPPA
- Advertising ID usage is necessary for free app functionality

**User Control**:
- Users can opt-out of personalized ads via in-app settings
- Google Ads provides opt-out mechanism

---

## 13. International Data Transfers

### For Users Outside the US
If you use QRScannerPro outside the United States:

- **Google Services**: May transfer data internationally per their privacy policies
- **Local Processing**: Your scan data remains on your device in your country
- **Compliance**: We comply with applicable data protection laws in your region

### EU Standard Contractual Clauses
Where required, we rely on:
- Standard Contractual Clauses (SCC) for Google data transfers
- Google's adequacy decisions and mechanisms
- Local data storage preferences when possible
- Encryption to protect data in transit

---

## 14. Grievance Redressal

If you have concerns about our privacy practices:

1. **In-App Report**: Use the feedback feature to report issues
2. **Email**: nexeldor@gmail.com (response within 14 days)
3. **GitHub Issues**: [QRScannerPro/Issues](https://github.com/panosgdev/QRScannerPro/issues)
4. **Data Protection Authority**: File a complaint with your local DPA (EU/EEA)
5. **California Attorney General**: For CCPA violations (ca.gov/cpra)
6. **FTC Complaint**: For US privacy violations (reportfraud.ftc.gov)

**Escalation Process**:
- We acknowledge receipt within 3 business days
- We investigate and respond within 30 days
- We provide remediation options

---

## 15. Acknowledgments

This privacy policy is updated to reflect:
- **v1.3.0 Changes**: Google User Messaging Platform (UMP) integration for GDPR compliance
- **Latest Google Services**: Safe Browsing API, AdMob (v23.6.0), UMP (3.1.0), Google Play Billing (7.1.1)
- **Android Best Practices**: Modern permission handling, scoped storage, encryption standards
- **Regulatory Updates**: GDPR, CCPA, CalOPPA, COPPA, LGPD compliance

---

## 16. Policy Versions

| Version | Date | Changes |
|---------|------|---------|
| 1.3.0 | 2026-06-09 | UMP integration, GDPR/CCPA enhancement, AdMob v23.6.0, Security improvements, Comprehensive data deletion options |
| 1.2.0 | 2026-05-30 | Initial comprehensive privacy policy |

---

## 17. Quick Reference

### If you want to...
- **Delete Your History**: Settings → Data → Clear History
- **Export Your Data**: Settings → Data → Export (CSV/JSON)
- **Manage Ad Preferences**: Settings → Advertising → Manage Ads
- **Disable Biometric Lock**: Settings → Security → App Lock (toggle off)
- **Reset Advertising ID**: Settings → Google → Ads Settings
- **Withdraw Consent**: Settings → Privacy → Consent Preferences
- **View System Logs**: Enable debug logging in Settings → Developer Options
- **Request Your Data**: Email nexeldor@gmail.com with proof of identity
- **Opt-out of Personalized Ads**: Settings → Privacy → Ad Personalization (toggle off)
- **Report Privacy Issue**: Settings → Help & Feedback → Report Issue

---

## 18. Third-Party Links & Services

### External Links
- This app may contain links to external websites
- We are not responsible for external sites' privacy practices
- We recommend reviewing their privacy policies
- Data shared with external sites is governed by their policies

### Integrated Services
- **Google Play Services**: Provides Safe Browsing, Ads, Billing, UMP
- **Google Analytics**: (If enabled) provides app analytics
- **Firebase**: (If enabled) provides crash reporting and analytics

---

## Final Note

Your privacy is important to us. We've designed QRScannerPro to collect minimal data while providing a great user experience. By using this app, you acknowledge that you've read and understood this Privacy Policy.

**If you don't agree with our privacy practices, please do not use the app.**

We welcome feedback and suggestions to improve our privacy practices. Contact us at nexeldor@gmail.com.

---

**For the latest version of this policy, visit**:  
[QRScannerPro Privacy Policy Repository](https://github.com/panosgdev/qrscannerpro-privacy-policy)

**Effective Date**: June 9, 2026  
**Document ID**: QSP-PP-1.3.0-2026-06-09  
**Next Review**: June 9, 2027 (or as required by law changes)
