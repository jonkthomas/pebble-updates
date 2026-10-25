# Meerkat updates

**Keep your coding limits in view.** Meerkat shows AI coding usage limits and reset times in your Mac's menu bar, with optional notch and low-limit alerts. Providers expose different data—percentages, time windows or credits—not always exact token counts.

Choose your coding profiles and press **Connect**; no terminal commands or login tokens to copy. Claude, Codex and Grok read limits through their own coding apps; Muse shares its last observed report when supported. Claude uses native quota metadata, and connecting does not rewrite your status line. If a cold CLI has no limits yet, the separate **Probe usage** action sends one tiny Haiku prompt on a confirmed Claude subscription, then reads the real metadata in that same process. Each explicit click uses your Claude allowance and any enabled extra usage; background checks never send model prompts. The dated snapshot remains for up to 15 minutes or reset (in memory; restarting Meerkat needs a new probe). API-key accounts are not eligible. A recent already-installed Claude reporter can remain a fallback. Native Claude usage support depends on your Claude Code version and account; unavailable limits remain unknown, never a guessed percentage. Pi, OpenCode and desktop clients can use the provider profile you explicitly select—not an invented extra quota. Meerkat does not import Claude login tokens or grant blanket Keychain or browser access.

In **Connections**, choose **Remove from Meerkat** to stop tracking a profile. Its coding-app account, credentials and settings stay intact. **Disconnect** pauses readings without removing the profile. Adding a removed native profile back requires **Connect** again.

When a Meerkat release is available, download its **Meerkat DMG** from [Releases](https://github.com/jonkthomas/pebble-updates/releases), open it, and drag Meerkat to Applications. Release downloads are signed and notarized for macOS 14 or later on Apple silicon. The ZIP is for automatic updates.

Quit your installed copy before a manual replacement. Replace that copy rather than keep two apps. The technical app identity stays stable so existing accounts, settings and updates remain connected.

Updates download in the background and install when you quit, or when you choose Restart. `appcast.xml` is a signed Sparkle feed; do not edit it after signing. The public update repository and feed address stay stable for existing installs. Application source is not published here.
