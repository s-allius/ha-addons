# TSUN Proxy Apps for Home Assistant

This Home Assistant App repository provides the **TSUN Proxy App**, which seamlessly integrates TSUN inverters (including TSOL MS800, MS2000, MS3000, MX800, MX1000, MX3000) and battery systems (TSOL DC1000) into your Home Assistant environment.

---

## 🤖 Automated Repository (CI/CD)

> [!NOTE]
> This repository is fully automated. You do not need to open issues or pull requests here. All files, updates, and releases in this repository are automatically built and deployed via a GitHub workflow directly from the main project repository: **[tsun-gen3-proxy](https://github.com/s-allius/tsun-gen3-proxy)**.

---

## 🚀 Installation

You can add this repository to your Home Assistant instance either automatically or manually.

### Method 1: Automatic (Recommended)

Click the button below to open your Home Assistant instance and automatically add this repository:

[![Open your Home Assistant instance and show the add-on store with a row (add-on repository) pre-filled.][repository-badge]][repository_url]

### Method 2: Manual Installation

If the automatic redirect does not work, follow these simple steps:

1. Copy the repository URL: `https://github.com/s-allius/ha-addons`
2. In your Home Assistant dashboard, navigate to **Settings** > **Add-ons** (or **Apps**).
3. Click on the **Add-on Store** (App Store) button in the bottom right corner.
4. Click the **three dots** in the top right corner and select **Repositories**.
5. Paste the copied URL into the field and click **Add**.
6. Close the dialog and **reload** the App store page.
7. Find the **TSUN Proxy App** in the list, click it, and hit the **Install** button.

---

## 🛠️ Configuration & Usage

Once installed, please refer to the documentation inside the specific App folder for configuration details regarding your specific TSUN inverter or battery model.

---

## 📄 License

This repository is licensed under the [BSD 3-Clause License](LICENSE).

[repository-badge]: https://img.shields.io/badge/Add%20repository%20to%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[repository_url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fs-allius%2Fha-addons
