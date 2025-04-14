# YouTube Ad Skipper Chrome Extension

This Chrome Extension automatically skips skippable ads on YouTube, giving you a smoother and uninterrupted video-watching experience.

---

## Features

- Automatically clicks the "Skip Ad" button on YouTube
- Lightweight and fast
- No data collection or tracking
- Simple to install and use
- Works on all YouTube videos

---

## Installation Instructions

1. **Download or Clone the Extension Folder**

   Download the ZIP file or clone the repository to your local system.

2. **Extract the Folder (if ZIP)**

   Unzip the file to any location on your computer.

3. **Open Chrome Extension Settings**

   - Open Google Chrome
   - Go to `chrome://extensions/`
   - Enable **Developer Mode** using the toggle at the top-right corner

4. **Load the Extension**

   - Click **Load unpacked**
   - Select the folder where the extension files are located (this folder should contain the manifest file)

5. **Pin the Extension (Optional)**

   - Click the puzzle icon near the address bar
   - Pin "YouTube Ad Skipper" for easy access

---

## Project Structure

- manifest.json — Describes the extension and its behavior
- content.js — Script that auto-clicks "Skip Ad" button
- background.js — Optional background worker file
- README.md — Documentation

---

## How It Works

The extension observes the YouTube video player using a MutationObserver. When a "Skip Ad" button appears, it simulates a click on that button instantly to skip the ad. It runs automatically whenever a YouTube video page is loaded.

---

## Privacy & Security

- This extension does not collect, store, or transmit any user data
- No third-party analytics or cookies
- It only interacts with YouTube’s frontend to click the "Skip Ad" button

---

## Tested On

- Google Chrome 119+
- YouTube desktop website

---

## Contact

Author: Aarthi E & Akash A  
GitHub: github.com/Grind1503             
Email: aarthielumalaimaha@gmail.com || a.akash030305@gmail.com

---
