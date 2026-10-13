# Chemo Fever Card

> ✅ **Wording reviewed by a doctor, Oct 2026.** The card wording (Roman Urdu, اردو and English) was reviewed and approved, with one fix applied (the patient side now names the patient's specific hospital instead of "nearest emergency").

Free, no-server wallet card generator for people on chemotherapy.

- **Patient side** in Roman Urdu, اردو or English: "fever during chemo = emergency, go now, show this card".
- **Emergency-staff side** in English, with a QR code holding the same details as plain text (works with any scanner).
- Everything runs in the browser. No account, no backend, no API. Data is only saved on the device if the user ticks "remember".

## Why this exists

Hospitals in Canada, Australia and the UK already give chemo patients a fever / neutropenia alert card, but these are hospital-specific paper cards or PDFs. This project makes a free, customizable, Urdu-friendly version that a patient or caregiver can fill in and print.

Examples of the hospital cards this is modelled on:

- https://www.lhsc.on.ca/london-regional-cancer-program/febrile-neutropenia-fever-card
- https://monashhealth.org/services/cancer/medical-alert-card-for-neutropenia/

## Important

- The app **does not give medical advice** and has **no default fever threshold**. The patient or caregiver must enter the number their own oncology team gave them (it differs between hospitals).
- **Apni oncology team ki hidayat follow karein — yeh app unka badal nahi.** This card is a reminder of your oncology team's advice; it does not replace it.

## Run

Open `index.html` in a browser, or visit the live site. The QR library (`qrcode.min.js`) is bundled locally, so QR generation works fully offline once the page is loaded.

## Roadmap

- Lock-screen image export (PNG)
- Installable PWA, offline
- More card types (e.g. a discreet HIV medication reminder)

## License

MIT — see `LICENSE`.
