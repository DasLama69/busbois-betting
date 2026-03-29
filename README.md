# 🏇 Bus Bois Betting — 2026

A mobile-friendly web app for tracking our weekly horse racing betting group.

## Live App
👉 **[Open the App](https://YOUR-USERNAME.github.io/busbois-betting)**

> Replace `YOUR-USERNAME` with your GitHub username after setup.

---

## Features
- 🏠 Home dashboard — who's up, account balance, recent bets
- ➕ Log bets with auto-rotation (Cass → Hoops → Pedro → Benji → Billy → CC)
- 🏆 Season leaderboard with ROI comparison bars
- ⚙️ Admin — override rotation, settings, delete bets
- 💾 Export/Import JSON backup + CSV export
- 📄 Weekly PDF report generator
- ✨ AI weekly insight

## Rules
- 6 punters × $10 = **$60/week pool**
- Betting order rotates each week
- **Win** (return ≥ 2× pool) → same punter bets again next week
- **Loss** → rotate to next punter
- **Void** → refund, no P/L impact, rotation unaffected

## Data & Privacy
All bet data is stored in **browser localStorage** on your device. No data is sent to any server. Export a JSON backup regularly from the Admin tab.

## Updating the App
When a new version is ready, replace `index.html` with the new file and commit. GitHub Pages will update within a minute or two.

---

## Changelog

### v1.3.0
- **Fix:** Weekly report no longer counts void bets as losses in the net result total
- **Fix:** Void bet rows in the report table now correctly show $0.00 net and a neutral grey badge
- **Simplified result system:** Reduced from 5 results (Win/Loss/Success/Pending/Void) to 3 (Win/Loss/Void)
  - "Success" removed — any completed week that doesn't go again is now simply a Loss
  - "Pending" removed as a settable option — incomplete weeks remain tracked internally
- **Added:** Subtle version indicator in the app footer

### v1.2.x and earlier
- Initial season setup, Supabase integration, leaderboard, weekly PDF reports, bonus bets, avatar support, drag-and-drop rotation order

---

*Bus Bois Betting 2026 · Built with Claude*
