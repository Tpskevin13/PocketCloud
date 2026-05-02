# PocketCloud
Turn your old Android phone into a personal cloud server.
PocketCloud is a free, open-source solution that lets you use an old Android device as a private file server, accessible from your main phone over Wi-Fi or the internet — no subscriptions, no third-party cloud, no data leaving your hands.

# How it works
PocketCloud consists of two companion apps:

PocketCloud Server — installed on your old device (C2). It runs a lightweight Ktor HTTP server in the background, exposing your files through a secure REST API. It stays alive using a foreground service with WakeLock and WifiLock, and can auto-start on boot.
PocketCloud Client — installed on your main device (C1). It connects to the server, lets you browse the full file system of C2, and perform file operations remotely.

# Features
🔒 JWT authentication with BCrypt password hashing
🔐 Brute-force protection (5 failed attempts = 15 minute lockout)
📁 Full file system browser (list, navigate, create folders)
📤 Upload files from C1 to C2
📥 Download files from C2 to C1
✏️ Rename, move, and delete files
💾 Storage usage display (total / used / free)
🔄 Auto-start server on device boot
🛡️ Path traversal attack protection

# Tech Stack
Language: Kotlin
UI: Jetpack Compose + Material Design 3
Server: Ktor (Netty engine) embedded in Android
Client: Ktor HTTP Client
Security: JWT, BCrypt, EncryptedSharedPreferences
Min SDK: 26 (Android 8)

# Remote Access
For access outside your home network, pair both devices with Tailscale (free, open-source VPN) and use your Tailscale IP as the server address.
License
GPL-3.0 — free to use, modify, and distribute.
