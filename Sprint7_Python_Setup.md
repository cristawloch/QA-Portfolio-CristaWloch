## Sprint 7 — Python Test Framework Setup (Urban Routes)

**Goal:**  
Establish the Python project structure and foundational files for automated UI testing of the Urban Routes web app, preparing for Selenium implementation in Sprint 8.

**Key Deliverables:**  
- **`helpers.py`** — Imported utility functions (`retrieve_phone_code`, `is_url_reachable`) provided by the course, kept unmodified for consistency.  
- **`data.py`** — Centralized constants for test data (addresses, phone number, card details, driver message) to ensure easy updates without altering test logic.  
- **`main.py`** — Pytest class `TestUrbanRoutes` with:
  - `setup_class` method to verify server connectivity before running tests.
  - Eight placeholder test methods aligned with Sprint 8 automation goals (route setup, plan selection, phone entry, card entry, driver message, blanket/handkerchief order, ice cream order, car model check).

**Technical Skills Demonstrated:**  
- Python project structuring for test automation.  
- Modular test data management.  
- Pytest class and method scaffolding.  
- GitHub version control with clear, atomic commits.  

**Outcome:**  
A clean, modular, and version‑controlled Python test framework, ready for Selenium WebDriver integration in Sprint 8. This setup ensures that test logic, data, and utilities remain decoupled, improving maintainability and scalability.
