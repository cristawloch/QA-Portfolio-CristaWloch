## Sprint 8 — Selenium End-to-End Automation (Urban Routes)

**Platform:** Python, Selenium WebDriver, PyTest, Page Object Model (POM)  
**Focus:** Full automation of Urban Routes app  
**GitHub Repository:** [QA-USA-Python_Automation1](https://github.com/cristawloch/QA-USA-Python_Automation1)

**Key Deliverables:**
- Implemented **Page Object Model (POM)** in `pages.py` for maintainable, reusable test code
- Automated complete booking flow:
  1. Set route  
  2. Select tariff  
  3. Enter phone  
  4. Verify SMS  
  5. Add card  
  6. Add driver comment  
  7. Order blanket & handkerchiefs  
  8. Order 2 ice creams  
  9. Verify car search modal
- Applied **explicit waits** and **conditional checks** to ensure stability
- Created helper utilities for common actions
- Structured tests in `main.py` with locators + methods in `pages.py`

**Technical Skills Demonstrated:**
- Selenium WebDriver automation with PyTest
- POM architecture for scalability and maintainability
- Synchronization strategies using explicit waits
- Modular test design with separation of concerns

**Outcome:**  
Delivered a robust, fully automated test suite covering the Urban Routes booking process from start to finish, ready for CI/CD integration and regression testing.
