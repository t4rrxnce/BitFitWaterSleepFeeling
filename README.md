BitFit v2 — Water • Sleep • Feeling

Unit 6 — CodePath AND102

BitFit is an offline-friendly health tracker built with Kotlin, Room, and Jetpack. In Project #6 it evolves to a multi-screen app using the Navigation Component with a BottomNavigationView and a Dashboard that summarizes the last 7 days (totals/averages + chart).

Metrics tracked

💧 Water consumed (oz)

😴 Hours of sleep (0–12)

🙂 Morning feeling (1–10)

All entries are stored locally with Room and persist across app restarts.

📱 Screens

Log — Scrollable list of all entries with pull-to-refresh and a FAB to add a new entry.

Dashboard — Today’s water total, average sleep, average feeling, and a 7-day trend chart.

✅ Required Features (Unit 6)

 App uses multiple destinations with Navigation Component.

 BottomNavigationView swaps between Log and Dashboard fragments.

 Create Entry flow saves data to a Room database.

 RecyclerView updates as new entries are added.

 Data persists across app restarts.

 Uses ViewModel + Repository + Kotlin Flows to observe DB changes.

 Material 3 DayNight theme with a top MaterialToolbar.

✨ Stretch Features Implemented

 Dashboard summaries (today’s water, avg sleep, avg feeling).

 7-day chart (MPAndroidChart).

 SwipeRefreshLayout on the Log list.

 Orientation-responsive layouts & values-night/ dark theme resources.

 Polished UI with Material components (Toolbar, Cards, FAB).

🎥 Walkthrough
[
(https://github.com/t4rrxnce/BitFitWaterSleepFeeling/blob/ebadaa00f1c9553e0bb2c52d6e95f9e84bc3052a/Untitled%20design%20(11).gif)](https://github.com/t4rrxnce/BitFitWaterSleepFeeling/blob/ebadaa00f1c9553e0bb2c52d6e95f9e84bc3052a/Untitled%20design%20(11).gif)

🛠 Tech Stack

Language: Kotlin

Architecture: MVVM + Repository

DB: Room (Entity, DAO, Database) with KSP compiler

Async: Coroutines + Flow

UI: RecyclerView + custom adapter, MaterialToolbar, MaterialCardView, FAB, SeekBars, SwipeRefreshLayout

Navigation: Jetpack Navigation Component (fragments + bottom nav)

Charts: MPAndroidChart

Theming: Material 3 DayNight, values-night/

---

## Author
Terrance McGowan  
CodePath AND102 – Unit 6 Project
