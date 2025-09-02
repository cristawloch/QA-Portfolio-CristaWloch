# Sprint 6 – Urban Lunch Mobile App Manual Testing (Android Studio)

## Overview
In Sprint 6, I focused on **manual mobile app testing** for the Urban Lunch Android application.  
Key activities included:

- **Learning and using Android Studio** with a Pixel 5 emulator to install, run, and interact with the app in a controlled test environment.  
- **Executing manual functional tests** across core user flows — login, menu browsing, cart management, checkout, payment, and order tracking — using both checklist‑driven and exploratory approaches.  
- **Documenting defects as Jira**, each with clear summaries, reproduction steps, expected vs. actual results to ensure developer‑ready clarity.  

This sprint strengthened my ability to test mobile applications end‑to‑end, reproduce and isolate issues, and communicate findings in a way that supports efficient fixes.

**Related Resources:**  
- 📄 [Sprint 6 Google Drive Test Documentation](https://docs.google.com/spreadsheets/d/1nNq8GWS4qqKsPb6n_uY6thkHnOkm1cIozoH9OXFuyEY/edit?gid=287334773#gid=287334773)  
- 🗂 [Sprint 6 Jira Board](https://cristaquility.atlassian.net/jira/software/projects/TS6P/boards/100?selectedIssue=TS6P-1)  

---

## Environment
- Device: Pixel 5 (Android Studio emulator)    
- Network: Wi‑Fi, stable connection    

---

## Key Bug Reports

| ID   | Summary                                                        | Steps to Reproduce                                                                 | Expected Result                                               | Actual Result                                   |
|------|----------------------------------------------------------------|------------------------------------------------------------------------------------|----------------------------------------------------------------|-------------------------------------------------|
| S6‑01 | Long restaurant names overlap price and amount counters        | 1. Open Urban Lunch → 2. Select a restaurant with a long name (e.g., “The Aroma Lane”) → 3. Tap “Tomato Soup And Croutons” → 4. Scroll past ingredients | Price and restaurant name display without overlap             | Price and restaurant name overlap amount counters |
| S6‑02 | Missing delivery cost in order summary                         | 1. Place an order → 2. Proceed to order summary                                    | Delivery cost is displayed in summary                         | Delivery cost is missing                        |
| S6‑03 | Map does not show order of pick‑up points                       | 1. Open Urban Lunch main page → 2. View pick‑up points on map                       | Pick‑up points displayed in correct order                      | Pick‑up points appear unordered                  |

---

## Conclusion & Recommendations
Sprint 6 testing confirmed that the Urban Lunch app’s main flows work under normal conditions, but several issues affect user experience:

- Adjust UI layout to prevent text overlap on menu item details  
- Display delivery cost in order summary  
- Ensure map pick‑up points are shown in correct order
