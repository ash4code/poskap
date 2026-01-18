# Kabir Auto Parts - POS (v1.1.0)

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/ash4code/poskap?label=latest%20release)](https://github.com/ash4code/poskap/releases/latest)

A comprehensive standalone Point of Sale (POS) and shop management system built with Python and tkinter. Custom-built for **Kabir Auto Parts**, this application streamlines order management, invoicing, part requests, and sales commissions into a single, powerful desktop tool.

![Kabir Auto POS Dashboard Screenshot](dashboard.png)

## 📥 Download

The latest standalone Windows application (**no installation required**) is available on our **[Releases Page](https://github.com/ash4code/poskap/releases/latest)**.

## ✨ Key Features

This application consolidates essential business functions into one central hub:

* **📈 Financial Dashboard:** Get a real-time snapshot of your finances with a breakdown of **Total**, **Paid**, and **Unpaid** invoice amounts for any selected month and year.
* **🛒 Flexible Order Management:**
    * **Standard Order:** Quick and simple manual entry for standard OEM parts.
    * **🏍️ Hero Genuine Mode (NEW):** A dedicated tab for Hero Genuine parts featuring a **built-in web scraper**. Automatically fetches part details (Description, MOQ, Price) from the official catalogue, applies a default **24% DLP**, and calculates expected totals.
    * **🔧 Non-OEM Order:** A specialized form tailored for non-OEM parts with detailed vehicle and brand fields.
* **🧾 Accounting & Invoicing:** Complete invoice management system with visual status tracking (`PAID` in green, `UNPAID` in red).
* **📦 Part Request Tracking:** Log customer part requests and generate professional **PDF receipts** instantly.
* **💰 Sales Commission:** Manage mechanic commissions with flexible calculation methods (percentage-based or fixed amount) and generate detailed slips.
* **📂 Export Capabilities:** Seamlessly export orders, invoices, and slips to **PDF** and **XLSX (Excel)** formats.
* **⚙️ Admin Utilities:** Secure crucial sections with password protection and easily **Backup & Restore** your entire database.

## 📸 Screenshots

| Dashboard | About & Database |
| :---: | :---: |
| ![Dashboard Page](dashboard.png) | ![About Page](about.png) |

### 🔐 Admin Access

Sensitive sections like **Accounting** and **Sales Commission** are password-protected to ensure data security.

* **Default Password:** `admin123`

*(Note: This password is hard-coded in v1.1.0. Future updates will allow for custom password configuration.)*

## Credits

* **Developer:** [ash4code](https://github.com/ash4code)
* **Project Context:** Developed as a bespoke management solution for Kabir Auto Parts.
* **Development Workflow:** This project highlights a modern "pair-programming" approach. Google's **Gemini** (a generative AI) served as a collaborative partner, assisting the developer (ash4code) with design, code generation, and debugging.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Running from Source (For Developers)

To run the application directly from the source code:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ash4code/poskap.git](https://github.com/ash4code/poskap.git)
    cd poskap
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # Create the environment
    python -m venv venv

    # Activate on Windows
    .\venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *Note: You will also need `msedgedriver.exe` in the root directory for the web scraper to function.*

4.  **Run the application:**
    ```bash
    python main.py
    ```
