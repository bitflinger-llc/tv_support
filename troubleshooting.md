# Troubleshooting Guide

Start with the steps below in order — most issues are resolved by step 1 or 2.

---

## 1. Authentication Errors

**Symptoms:** You're stuck on a login screen, the app says your account can't be verified, or you're unexpectedly signed out.

**Fix: Force close the app and relaunch it.**

### Android TV / Google TV

1. Press the **Home** button on your remote to leave the app.
2. Open **Settings → Apps → See all apps → Bitflinger TV**.
3. Select **Force Stop**, then confirm.
4. Relaunch Bitflinger TV from the home screen.

### Android (phone / tablet)

1. Tap the recent apps button (square or three-line icon) to open the app switcher (on newer devices, swip up from the bottom of the screen.
2. Swipe the Bitflinger TV card away to close it.
3. Tap the app icon to relaunch.

Alternatively: **Settings → Apps → Bitflinger TV → Force Stop**.

### iOS

1. Swipe up from the bottom of the screen (or double-press the Home button on older devices) to open the app switcher.
2. Swipe the Bitflinger TV card up to close it.
3. Tap the app icon to relaunch.

If the issue persists after force closing, try signing out and back in using the profile avatar in the top-left corner of the home screen.

---

## 2. Content Issues

**Symptoms:** Content rows are empty, recommendations look wrong, images are missing, or you're seeing stale data.

**Fix: Clear app data to remove cached content.** Your data (account, watchlist, preferences) is stored on our servers and will be restored automatically after you sign back in.

### Android TV / Google TV

> Delete **all app data** — not just the cache. This ensures the content cache is fully reset.

1. Press **Home** on your remote and open **Settings → Apps → See all apps → Bitflinger TV**.
2. Select **Clear data** (not "Clear cache").
3. Confirm when prompted.
4. Relaunch the app and sign in. Your watchlist and preferences will sync from the server.

### Android (phone / tablet)

> Delete **all app data** — not just the cache.

1. Open **Settings → Apps → Bitflinger TV → Storage**.
2. Tap **Clear Data** (not "Clear Cache").
3. Confirm when prompted.
4. Relaunch the app and sign in. Your watchlist and preferences will sync from the server.

### iOS

1. Open **Settings** (the iOS Settings app, not Bitflinger TV settings).
2. Scroll down and tap **Bitflinger TV**.
3. If an "Offload App" or "Delete App" option is shown, deleting and reinstalling (see step 3 below) is the most effective reset on iOS.

---

## 3. Reinstall the App

If the steps above don't resolve your issue, a clean reinstall is recommended.

Your data is backed up on our servers — after reinstalling and signing in, your account, watchlist, and preferences will be restored.

### Android TV / Google TV

1. Open **Settings → Apps → See all apps → Bitflinger TV**.
2. Select **Uninstall** and confirm.
3. Open the Google Play Store and reinstall **Bitflinger TV**.

### Android (phone / tablet)

1. Long-press the Bitflinger TV icon and tap **App info**, or go to **Settings → Apps → Bitflinger TV**.
2. Tap **Uninstall** and confirm.
3. Open the Google Play Store and reinstall **Bitflinger TV**.

### iOS

1. Long-press the Bitflinger TV icon.
2. Tap **Remove App → Delete App** and confirm.
3. Open the App Store and reinstall **Bitflinger TV**.

---

## Still Having Issues?

If none of the above resolves your problem, please [open a GitHub issue](https://github.com/bitflinger-llc/tv_support/issues) with a description of what you're seeing, or email us at [help@bitflinger.net](mailto:help@bitflinger.net).

← [Back to Support Home](README.md)
