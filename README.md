# Technical Installer Calculator (SecPro Demo)

<!-- LIVE DEMO BADGE -->
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://jakubkriska.github.io/Technical-Installer-Calculator/)

[**👉 Click here to open the Tool**](https://jakubkriska.github.io/Technical-Installer-Calculator/)

This repository contains a browser-based tool developed as a **Portfolio Project** for the position of *Teknisk Supporter & Produktansvarlig*.

It demonstrates the ability to translate technical product data (Milesight CCTV bitrates & Ajax power requirements) into practical support tools for installers.

## 📸 Preview

![App Screenshot](screenshot.png)
*(Note: Upload a screenshot of the app named 'screenshot.png' to your repository to see it here)*

## 🎯 Purpose

In a technical support role, questions about storage requirements ("How big a hard drive do I need?") and battery backup times ("Will the router survive a power cut?") are common.

This tool allows for instant, accurate answers based on:

* **H.265 Compression Standards** (for Milesight NVRs).
* **12V DC Power Consumption** (for Router/NVR battery backups).

## 🛠 Features

### 1. CCTV Bandwidth & Storage Calculator
*Designed for Milesight Surveillance Solutions.*
* **Inputs:** Number of cameras, Resolution (2MP - 12MP), Retention period (Days).
* **Outputs:**
  * **Network Load (Mbps):** Helps assess if the switch/network can handle the traffic.
  * **Storage (TB):** Estimates the required HDD capacity for the NVR.

### 2. UPS & Battery Backup Calculator
*Designed for Ajax Systems & Infrastructure.*
* **Context:** While the Ajax Hub has an internal battery (15h), the **Router** and **NVR** do not. This tool calculates runtime for external UPS solutions.
* **Inputs:** Power consumption (Watts), Battery capacity (Amp-hours @ 12V).
* **Outputs:** Estimated runtime in hours/days.

## 🚀 Usage

You can access the tool directly via the "Live Demo" link above.

Alternatively, to run it locally:
1. Clone the repository or download the `index.html` file.
2. Double-click `index.html` to open it in any web browser.

## 💻 Tech Stack

* **HTML5 & JavaScript:** Core logic and structure.
* **Tailwind CSS:** For a responsive, clean, and professional UI.
* **FontAwesome:** For intuitive iconography.

---
*Created by Jakub Kriska*
