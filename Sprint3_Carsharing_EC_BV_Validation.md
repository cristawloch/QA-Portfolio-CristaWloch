## 🚗 Sprint 3 – Carsharing Requirements on Urban Routes App

In Sprint 3, I focused on validating **carsharing functionality** within the Urban Routes application. This included manual test planning for:

- 💳 Card number input validation using EC/BV techniques  
- 📅 Booking logic and time constraints  
- 🚘 Vehicle availability and selection flow  

All tests were manually executed in Chrome and documented in Google Sheets with structured formatting for developer readability.

📁 [Sprint 3 QA Files – Google Drive](https://drive.google.com/drive/folders/1lmWVbxhKNa5_BM0qwlz1NkAHmsUChBgL)  
🐞 [Sprint 3 Bug Reports – Jira](https://cristaquility.atlassian.net/jira/software/projects/TS3P/boards/34)

---

### 🔍 Card Number Field – EC/BV Test Design

I applied **Equivalence Class Partitioning** and **Boundary Value Analysis** to test the card number field. This included:

- Valid inputs: 16-digit numeric strings (e.g., `4242424242424242`)  
- Invalid inputs: too short (15 digits), too long (17+ digits), non-numeric characters, empty field  
- Edge cases: borderline values at 15 and 17 digits to confirm rejection logic

📊 [Sprint 3 Test Case Sheet – Google Sheets](https://docs.google.com/spreadsheets/d/149xCfPmJoY7_WqeTJEhCzlc_8GC9nvAugXaT93jEsYo/edit?gid=2010888140#gid=2010888140)  
🐞 [Sprint 3 Bug Reports – Jira](https://cristaquility.atlassian.net/jira/software/projects/TS3P/boards/34)

---

### 🧭 Carsharing Requirements Coverage

I also validated core carsharing flows within the Urban Routes app:

- ✅ Vehicle selection and availability logic  
- ⏱️ Booking time overlap and duration constraints  
- ⚠️ Error messaging for invalid payments  

These tests ensure the system handles real-world usage and edge conditions gracefully, supporting a seamless user experience.

