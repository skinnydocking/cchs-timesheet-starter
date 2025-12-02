# CCHS Timesheet Starter

A simple, browser-based tool for Contra Costa Health Services physicians and dentists to quickly fill out their payroll timesheets.

## 🌟 Features

- **No Installation Required** - Just open the HTML file in any modern web browser
- **Works Offline** - All processing happens locally in your browser
- **Saves Your Info** - Employee name, number, and signature are saved locally for future use
- **Built-in Help System** - Click the "?" button anytime for complete instructions
- **First-Time Tutorial** - Welcome guide appears automatically for new users
- **Smart Weekday Detection** - Automatically identifies weekdays (M-F) based on the actual calendar
- **Flexible Shifts** - Each day can have Full Day, Morning, or Afternoon shifts
- **Built-in PDF Template** - No need to upload a blank timesheet every time
- **Easy Day Selection** - Visual calendar with quick-select options
- **Professional Output** - Generates properly formatted, signed PDFs

## 🚀 Getting Started

### Online (Easiest)
1. Visit the [live demo](https://yourusername.github.io/cchs-timesheet-starter/cchs_timesheet_starter.html)
2. Fill in your information
3. Select your days worked
4. Download your completed timesheet!

### Local Use
1. Download `cchs_timesheet_starter.html`
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. Start filling out timesheets!

## 📋 How to Use

### First Time Setup
1. **Welcome Tutorial**: On your first visit, you'll see a friendly welcome guide
   - Shows the 3 main steps to get started
   - Can be skipped if you're already familiar
   - Won't appear again on future visits
2. **Employee Information**: Enter your name and employee number
3. **Signature**: Click to upload an image of your signature
   - Your information will be saved locally and auto-filled next time
   - You can update it anytime using the "Clear Saved Info" button

### Getting Help
- **Click the "?" button** in the bottom-right corner anytime
- Opens a comprehensive guide with:
  - Step-by-step instructions
  - Visual shift color guide
  - Tips and tricks
  - Privacy information

### Creating a Timesheet
1. **Select Pay Period**: Choose the month and year
2. **Select Half**: Choose 1st half (days 1-16) or 2nd half (days 16-31)
3. **Select Days & Shifts**: 
   - Click a day to select it with Full Day shift (8am-5pm, 8 hours)
   - Click again to change to Morning shift (8am-12pm, 4 hours)
   - Click again to change to Afternoon shift (1pm-5pm, 4 hours)
   - Click again to deselect the day
   - Use "Weekdays Full Day" to automatically select Mon-Fri with full shifts
   - Use "Select All Days" to select all 16 days with full shifts
4. **Review Summary**: Check total hours and days worked
5. **Generate**: Click "Generate Filled Timesheet" to create your PDF
6. **Download**: Click the download link to save your timesheet

The PDF will include:
- Your name and employee number
- Your signature
- The current date
- All selected days with appropriate shift times
- Total hours calculated automatically

## 🔒 Privacy & Security

- **100% Local Processing** - All data stays in your browser
- **No Server Uploads** - Your information never leaves your computer
- **No Tracking** - No analytics, cookies, or data collection
- **Open Source** - Full code is available for review

Your employee information and signature are stored using browser localStorage, which means:
- Data is only stored on your device
- Only accessible from the same browser on the same device
- You can clear it anytime using the "Clear Saved Info" button

## 🛠️ Technical Details

- **Pure HTML/JavaScript** - No dependencies or build process required
- **PDF Generation** - Uses [PDF-Lib](https://pdf-lib.js.org/) for PDF manipulation
- **Client-Side Only** - Everything runs in your browser
- **Modern Browsers** - Works in Chrome, Firefox, Safari, and Edge

## 💾 Saved Information

The app saves the following information locally:
- Employee Name (key: `cchs_employee_name`)
- Employee Number (key: `cchs_employee_number`)
- Signature Image (key: `cchs_signature_image`)
- Tutorial Status (key: `cchs_has_visited`)

This information persists between sessions and is automatically filled in when you return.

## 🗑️ Clearing Saved Data

To clear all saved information:
1. Click the "Clear Saved Info" button in the Employee Information section, OR
2. Clear your browser's localStorage for this site

## 📝 License

This project is provided as-is for use by Contra Costa Health Services employees. Feel free to modify and distribute as needed.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## ⚠️ Disclaimer

This is an unofficial tool created to help CCHS employees fill out timesheets more efficiently. It is not officially endorsed by Contra Costa Health Services. Always verify that your timesheet is accurate before submitting it to payroll.

## 📧 Support

For issues or questions, please open an issue on GitHub.

---

Made with ❤️ for CCHS physicians and dentists
