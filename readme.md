```markdown
# 🖨️ SharePrint App

SharePrint App is a **simple browser-based peer-to-peer (P2P) printing utility** designed for **fast and automatic document printing directly from a web interface**. It is useful for environments where quick printing is required without repeatedly opening the print dialog.

The project works best with **Google Chrome kiosk printing mode**, allowing documents to print instantly to the default printer.

## 🌐 Links

* **Live Demo:** [SharePrint App Demo](https://ronakksdevelopment.github.io/SharePrint-App/)
* **GitHub Repository:** [ronakksdevelopment/SharePrint-App](https://github.com/ronakksdevelopment/SharePrint-App)

## ✨ Features

* **Fast Browser-Based Printing:** Lightning-fast peer-to-peer WebRTC connection for immediate file transfer.
* **Automatic Printing Support:** Bypasses the traditional print preview for a seamless experience.
* **No Print Dialog Popup:** Achieves 100% silent printing using Chrome's kiosk mode flags.
* **Instant Document Printing:** Send PDFs and images directly to the host printer from any device.
* **Works with Google Chrome:** Optimized for Chrome's specific kiosk and printing capabilities.
* **Easy Setup and Usage:** Runs directly from the browser with zero installation or drivers needed.

## 🧠 How It Works

* **The Core Function:** The application triggers printing using the browser’s built-in JavaScript function:

```javascript
window.print();

```

* **Kiosk Mode Magic:** When **Google Chrome** is launched with the `--kiosk-printing` flag, the browser **skips the print dialog** and directly sends the document to the **default printer**.

## ⚙️ Chrome Kiosk Printing Setup (Windows)

To enable **automatic silent printing**, launch Google Chrome using the following command:

```cmd
"C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk --kiosk-printing [https://ronakksdevelopment.github.io/SharePrint-App/](https://ronakksdevelopment.github.io/SharePrint-App/)

```

This command will:

* **Launch Google Chrome** directly to the web application.
* **Open the SharePrint App** automatically.
* **Enable Kiosk Mode** for a fullscreen, distraction-free interface.
* **Enable Silent Printing** to bypass the standard print dialog.
* **Print Directly** to the default printer immediately upon receiving a file.

## 🖥️ Create Desktop Shortcut (Recommended)

* **Step 1:** Right-click on your **Desktop**
* **Step 2:** Select **New → Shortcut**
* **Step 3:** Paste the following command:

```cmd
"C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk --kiosk-printing [https://ronakksdevelopment.github.io/SharePrint-App/](https://ronakksdevelopment.github.io/SharePrint-App/)

```

* **Step 4:** Click **Next**
* **Step 5:** Name the shortcut (e.g., `SharePrint Kiosk`)
* **Step 6:** Click **Finish**

Opening this shortcut will launch Chrome with **automatic printing enabled**.

## 🪟 Silent Printing Without Fullscreen

If you do not want fullscreen kiosk mode but still want the silent printing feature, use:

```cmd
"C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk-printing [https://ronakksdevelopment.github.io/SharePrint-App/](https://ronakksdevelopment.github.io/SharePrint-App/)

```

This keeps the normal Chrome window but still enables **silent printing**.

## 🖨️ Set Default Printer

Before using kiosk printing, make sure your printer is configured:

* **1.** Open **Google Chrome**
* **2.** Press **Ctrl + P** to open the print dialog
* **3.** Select your preferred physical printer
* **4.** Set it as the **default printer** in your OS settings

Chrome will automatically send print jobs to this printer from now on.

## ⌨️ Exit Kiosk Mode

* **Close the App:** To close the fullscreen kiosk mode, simply press `Alt + F4`.

## 💡 Use Cases

* **Print Kiosks:** Setup a dedicated iPad or tablet next to a PC for customers to print.
* **Cyber Café Printing Stations:** Allow users to print directly from their phones to a master printer.
* **POS Receipt Printing:** Send receipts from a mobile ordering device to a central counter printer.
* **Office Printing Dashboards:** Quick, frictionless printing without installing network drivers on every employee's phone.

## 📄 License

* **Open Source:** This project is open-source and available for educational and practical use. Feel free to use and modify it!

---

> ⭐ If you find this project useful, consider **starring the repository**. This app is a hub for seamless P2P printing—enjoy printing without boundaries!

```

```
