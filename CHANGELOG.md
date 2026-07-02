# Changelog

## [0.0.5] - 2026-07-02

### Added
- **Back to Top button** – floating arrow appears when you scroll down
- **Click title to go home** – clicking "T&L Tracker" takes you to the Home page
- **Settings page redesign** – organized into topic boxes (Appearance, Default View, Server & Reset, Notifications, Data Management)
- **Server & Reset Time** – select your server (EU, NA East, NA West, SA, JP, OCE) or set custom reset time
- **Compact Mode** – smaller task rows and tighter spacing
- **Font Size** – Small, Medium, Large options
- **Hide Completed Tasks** – toggle to hide checked tasks from view
- **Default View** – choose which tab opens when you start the tracker
- **Confirm before auto-reset** – ask for confirmation before resetting tasks
- **Edit custom task timer** – edit countdown time and date/time for custom tasks

### Changed
- Settings page now uses a grid layout with topic-based cards
- All settings (including theme, default tab, font size, compact mode) are saved per profile
- Export/Import backup now includes all settings and data in one file

### Fixed
- Custom tasks can now have their timer edited (countdown or date/time)
- Auto-reset now asks for confirmation before resetting tasks

## [0.0.4] - 2026-06-29
### Added
- Profile edit feature: Edit profile name and server via ✎ button
- Profile dropdown now shows "Name - Server"
- Builds page with visual build tracking
- Build cards with name, tags, progress, and item count
- Drag and drop reordering for build items
- Move Up/Down buttons for reordering
- Progress tags with color coding: Wishlist (blue), In Progress (yellow), Done (green)
- Click progress tag to cycle through Wishlist → In Progress → Done
- Item modal with name, source, cost, and note fields
- Build tags (e.g., World Boss, Dungeon) on build cards
- Per-profile builds

## [0.0.3] - 2026-06-29
### Changed
- App width increased from 1300px to 1500px
- Task names no longer include numbers
- Guild Check-in removed from Daily default tasks
- Abyssal Token burn removed from Daily default tasks
- Shop hints now shown as pin tooltips (📍)
- Task rows have more spacing
- Edit button now allows changing max count and location
- Quick Add now includes max count and location fields
- Custom task form now includes max count and location fields

## [0.0.2] - 2026-06-27
### Added
- Navigation bar: Home, Guides, Builds, Calculators, Notes, Settings tabs
- Profiles system: Add/delete/switch between character profiles (max 6)
- Profile selector in header with + and ✕ buttons
- Notification bell with dot indicator
- Guides page with "How to Use This Tracker" guide
- Builds page (placeholder)
- Calculators page (placeholder)
- Notes page with per-profile notepad
- Settings page with notification toggles and data management
- Reset category to default (↺ button)
- Shop hints as tooltips (📍)
- Catch-up reset logic
- Local + UTC time display
- Sticky sidebar
- Dark, Light, and T&L themes

## [0.0.1] - 2026-06-27
### Added
- Initial release
- Daily, weekly, and monthly task checklists
- Custom tasks with countdown timers
- Counter support for multi-step tasks
- Auto-reset at 08:00 UTC
- Three-column layout with sticky progress bars and countdown timers
- Click anywhere on a task row to toggle completion
- Quick Add (+ button) in each section header
- Edit (✎) and Delete (✕) buttons on every task
- 3 themes: Dark, Light, and T&L
- Auto-save to browser localStorage
- Completely offline
- Live countdown timers
- Responsive design
