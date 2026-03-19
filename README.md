## 📝 Project Description

**BantayPahayag** is an intelligent fact-checking and bias analysis application designed specifically for the Philippine media landscape. As misinformation becomes increasingly sophisticated, this tool provides a data-driven approach to news consumption by analyzing linguistic patterns, identifying political leaning, and cross-referencing claims against a real-time database of reliable news sources.

The system utilizes a **Random Forest** classifier for claim detection and truthfulness verification, paired with **LIME (Local Interpretable Model-agnostic Explanations)** to show users exactly which parts of an article triggered a specific verdict.

---

## 📲 Installation Instructions

Follow these steps to install the **BantayPahayag** prototype on your Android device:

1. **Download the APK:**
   * Navigate to the [**Assets**](https://github.com/fborj/BantayPahayag/releases) section of the latest release.
   * Click on `BantayPahayag.apk` to start the download.

2. **Enable Unknown Sources:**
   * Before installing, go to your device **Settings**.
   * Navigate to **Security** or **Privacy** (this varies by Android version).
   * Enable the option to **"Install from Unknown Sources"** or "Install Unknown Apps" for your mobile browser.

3. **Install the App:**
   * Open your **Downloads** folder or click the download notification.
   * Tap the APK file and follow the on-screen prompts to complete the installation.

4. **System Requirements:**
   * **OS:** Android 8.0 (Oreo) or higher.
   * **Internet:** A stable connection is required for **Web Scraping** and **Evidence Retrieval** functions.
   * **Note:** This version is a technical prototype for thesis evaluation.

---

### 🛠️ Core Technology
* **Machine Learning:** Random Forest (Fact-Checking & Bias Analysis)
* **NLP:** TF-IDF & MiniLM (Semantic Embedding)
* **Explainability:** LIME (Verdict interpretation)
* **Backend:** BeautifulSoup (Hourly automated web scraping)
