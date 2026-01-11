# LiftCard

**LiftCard** is a local-first Chrome extension for trainers and coaches to create professional workout cards, export clean A4 PDFs, share client checklists, and import session reports — all without accounts or servers.

---

## What is LiftCard?

LiftCard solves a very specific problem:

> How do you go from **trainer → client → feedback** using simple, reliable files instead of apps, logins, or subscriptions?

LiftCard uses **print-ready PDFs** and **standalone HTML files** to keep everything fast, private, and under your control.

---

## Key Features

### 📝 Trainer Editor
- Single-screen workout builder
- Exercises, sets × reps, rest, RIR, notes, alternatives
- Clean, minimal UI
- Local autosave (no accounts)

### 📄 A4 Workout PDF
- Professional print layout
- Designed for pen + paper
- Clear exercise instructions
- Dedicated space for load and notes
- Export via browser print (maximum compatibility)

### 📦 Client Pack (HTML)
- Standalone file (no extension required)
- Mobile-friendly checklist
- Autosave progress locally
- Works offline on any device

### 📊 Report Pack Import
- Client exports a report as HTML
- Trainer imports it back into LiftCard
- Clear session summary
- WhatsApp-ready text copy

---

## Philosophy

LiftCard follows a few non-negotiable principles:

- **Local-first**: everything runs on your device
- **No servers**: nothing to maintain, nothing to break
- **No accounts**: no friction for trainers or clients
- **Files over platforms**: PDFs and HTML you actually own
- **Chrome 2022+ compatible** (Manifest V3, plain JavaScript)

---

## Who is this for?

- Personal trainers
- Strength coaches
- CrossFit coaches
- Small gyms
- Freelance fitness professionals
- Coaches who want simple, professional tools

---

## Technical Notes

- Chrome Extension (Manifest V3)
- Plain JavaScript (no frameworks)
- No external dependencies
- PDF export via native browser print
- HTML standalone files for client sharing

---

## Limitations (by design)

- WhatsApp does not allow automatic file attachments from browsers  
  → LiftCard opens the chat with a prefilled message; file attachment is manual.
- PDF generation uses browser print for maximum reliability and compatibility.

---

## Privacy

LiftCard does not track users.
There is no analytics, no telemetry, and no data collection.

See [`PRIVACY.md`](./PRIVACY.md) for details.

---

## Status

LiftCard is actively developed.
The codebase is intentionally small, readable, and hackable.

Suggestions and contributions are welcome.

---

## License

MIT License
