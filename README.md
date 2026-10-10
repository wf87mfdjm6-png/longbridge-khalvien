# Longbridge—Khalvien

A static account-registration and progress tracker designed for GitHub Pages.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `longbridge-khalvien`).
2. Upload `index.html` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the published URL shown in the Pages settings.

## Features
- Name and Telegram username fields
- Email and UID fields
- Registration status and progress
- Search and filter
- CSV export (opens in Excel or Google Sheets)
- JSON backup and CSV import
- Browser-based automatic saving

## Important limitations
This is a **static demo**. Records are stored in `localStorage` in the current browser on the current device. They are not automatically shared with an admin or other users and can be lost if browser data is cleared. CSV export creates a spreadsheet-compatible file; it does not write directly to an Excel workbook in the cloud.

For secure multi-user access, centralized progress tracking, or records shared between devices, connect a backend/database and add authentication with proper access rules. Do not put secret API keys or admin passwords in a public GitHub repository.

Collect only information users knowingly provide and that you are authorized to store. This page does not covertly collect physical addresses, IP addresses, or precise location.
