# Recommendations

Get the most out of PocketCloud with these tips and recommendations.

---

## 📱 Recommended Server Device (C2)

- **Battery:** Keep it plugged in at all times — PocketCloud Server runs 24/7
- **RAM:** At least 2GB recommended for stable background operation
- **Android version:** Android 10 or higher (Android 12 recommended)
- **Storage:** The more the better — this is your personal cloud!
- **WiFi:** Keep it connected to a stable 2.4GHz or 5GHz network
- Older mid-range phones work great: Motorola G series, Redmi, Samsung A series

---

## 🔒 Security Recommendations

- Use a strong password (at least 8 characters, mix of letters and numbers)
- Never share your server IP publicly
- Use Tailscale for remote access instead of port forwarding
- Keep both apps updated to the latest version
- If you suspect unauthorized access, change your password immediately from Settings

---

## 🌐 Network Recommendations

- Place C2 as close to your WiFi router as possible for best signal
- Use a 5GHz WiFi network for faster file transfers
- If your router supports it, assign a static IP to C2 so the address never changes
- For remote access outside your home, always use **Tailscale** — it is free, open-source, and much safer than opening ports on your router

---

## ⚡ Performance Tips

- Close unused apps on C2 to free up RAM for the server
- Enable "Do Not Disturb" on C2 to prevent interruptions
- If file transfers are slow, try switching to 5GHz WiFi
- For large file transfers, stay on the same WiFi network instead of using Tailscale

---

## 🛠️ Freeing Up Space on C2 with Shizuku + Canta (Android 12)

If your server device (C2) comes with a lot of pre-installed bloatware (Google apps, manufacturer apps, etc.), you can safely remove them to free up RAM and storage using **Shizuku** and **Canta**.

### What are they?
- **Shizuku** — an open-source tool that lets apps use Android's ADB shell without a PC. [Download on Google Play](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) or [GitHub](https://github.com/RikkaApps/Shizuku)
- **Canta** — an open-source app uninstaller that works with Shizuku to remove or disable system apps safely. [Download on GitHub](https://github.com/samolego/Canta)

### Setup
1. Install **Shizuku** on C2
2. Open Shizuku and start it using **Wireless debugging** (no PC needed on Android 11+)
3. Install **Canta**
4. Grant Canta permission in Shizuku
5. Browse the app list and uninstall bloatware safely

### Recommended apps to remove from C2
- Unused Google apps (Maps, YouTube, Gmail, etc.)
- Manufacturer bloatware (games, duplicate apps, etc.)
- Assistant and voice apps that consume RAM in background

### ⚠️ Warning
- Do NOT remove core system apps (Phone, Settings, WiFi, etc.)
- Canta marks apps as Safe / Unsafe / Recommended — always check before uninstalling
- If something breaks, you can reinstall apps from the Play Store or via ADB

---

## 🔋 Battery & Longevity

- Use the original charger to keep C2 healthy long-term
- If possible, keep the battery between 20% and 80% using a smart plug with a timer
- Remove the case if C2 gets hot — ventilation helps
- Consider keeping C2 in a cool, ventilated spot

---

## 📡 Tailscale Setup (Remote Access)

1. Create a free account at [tailscale.com](https://tailscale.com)
2. Install Tailscale on both C1 and C2
3. Sign in with the same account on both devices
4. In PocketCloud Client, use the Tailscale IP of C2 (looks like `100.x.x.x`) as the server address
5. Done — you can now access your files from anywhere in the world

---

## 💡 General Tips

- Use the search bar in PocketCloud Client to quickly find files
- Long press any file to access move, rename, and delete options
- Pull down to refresh the file list manually
- Keep the PocketCloud Server notification visible — dismissing it may cause the server to stop on some devices
