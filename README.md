# 💻 Windows 11 Telemetry and Bloatware Remover by X-EON

**Version: 1.0.0**

## ⚠️ Disclaimer

This script is provided for **educational purposes only**. By using it, you accept full responsibility for any consequences. [cite_start]**Modifying system settings can potentially disrupt functionality [cite: 3]**.

[cite_start]**It is highly recommended to create a system restore point before proceeding [cite: 4]**. [cite_start]Use this script at your own risk[cite: 5].

---

## 📄 Overview

This batch script is designed to help you remove telemetry, data collection, and bloatware applications from **Windows 11**. [cite_start]It offers granular control over what you want to disable or remove[cite: 2].

---

## ✨ Features

The script presents a menu with the following removal options:

* **1. [cite_start]Telemetry and data collection:** Disables data collection by Microsoft services and apps (modifies `AllowTelemetry`, `AllowDiagnosticData`, `MaxTelemetryEnabled`, and `Start_TrackProgs` registry keys)[cite: 6, 8].
* **2. [cite_start]Web search:** Removes Bing integration in Windows Search, and disables Cortana, which is described as "shitty anyway"[cite: 6, 9].
* **3. [cite_start]Windows 11's advertising ID:** Opts-out of targeted advertising for increased privacy (modifies the `Enabled` registry key in both **Local Machine** and **Current User** contexts)[cite: 6, 10].
* **4. [cite_start]Built-in apps:** Completely removes **Cortana**, **Feedback Hub**, and attempts to remove **Edge** (note: Edge removal may not work on most Windows 11 builds)[cite: 6, 11, 12, 13].
* **5. [cite_start]Built-in services:** Disables the startup of **WerSvc** (Windows Error Reporting Service)[cite: 6, 14]. *(Note: The script menu mentions DiagTrack and dmwappushservice, but the services section only explicitly disables WerSvc in the current code.)*
* **6. [cite_start]Recall:** Disables Recall by deleting its associated scheduled tasks[cite: 6, 15].
* **7. All of the above:** Performs all removals mentioned in options 1 through 6.
* **8. [cite_start]Exit:** Closes the script[cite: 6].

---

## 📥 Installation and Usage

### Downloading and Running the Script

1.  **Download the latest release:** Head over to the Releases page and download the latest .zip file.
2.  **Extract the files:** Unzip the downloaded file.
3.  [cite_start]**Run as Administrator:** **You must right-click the script and select "Run as administrator"** for it to function correctly[cite: 1].

### Using Git (Optional)

1.  **Open a command prompt or terminal.**
2.  **Navigate to the desired directory.**
3.  **Clone the repository:**
    ```bash
    git clone https://github.com/krookzmane/telemetryremover
    ```
4.  **Change directory:**
    ```bash
    cd telemetryremover
    ```
5.  **Run the script:** Double-click the `bloat-telemetry-remover.bat` file and **run as administrator**.

### Usage Instructions

1.  **Launch the script:** Run the batch file as administrator.
2.  **Select options:** The script will present a menu.
3.  [cite_start]**Follow prompts:** Enter the corresponding number for the desired action (1-8) and press Enter[cite: 7].
4.  [cite_start]**Completion:** The script will confirm the action and pause, requiring you to press a key to return to the main menu[cite: 9, 10, 11, 14, 15].
5.  [cite_start]**Exiting:** Select option **8** or wait for the 'All' option to complete, and press a key to exit[cite: 15].
