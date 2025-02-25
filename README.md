# ICE_RAIIDS_PROJECT

# ICE Raid Reporting App (SwiftUI + MapKit + CloudKit)

A SwiftUI iOS app that allows users to report ICE raids in real time and view reported locations on a map. It also provides **"Know Your Rights"** resources and up-to-date immigration-related news.

## 🚀 Features

### 1. **ICE Raid Reporting (MapKit + CloudKit)**
- Users can **report ICE raids** by entering **City, State, and Zip Code**.
- Locations are stored in **CloudKit** and displayed on a **MapKit** interface.
- Uses **CloudKit’s free tier** for storage and syncing.

### 2. **Know Your Rights (Legal Resources)**
- Includes **"Know Your Rights"** materials from **[ILRC Red Cards](https://www.ilrc.org/red-cards-tarjetas-rojas)**.
- Provides **links to immigration lawyers and pro bono legal aid** services.

### 3. **Live News Feed on Immigration & ICE Raids**
- Pulls real-time immigration news using **free news APIs**, such as:
  - [NewsAPI.org](https://newsapi.org/)
  - [GNews](https://gnews.io/)
  - [ContextualWeb](https://rapidapi.com/)
- Alternatively, the app can **scrape and aggregate RSS feeds** from trusted sources.

### 4. **Push Notifications (Optional)**
- Uses **CloudKit Subscriptions** for free push notifications when:
  - A new ICE raid report is submitted.
  - A significant immigration law update is published.

---

## 📂 Tech Stack

| Component        | Technology |
|-----------------|------------|
| UI Framework    | SwiftUI    |
| Mapping        | MapKit     |
| Backend        | CloudKit (Apple's free backend) |
| News API       | NewsAPI.org, GNews, or RSS Feeds |
| Legal Resources | Static JSON or CloudKit Database |
| Notifications  | CloudKit Subscriptions (Free) |

---

## 🛠 Setup Instructions

### 1. **Clone the Repository**
```sh
git clone https://github.com/yourusername/ICE-Raid-Reporting-App.git
cd ICE-Raid-Reporting-App
