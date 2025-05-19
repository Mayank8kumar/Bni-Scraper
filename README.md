# BNI India Member Scraper

## Overview

This project is an automation-driven web scraper designed to extract publicly available member and profile data from the BNI India directory. The objective is to support internal business development teams by programmatically gathering initial leads that can be used to build a potential customer base.

This codebase reflects a simplified version of a broader internal tool and is intended to demonstrate automation logic, project staging, and structural approach in building scalable data extractors.

---

## Disclaimer

> 📌 **This repository is a sample representation only.**
> Due to data privacy and organizational restrictions, the full production-grade implementation — which includes detailed modules for data validation, cleaning, and post-processing — is **not included** in this public version.
> The shared code is a brute prototype version and should be treated as a functional base rather than a complete pipeline.

---

## Technical Stack (Versions as of January 2024)

* ✅ Python 3.10
* ✅ Selenium 4.16.0
* ✅ BeautifulSoup 4.12.2 (via bs4)
* ✅ requests 2.31.0
* ✅ Jupyter Notebooks (optional for iterative development)
* ✅ ChromeDriver 120.0+ (compatible with Chrome v120)

---

## Project Structure and Stages

The scraper is developed in multiple staged components to mirror real-world data extraction pipelines:

1. ⚙️ **Stage 1 – Initial Navigation & Setup**
   Automates browser actions, logs entry points, and sets up scraping logic.

2. 🧲 **Stage 2 – Data Extraction**
   Captures key member information (e.g., names, roles, chapters, etc.).

3. 📦 **Stage 3 – Export & Structuring (Optional)**
   *\[Not included in this version]* In full implementations, this stage handles structured export (e.g., CSV/JSON), validation, and integration with downstream tools.

---

## Usage Instructions

### Prerequisites

* Python 3.10 or later
* Install required packages manually:

  ```bash
  pip install selenium==4.16.0 beautifulsoup4==4.12.2 requests==2.31.0
  ```

### Run the Scraper

* Ensure ChromeDriver v120+ is installed and available in your system's PATH.
* Execute the script:

  ```bash
  python scraper.py
  ```

> 💡 Ensure a stable internet connection and valid browser settings if using headless mode.

---

## For Recruiters & Employers

This repository reflects a modular and staged approach to building real-world data tools. While the current code is a simplified version, it represents my understanding of browser automation, data gathering strategy, and the foundation required to build scalable internal utilities.

Feel free to reach out if you'd like to explore the complete project or discuss the system design and enhancements.

---

## License & Usage Terms

This project is shared **for educational and internal reference purposes only**.
🔒 **Not for commercial use or redistribution.**

---

## Contact

**Mayank Kumar**
📧 [mayankkumar08132@gmail.com](mailto:mayankkumar08132@gmail.com)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/mayankkumar-tech/)
