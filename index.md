Privacy Policy for Ascent
Last updated: July 2025

This Privacy Policy describes how Ascent ("we", "us", or "our") handles your information when you use the Ascent iOS application (the "App"). We are committed to being transparent about what data we collect, why we collect it, and how it is used.

1. Summary
Your videos never leave your device. All pose estimation and movement analysis runs entirely on-device using Apple's CoreML framework.
We collect anonymous performance data to improve the accuracy of the analysis engine. This data is not linked to your name, email, or any personal identifier.
We do not sell your data to third parties, ever.
2. What Data We Collect
2.1 Data Stored Locally on Your Device
The following information is saved only on your device and is never transmitted to our servers:

The video files you choose to analyse
Your climb history (scores, dates, thumbnails)
The frame-by-frame pose and score data used for video playback review
2.2 Anonymous Analytics Data Uploaded to Our Servers
After each climb analysis completes, we upload a small analytics record to our servers via Google Firebase Firestore. This record contains no personally identifiable information. Specifically, it includes:

Session Identity

A randomly generated session ID (UUID) for this climb
A short human-readable code (e.g. "ASC-A1B2C3") you can use to report inaccurate results
Device & App Information

App version number
iOS version
Device model identifier (e.g. "iPhone16,2") — hardware model only, not your device name or serial number
An anonymous Firebase UID — a random identifier generated per device installation, not linked to your Apple ID or any personal account
Video Metadata

Frame count, resolution, and frame rate of the analysed video
The fraction of frames where a pose was successfully detected
Climb Performance Metrics

Duration of the climb
The six pillar scores (Power, Control, Stability, Precision, Fluidity, Coordination) and total score
Letter grade
Raw penalty values used for score debugging
Peak power and leg-drive ratio estimates
A list of detected movement mistakes (type, severity, timestamp within the climb)
Wall angle estimate, route path length, and torso calibration status
This data is used exclusively to identify and correct inaccuracies in the scoring engine.

3. What We Do NOT Collect
Your name, email address, or Apple ID
Your location or GPS data
Your contacts or calendar
Video content (videos are analysed on-device and never uploaded)
Any biometric identifiers
4. How We Use This Data
The anonymous analytics data described in Section 2.2 is used solely to:

Identify patterns where the scoring algorithm produces unusual or inaccurate results. Improve the ML models and physics engine in future versions of the app. Understand how different video qualities and device types affect analysis accuracy.

5. Data Sharing
We do not sell, rent, or share your data with third parties for advertising or any commercial purpose.

We use the following third-party service to store and process analytics data:

Google Firebase (Firestore & Authentication) Firebase provides the database infrastructure that stores the anonymous analytics records described in Section 2.2. Firebase Anonymous Authentication is used to generate a stable random identifier for each device installation — no account creation or personal information is required.

Google's Privacy Policy: https://policies.google.com/privacy

6. Data Retention
Anonymous analytics records are retained indefinitely to support ongoing model improvement. Because records contain no personal identifiers, they cannot be attributed to or deleted on behalf of a specific individual.

If you would like a specific session's data removed by its climb code (e.g. "ASC-A1B2C3"), you may contact us at the address below and we will delete the corresponding Firestore document.

7. Children's Privacy
The App is not directed at children under 13. We do not knowingly collect data from children. If you believe a child has submitted data through the App, please contact us and we will delete it promptly.

8. Security
All data transmitted between the App and our servers uses HTTPS (TLS encryption). Firebase Firestore enforces server-side access rules that prevent one device from reading another device's records.

9. Changes to This Policy
We may update this Privacy Policy from time to time. We will post the updated policy at this URL with a revised "Last updated" date. Continued use of the App after a change constitutes acceptance of the updated policy.

10. Contact Us
If you have any questions or requests regarding this Privacy Policy, please contact:

Email: [
brokearis@gmail.com
]

Ascent is an independent app. All video analysis is performed on-device. Your climb videos are yours.
