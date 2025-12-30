# Xiaomi TV Debloating (ADB)

Recently, I purchased a **Xiaomi QLED 43" TV A Pro 43 2026**  
(Model: **L43MB-APME**, ID: **1139939**).

After connecting to the TV using **ADB** (via an ADB TV app and the `adb` console), I discovered that the system comes with a large number of preinstalled applications. Running the following command:

    pm list packages

showed a total of **167 installed packages**.

## Repository Contents

- **`installed-packages.txt`**  
  A complete list of all packages installed on the TV out of the box.

- **`removed-packages.txt`**  
  A list of packages that I have personally removed.

So far, I have removed **40 apps**, and the TV has been working perfectly for my needs and requirements since then.

## Notes

- I do **not** need all preinstalled apps, which is why this cleanup was performed.
- Some system apps are **critical** for proper TV operation. Removing the wrong package **may break system functionality or even brick your device**.
- If I decide to remove additional apps in the future, I will update the `removed-packages.txt` file accordingly.

## ⚠️ Disclaimer

If you choose to use the package list from `removed-packages.txt`, **you do so at your own risk**.

I am **not responsible** for any damage, data loss, or malfunction that may occur as a result of uninstalling system packages on your TV.

---

Feel free to open an issue or submit a pull request if you have additional findings, corrections, or suggestions.
