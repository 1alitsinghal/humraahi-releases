# Humraahi public demo

Version 0.1.2-demo (Android version code 2).

Download both signed APKs from https://github.com/1alitsinghal/humraahi-releases/releases/latest

- Customer: choose a Demo stand, order, track, show QR, then make a Razorpay TEST payment.
- Vendor: sign in, select the same stand, go online, claim, walk to the customer and scan the QR. No vendor bot.
- Code: 123456 after requesting an OTP for any valid phone. One phone may have both demo roles.
- Throwaway data; do not enter personal or sensitive information. Data resets daily; sign in again after reset.
- Internet required. Free backend may take about a minute to wake; retry if needed. No laptop or Metro required.
- Browsing needs no location permission; ordering/handover still need fresh accurate GPS. Demo handover radius: 500 m.
- Test payments only: use Razorpay test checkout details; never enter real payment credentials.
- Android may ask to allow installation from your browser. These APKs are distributed outside Google Play.
- Existing developer/debug installations use a different signing key: uninstall those first (clears local app data). Later demo updates use this same signing key.

The source repository is private. This repository contains distribution files only.

SHA-256:

```text
63b67a9e7a7a416ccb4f0dd58b56d781cb3dab77b6b1e4fb37d69a7d6a4410c8  humraahi-customer-demo.apk
f049e271316eac27f58a896c0bc376da11e3a7cc3c50f48d7cadabd90891a95b  humraahi-vendor-demo.apk
```
