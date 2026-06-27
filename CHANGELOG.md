# Changelog

## [0.0.2] - 2026-06-27

### Added
- **Navigation bar**: Home, Guides, Builds, Calculators, Notes, Settings tabs
- **Profiles system**: Add/delete/switch between character profiles (max 6)
- **Profile selector** in header with + and ✕ buttons
- **Notification bell** with dot indicator
- **Guides page** with "How to Use This Tracker" guide (accordion style)
- **Builds page** (placeholder - "Coming Soon")
- **Calculators page** (placeholder - "Coming Soon")
- **Notes page** with per-profile notepad (auto-saves)
- **Settings page** with notification toggles and data management
- **Reset category to default** (↺ button per section) - restores default tasks
- **Shop hints** as tooltips (📍 icon) showing where to buy items
- **Catch-up reset logic** - tasks auto-reset on page load if reset time was missed
- **Local + UTC time** display in countdown timers
- **Sticky sidebar** - progress bars and countdown timers stay visible while scrolling
- **Dark, Light, and T&L (purple/gold) themes**

### Changed
- **Header layout**: Title centered with profile selector on left, theme controls and notification bell on right
- **Guides**: Only "How to Use This Tracker" guide remains
- **Settings**: Notification checkboxes now properly aligned (label left, checkbox middle, description right)
- **Data Management**: Cleaner layout with separate rows for Export, Import, and Clear All
- **Countdown timer display**: More stable width with tabular-nums

### Fixed
- Notification checkbox alignment in Settings
- Data Management import file input size and layout
- Countdown timer width jumping when numbers change

---

## [0.0.1] - 2026-06-27

### Added
- Daily, weekly, and monthly task checklists with persistent save state
- Custom tasks with optional countdown timers (HH:MM format)
- Counter support for multi-step tasks (e.g., 3/3 Co-op Dungeons)
- Auto-reset at 08:00 UTC (daily), Tuesday 08:00 UTC (weekly), 1st of month 08:00 UTC (monthly)
- Three-column layout with sticky progress bars (left) and countdown timers (right)
- Click anywhere on a task row to toggle completion
- Quick Add (+ button) in each section header
- Edit (✎) and Delete (✕) buttons on every task
- 3 themes: Dark, Light, and T&L (purple/gold)
- Auto-save to browser localStorage
- Completely offline - no internet connection needed
- Live countdown timers that update every second
- Responsive design (desktop, tablet, mobile)

### Fixed
- Daily tasks not resetting when browser was closed during reset time (catch-up logic)
- Countdown timer width jumping when numbers change (fixed with tabular-nums)

### Known Issues
- Data is stored locally only (no cloud sync)
- Clearing browser data will erase progress
- Notifications require browser permission