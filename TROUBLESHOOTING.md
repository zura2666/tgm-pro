# TGM Pro – Download & Security Warnings

Because TGM Pro is a new and unsigned app, Windows and browsers may show warnings. This is **normal** for indie tools.

Use the steps below if you or your buyers have trouble installing/running the app.

---

## 1. Browser blocks the download

On Chrome / Edge you might see a warning when downloading `TGM Pro.zip` because the file is new.

### Chrome

1. Click the download icon with the warning.  
2. Choose **Keep** → **Keep anyway**.

### Microsoft Edge

1. Click the download warning.  
2. Choose **Keep** → **Keep anyway**.

The ZIP is large because it contains an embedded Python runtime – this is normal for apps built with PyInstaller.

---

## 2. Windows SmartScreen: "Windows protected your PC"

On first run Windows may show a purple dialog:

> **Windows protected your PC**  
> Microsoft Defender SmartScreen prevented an unrecognized app from starting.

This happens because TGM Pro is **new and not code-signed**, so Windows has no reputation for it yet.

To run it:

1. Click **More info**.  
2. Click **Run anyway**.

If you downloaded TGM Pro from the official GitHub Releases page, this is expected and safe.

---

## 3. Antivirus flags the app

Some antivirus tools may warn about any new unsigned executable.

- Allow / trust the file if you downloaded it from the official link.  
- Then run `TGM Pro.exe` again from the extracted `TGM Pro` folder.

TGM Pro does **not** install drivers or system services; it is a normal user‑mode desktop application.

---

## 4. App doesn't start or closes immediately

If you double-click `TGM Pro.exe` and nothing appears:

1. Make sure you **extracted** `TGM Pro.zip` and are running `TGM Pro.exe` from the extracted **folder**, not directly from inside the ZIP.  
2. Ensure you did **not move or delete** the `_internal` folder next to `TGM Pro.exe`.  
3. Temporarily disable overly aggressive antivirus and try again.  
4. If it still fails, contact support with:  
   - Your Windows version (e.g. Windows 11 64‑bit)  
   - Any error message you see

---

## 5. License key issues

- **"Invalid license key"** – check for typos and extra spaces when pasting.  
- **"License already used on another machine"** – contact the seller to move or reset your license.  
- If activation fails repeatedly, send the seller:  
  - The key you used  
  - Your machine ID (shown on the license screen or by the seller's request)

---

## 6. Support

If you still have trouble after following these steps, contact:

- Telegram: `<your Telegram @handle>`  
- Email: `<your-email@example.com>`

Replace the placeholders with your real contact details before publishing.
