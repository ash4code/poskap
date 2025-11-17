# Kabir Auto Parts - POS (v1.0.0)

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/ash4code/KabirAutoPOS?label=latest%20release)](https://github.com/ash4code/KabirAutoPOS/releases/latest)

A standalone Point of Sale (POS) and shop management system built with Python and tkinter. This application is custom-built for Kabir Auto Parts to manage orders, invoicing, part requests, and sales commissions in one simple-to-use desktop tool.

![Kabir Auto POS Dashboard Screenshot](dashboard.png)

## 📥 Download

The latest standalone Windows application (**no installation required**) can be downloaded from our **[Releases Page](https://github.com/ash4code/poskap/releases/latest)**.

## ✨ Key Features

This application combines multiple tools into one central hub:

* **📈 Financial Dashboard:** At-a-glance view of **Total**, **Paid**, and **Unpaid** invoice amounts for any selected month and year.
* **🛒 Order Management:** Separate, tailored forms for creating standard OEM party orders and detailed Non-OEM orders.
* **🧾 Accounting & Invoicing:** Full invoice management system with `PAID` (green) and `UNPAID` (red) status tracking.
* **📦 Part Request Tracking:** Log customer requests and print **PDF receipts**.
* **💰 Sales Commission:** Generate detailed commission slips for mechanics with flexible calculation (by % or ₹).
* **📂 Exporting:** Export orders and slips to professional **PDF** and **XLSX (Excel)** files.
* **⚙️ Admin & Utilities:** Password-protected sections and a simple **Backup & Restore** feature.

## 📸 Screenshots

| Dashboard | About & Database |
| :---: | :---: |
| ![Dashboard Page](dashboard.png) | ![About Page](about.png) |

## Credits

* **Developer:** [ash4code](https://github.com/ash4code)
* **Project:** This application was custom-built as a comprehensive management solution for Kabir Auto Parts.
* **A Note on Development:** This project represents a modern development workflow. Google's Gemini (a generative AI) functioned as a pair-programming partner, collaborating with the developer (ash4code) to help design, write, and debug the application.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Running from Source (For Developers)

If you want to run the application from the source code:

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
    
4.  **Run the application:**
    ```bash
    python app.py 
    ```
