# Privacy Policy for GPS Map Camera

**Last Updated:** October 2026  
**Application Name:** GPS Map Camera  
**Package Name:** `com.io.gpsmapcamera`  
**Developer:** Divyesh Murani  
**Contact Email:** [divyeshvmurani@gmail.com](mailto:divyeshvmurani@gmail.com)  
**Developer Profile:** [https://github.com/DivyeshMurani](https://github.com/DivyeshMurani)  

---

## Introduction & Overview

**GPS Map Camera** is committed to protecting your privacy. This policy explains how we collect, use, and safeguard your data in full compliance with **Google Play Developer Policies** and **Google Play Data Safety requirements**.

We believe in complete transparency and a **Privacy-First** architecture: **100% of your captured photos and recorded videos are processed and stored locally on your device.** We do not operate remote photo-storage servers, we do not upload your media to the cloud, and we never sell, rent, or monetize your personal information.

---

## 1. Camera & Audio

* **Camera Permission (`android.permission.CAMERA`):**
  * Used solely to provide a real-time camera viewfinder and capture photos or videos with geotagged and environmental telemetry stamps when explicitly initiated by you.
  * All image rendering, watermark stamping, and media encoding take place **100% locally on your device**.
  * We do not perform facial recognition, biometric analysis, or background recording.
* **Microphone Permission (`android.permission.RECORD_AUDIO`):**
  * The microphone permission is optional and utilized strictly during video recording sessions to record ambient audio along with your video.
  * Audio is never recorded in the background or transmitted to any external server.

---

## 2. Precise Location & Geocoding

* **Foreground Location Permission (`android.permission.ACCESS_FINE_LOCATION`, `android.permission.ACCESS_COARSE_LOCATION`):**
  * High-accuracy GPS location (latitude, longitude, altitude, and compass azimuth/heading) is accessed in the foreground exclusively while actively using the camera viewfinder or the interactive map screen.
  * **Purpose:** This data is used solely to imprint geospatial coordinates and telemetry onto your photos/videos and to fetch physical street addresses via reverse geocoding.
  * **No Background Tracking:** Your location is **NEVER** tracked or monitored in the background.
  * **No Location Sharing:** Location coordinates are never transmitted to external proprietary servers, never stored off-device, and never sold or shared with data brokers, advertisers, or third parties.

---

## 3. Storage & Local Processing

* **Storage Access (`READ_MEDIA_IMAGES`, `READ_MEDIA_VIDEO`, scoped storage):**
  * Allows the app to save stamped photos and videos directly to your device's public `Pictures/GPSMapCamera` directory.
  * Enables displaying your captured media within the in-app gallery.
* **Local Control:**
  * We do not operate remote servers, cloud databases, or external hosting for your media.
  * You retain **100% complete ownership and control** of your photos, videos, and metadata at all times.

---

## 4. Third-Party Services & Telemetry

To ensure high app stability, performance, and reliability, the following trusted third-party SDKs are integrated into GPS Map Camera in compliance with Google Play Developer Policies:

| Service / SDK | Purpose | Privacy Policy |
| :--- | :--- | :--- |
| **Google Play Services** | In-app updates, in-app reviews, and core Android runtime services. | [Google Privacy Policy](https://policies.google.com/privacy) |
| **Microsoft Clarity** | Anonymous user interaction heatmaps and session diagnostics (all PII masked). | [Microsoft Clarity Terms](https://clarity.microsoft.com/terms) |
| **Firebase Analytics & Crashlytics** | Anonymous crash reports, stack traces, and stability metrics to diagnose bugs. | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Google AdMob** | Non-personalized and personalized advertising adhering to AdMob developer policies. | [Google AdMob Privacy](https://support.google.com/admob/answer/6128543) |
| **Open-Meteo Weather API** | Ephemeral GPS coordinates are sent to fetch real-time weather (temperature, humidity, wind, pressure). No device or user identifiers are transmitted. | [Open-Meteo Terms](https://open-meteo.com/en/terms) |

---

## 5. Data Retention & Security

* Because your photos, videos, and telemetry stamps are processed and stored locally on your device, we do not store, retain, or have access to your personal files on any remote server.
* **User-Driven Deletion:** Deleting a photo or video inside the app gallery permanently removes it from your device storage.
* All network communication with third-party service endpoints (such as weather lookups and crash diagnostics) is encrypted using industry-standard **HTTPS / TLS encryption**.

---

## 6. Managing Permissions & User Rights

You have full control over the permissions granted to GPS Map Camera:
* You can grant, deny, or revoke any permission (Camera, Location, Storage, Microphone) at any time through your Android device settings:
  ```
  Settings > Apps > GPS Map Camera > Permissions
  ```
* If you deny location or microphone permissions, core photo capture remains functional, though location-stamping or video audio may be disabled accordingly.
* You have the right to contact us at any time regarding any privacy inquiries, clarifications, or data safety requests.

---

## 7. Children's Privacy

GPS Map Camera is not directed toward children under the age of 13. We do not knowingly collect or solicit personal information from children under 13. If you believe that a child under 13 has provided personal data to us, please contact us immediately so we can take appropriate measures.

---

## 8. Google Play Data Safety Summary

| Data Category | Collected? | Shared? | On-Device Processing Only? | Ephemeral? | Purpose |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Photos & Videos** | No | No | **Yes (100% Local)** | No | User-initiated capture & watermarking |
| **Precise Location** | Foreground only | No | **Yes (100% Local)** | Yes | Imprinting coordinates & address stamping |
| **Audio Recordings** | Optional (video only)| No | **Yes (100% Local)** | No | Video soundtrack |
| **Crash Logs & Diagnostics** | Yes | Yes (Firebase) | No | Yes | App stability & bug fixes |
| **Device / Ad Identifiers** | Yes (AdMob) | Yes (Google) | No | Yes | Advertising & ad fraud prevention |

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect app updates, new features, or changes in legal and regulatory requirements. Any updates will be posted with an updated **"Last Updated"** date at the top of this document. We encourage you to review this policy periodically.

---

## 10. Contact Developer & Support

If you have any questions, suggestions, feedback, or privacy concerns regarding this Privacy Policy or your data, please contact the developer directly:

* **Developer:** Divyesh Murani
* **Email:** [divyeshvmurani@gmail.com](mailto:divyeshvmurani@gmail.com)
* **Email Subject Line:** `GPS Map Camera - Privacy Inquiry`
* **GitHub Profile:** [https://github.com/DivyeshMurani](https://github.com/DivyeshMurani)
