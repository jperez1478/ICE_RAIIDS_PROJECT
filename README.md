# ICE Raid Alert & Community Support App

## Overview
This project is an iOS application built using SwiftUI, MapKit, and CloudKit to provide real-time ICE raid reports, community events (such as protests), and immigration rights information. The goal is to ensure undocumented individuals and allies have access to critical information in a secure and anonymous way.

## Features
### 1. **ICE Raid Reporting**
- Users can anonymously submit reports of ICE activity using city, state, and zip code.
- Reports are displayed on a **MapView** (MapKit) for others to see.
- Data is stored in **CloudKit's Public Database** to maintain user anonymity.

### 2. **Know Your Rights Section**
- A dedicated tab to display legal rights information sourced from organizations like [ILRC Red Cards](https://www.ilrc.org/red-cards-tarjetas-rojas).
- Links to trusted legal aid services for immigrants.

### 3. **Community Events & Protests**
- Users can view **upcoming protests, rallies, and immigration-related events**.
- An event submission form allows users to add events with:
  - Event Name
  - Description
  - Date & Time
  - Location (City/State/Zip, optionally displayed on a map)
  - Contact Info
  - Optional image uploads
- Data is stored in **CloudKit** for easy retrieval.

### 4. **Real-Time Immigration News**
- Displays immigration-related news from **NewsAPI** or **GNews API**.
- Users can stay updated on ICE activity, legal changes, and advocacy efforts.

### 5. **Security & Privacy**
- **No user logins or accounts** to ensure anonymity.
- No personal data is stored, only reports and events.
- **Opt-out of iCloud Sync** for CloudKit to prevent linking to Apple IDs.
- Minimal logging and no tracking.

## Tech Stack
- **SwiftUI** – Modern UI framework for iOS.
- **MapKit** – Display ICE raid reports and event locations.
- **CloudKit** – Store reports, event data, and user-submitted info anonymously.
- **NewsAPI/GNews API** – Fetch immigration-related news.
- **PHPickerViewController** – Allow users to attach images to event submissions.

## Potential Costs
- **App Store Fee**: $100/year (Apple Developer Program).
- **CloudKit Storage**:
  - Free tier: **5GB storage, 50MB per record**.
  - If usage exceeds limits, consider **Firebase** or **AWS S3** for media uploads.
- **NewsAPI Costs**:
  - Free tier allows **500 requests/day**.
  - GNews API allows **100 requests/day for free**.

## Next Steps
1. **Set Up SwiftUI Project**
   - Create SwiftUI views for home, map, events, and rights tabs.
2. **Implement MapKit for Reporting ICE Raids**
   - Allow users to submit locations.
   - Display reports as map annotations.
3. **Integrate CloudKit for Storing Reports & Events**
   - Store submitted ICE reports in a public database.
   - Implement event submission and display logic.
4. **Add Know Your Rights Section**
   - Fetch legal information and resources.
5. **Fetch News Data**
   - Integrate **NewsAPI/GNews API** for real-time updates.
6. **Test & Optimize**
   - Ensure app performance and security measures are in place.

## Contribution
- Open to developers and organizations advocating for immigrant rights.
- Fork the repo, submit pull requests, and report issues.

## License
MIT License – Open-source for community use and improvement.


