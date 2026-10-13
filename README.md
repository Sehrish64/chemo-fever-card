# Chemo Fever Card

> ⚠️ **WORK IN PROGRESS — review pending.** The card wording (Urdu and English) has **not** yet been reviewed by an oncologist or oncology nurse. Do not promote this to patients until that review is done.

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
- Before sharing the card wording, have it reviewed by an oncologist or oncology nurse.

## Run

Open `index.html` in a browser. The QR library loads from cdnjs; to work fully offline, download `qrcode.min.js` (qrcode-generator 1.4.4), put it next to `index.html` and change the `<script src>`.

## Roadmap

- Lock-screen image export (PNG)
- Installable PWA, offline
- Reviewed Urdu wording with a Pakistani oncology nurse
- More card types (e.g. a discreet HIV medication reminder)

## License

MIT (add a LICENSE file).
