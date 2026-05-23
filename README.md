# 📋 Job Application Tracker

A simple, elegant web-based application to track and manage your job applications all in one place. Never lose track of where you applied, what stage you're at, or when to follow up!

## ✨ Features

- **Add & Manage Applications** — Track company name, position, dates, status, and contact information
- **Real-time Statistics** — Dashboard showing total applications, in-progress count, interviews, and pending follow-ups
- **Status Tracking** — Monitor application status (Applied, Screening, Interview, Offer, Rejected, Declined, On Hold)
- **Search & Filter** — Quickly find applications by company name, job title, or contact
- **Tab Views** — Organized views for All, Applied, Interviews, and Offers
- **Visual Analytics** — Doughnut chart showing distribution of applications by status
- **Follow-up Reminders** — Track follow-up dates and see which applications need attention
- **Data Export/Import** — Export to CSV for backup or import data from other sources
- **Auto-Save** — All changes are automatically saved locally to your browser
- **Responsive Design** — Works seamlessly on desktop, tablet, and mobile devices
- **No Login Required** — Privacy-first design with data stored entirely on your device

## 🚀 Getting Started

### Option 1: Online (GitHub Pages)
Simply click the link provided in your repository to access the app online. Your data is saved locally in your browser.

### Option 2: Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-application-tracker.git
   ```
2. Open `job_tracker_app.html` in your web browser
3. Start tracking your applications!

## 📝 How to Use

### Adding a New Application
1. Click the **"+ Add New Application"** button
2. Fill in the application details:
   - Company name & job title (required)
   - Application date (required)
   - Status (required)
   - Expected response date
   - Follow-up date
   - Recruiter/contact information
   - Job description link
   - Salary range & location
   - Work type (Remote/Hybrid/Onsite)
   - Personal notes
3. Click **"Save Application"**

### Searching & Filtering
- Use the **search box** to find applications by company, job title, or contact name
- Click **tabs** to view applications by category (All, Applied, Interviews, Offers)

### Editing & Deleting
- Click **"Edit"** to modify an application
- Click **"Delete"** to remove an application

### Exporting Your Data
- Click **"📥 Export CSV"** to download all applications as a CSV file
- Great for backups or sharing with Excel/spreadsheets

### Importing Data
- Click **"📤 Import CSV"** to bulk import applications from a CSV file
- Useful for migrating from other trackers

## 💾 Data Storage

Your application data is stored **locally in your browser** using the browser's `localStorage` feature:
- ✅ **Private** — Your data never leaves your device
- ✅ **Persistent** — Data is saved automatically and survives browser restarts
- ✅ **No account needed** — No login or sign-up required
- ⚠️ **Browser-specific** — Data is unique to each browser and computer
- ⚠️ **Clearing browser data** — Clearing browser cache/history will delete your data (use CSV export as backup!)

## 🌐 Using on GitHub Pages

To host this app for free on GitHub Pages:

1. Push this repository to GitHub
2. Go to **Settings** → **Pages**
3. Under "Build and deployment":
   - Source: Select "Deploy from a branch"
   - Branch: Select `main` (or your default branch)
4. Click **Save**
5. Your app will be available at: `https://yourusername.github.io/job-application-tracker/job_tracker_app.html`

## 📊 Dashboard Statistics

The app displays real-time statistics:
- **Total Applications** — Total number of job applications tracked
- **In Progress** — Applications in Applied, Screening, or Interview stage
- **Interviews** — Applications where you're actively interviewing
- **Follow-ups Due** — Applications waiting for your follow-up action

## 📈 Status Chart

A visual doughnut chart shows the breakdown of applications by status, helping you see at a glance where most of your applications stand.

## 🛠️ Technologies Used

- **HTML5** — Structure and markup
- **CSS3** — Styling and responsive design
- **Vanilla JavaScript** — Functionality and interactivity
- **Chart.js** — Data visualization
- **localStorage API** — Local data persistence

## 📱 Browser Compatibility

Works on all modern browsers:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Privacy

- No data is sent to any server
- No tracking or analytics
- No cookies or user profiling
- Completely private and offline-capable

## 💡 Tips & Best Practices

1. **Regular Backups** — Export your data to CSV monthly as a backup
2. **Follow-up Dates** — Set realistic follow-up dates (usually 1-2 weeks after application)
3. **Detailed Notes** — Add notes about the company, role, or interview insights for future reference
4. **Track Everything** — Even rejected applications help you learn and improve
5. **Update Status** — Keep statuses current so your dashboard accurately reflects your progress

## 🐛 Troubleshooting

**Q: My data disappeared!**
- A: Check if you're using a different browser or cleared your browser cache. Always export to CSV as a backup!

**Q: Can I sync data across devices?**
- A: Export as CSV on one device and import on another. Cloud sync is not currently supported.

**Q: Can I share my data with others?**
- A: Export to CSV and share the file. They can then import it into their own tracker.

## 🤝 Contributing

Found a bug? Have a feature suggestion?
1. Open an issue on GitHub
2. Describe the problem or feature request
3. Include screenshots if helpful

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙌 Acknowledgments

Built with care for job seekers everywhere. Good luck with your applications! 🚀

---

**Happy job hunting! 📝✨**
