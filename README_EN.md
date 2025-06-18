# Antaria Tracker - Windows Desktop Client

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)
![License](https://img.shields.io/badge/license-Proprietary_/_Freeware-lightgrey)

Antaria Tracker is a professional Windows desktop application designed to create and manage email tracking pixels. It allows businesses and professionals to know when, where, and how their emails are opened, while providing tools for campaign analysis and management.

This application is the heavy client that communicates with a dedicated server (not included in this repository).

---

### Interface Overview

| Login View | Dashboard | Tracker Management |
| :---: | :---: | :---: |
| ![Login](https://i.imgur.com/lTTsY4z.png) | ![Dashboard](https://i.imgur.com/Fs5R9de.png) | ![Trackers](https://i.imgur.com/qipzIBc.png) |

---

### Key Features

* **Analytical Dashboard:** View real-time open statistics, top-performing trackers, and activity over the past 7 days.
* **Campaign Management:** Organize your tracking pixels into distinct campaigns (e.g., "Newsletter", "Prospecting") for targeted analysis.
* **Custom Tracker Creation:** Upload your own pixel image (1x1 transparent) and associate it with a campaign and description.
* **Geographical Tracking:** Identify the country and city of each email open.
* **Log Visualization:** Inspect detailed open events for a given tracker: timestamp, IP address, country, city, and User Agent.
* **Multilingual:** Interface available in French and English.
* **User Management:** An admin panel to create and delete user accounts.
* **Secure:** Communication with the server is secured via JWT authentication tokens.

---

### Download and Installation

This repository does not contain source code but only compiled versions of the application.

1. Go to the **[Releases](https://github.com/Kertie2/Antaria-Tracker-Client/releases)** section of this repository.
2. Download the `.zip` file of the latest release.
3. Extract the file anywhere on your computer.
4. Run `AntariaTracker.exe`.

**Prerequisites:** The application requires the [Antaria Tracker server](https://github.com/Kertie2/Antaria-Tracker-Server/) to be running and accessible from your machine or from an internet-accessible server. The server URL can be configured on the login screen.

---

### Contribution

The source code is not open for public contributions.  
However, you can report bugs or make suggestions via the [Issues](https://github.com/Kertie2/Antaria-Tracker-Client/issues) section.

---

### License

This software is distributed under a proprietary "Freeware" license. Please refer to the `LICENSE_EN.md` file for more details.
