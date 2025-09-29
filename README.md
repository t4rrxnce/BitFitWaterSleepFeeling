# BitFit Water + Sleep + Feeling Tracker

## Overview
This is my Unit 5 project for CodePath AND102. The app is an offline-friendly health tracker built with Room and Kotlin. It lets users log daily health entries and view them in a scrollable list.

### Metrics tracked:
- 💧 Water consumption (oz)
- 😴 Hours of sleep (slider, 0–12)
- 🙂 Morning feeling (slider, 1–10)

All entries are saved in a local Room database and persist across app restarts.

---

## Required Features
- [x] At least one health metric is tracked (here: water, sleep, feeling).
- [x] “Create entry” UI for daily input.
- [x] New entries are saved in a database.
- [x] RecyclerView updates with new entries.
- [x] Entries persist after app restart.

---

## Stretch Features
- [x] Dashboard with:
  - Total water consumed today
  - Average hours of sleep
  - Average feeling score
- [x] Material Design UI (Toolbar, CardView, FAB).
- [x] Orientation responsive layouts.

---

## Walkthrough
https://github.com/t4rrxnce/BitFitWaterSleepFeeling/blob/bca50f4fbb8afbe9eebd44ce9f952ea0f028227c/Untitled%20design%20(9).gif 

---

## Technical Details
- **Language:** Kotlin  
- **Database:** Room (Entity, DAO, Database)  
- **UI:** RecyclerView + custom adapter, MaterialToolbar, MaterialCardView, FAB, SeekBars  
- **Async:** Coroutines with `Dispatchers.IO` for DB work  

---

## Project Structure
app/src/main/java/com/codepath/bitfitcombo/
├── AddEntryActivity.kt
├── MainActivity.kt
├── AppDatabase.kt
├── Entry.kt
├── EntryDao.kt
├── EntryAdapter.kt
└── DateUtil.kt


---

## Author
Terrance McGowan  
CodePath AND102 – Unit 5 Project
