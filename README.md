# Instagram Follower Tracker

A browser-based Instagram follower comparison tool built using HTML, CSS, and JavaScript.

This tool helps users compare follower snapshots to detect:
- Unfollowers
- New followers
- Follower changes over time
  
NOTE: The first file you download will serve as your initial followers list. The next time you want to check for unfollowers or new followers, upload the previously saved file along with the newly downloaded one.

## Features
- Compare follower snapshots
- Detect unfollowers
- Detect new followers
- Drag & drop file upload
- Dark mode support
- Copy & download results
- Privacy-friendly (runs completely in the browser)
- No login required

## How It Works
1. Export follower snapshots from Instagram using the provided browser script
2. Upload or paste two follower lists
3. Compare them instantly

## Getting Started - Step by Step Guide

### Step 1: Click on Followers Button
Open your Instagram profile and click on the **Followers** button to open your followers list.

![Step 1 - Followers Button](./screenshots/step-1-followers-button.png)

### Step 2: Scroll All The Way To The Bottom
Scroll down using the scrollbar on the right side until you reach the very bottom of the list. This ensures all followers are loaded before running the script.

**Important:** Make sure you scroll all the way to the bottom so that all followers are loaded.

![Step 2 - Scroll To Bottom](./screenshots/step-2-scroll-to-bottom.png)

### Step 3: Open Console & Paste Script
1. Open the browser Developer Console (Press `F12` or `Ctrl+Shift+J`)
2. Go to the **Console** tab
3. If Chrome blocks pasting, type `allow pasting` and press Enter
4. Paste the extractor script and press Enter

The script will extract all your followers and automatically download a file.

![Step 3 - Console & Paste Script](./screenshots/step-3-console-paste-script.png)

### Step 4: Rename & Save The File
When the download dialog appears, rename the file to something descriptive (e.g., `initial_followers.txt` or `followers_may_2024.txt`).

This naming convention helps you keep track of different follower snapshots over time without overwriting previous data.

![Step 4 - Rename & Save File](./screenshots/step-4-rename-save-file.png)

---

## Compare Your Followers

Once you have downloaded your follower snapshots:

1. Upload your first follower file
2. Upload your latest follower file
3. The tool will automatically show:
   - **New Followers** ✅
   - **Unfollowers** ❌
   - **Total Changes** 📊

## Technologies Used
- HTML
- CSS
- JavaScript

## Privacy
This project does not collect, store, or send user data.
All processing happens locally in the user's browser.
User isn't required to type any login details in this process.

## Created By
@probably_akhil
