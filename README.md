# WhatsApp Chat Stats (מי חופר)

A simple, private web app that shows who talks the most in a WhatsApp group.
Upload an exported chat and get a report for every participant.

**Live app:** https://gosagi-dev.github.io/whatsapp-chat-stats/

## Features

- Message count and percentage for each participant
- Who starts conversations (set the gap between conversations: 1, 3, 6, 12 or 24 hours)
- Filter by period: last 30 days, 3 months, 12 months, or a single year
- Activity by month: a chart and a heat map of the top participants
- More stats: busiest hours, fastest to reply, most photos and files, most used words
- Rename or hide participants before you export
- Export the report as a PDF or an image, or share the image
- Works with iPhone and Android exports (`.txt` or `.zip`)
- Ignores WhatsApp system messages (group name, "You", encryption notice)
- Languages: English (default), Hebrew, Spanish, French, Russian, Arabic
- Light and dark mode, works on phones, can be added to the home screen

## How to use

1. In WhatsApp, open the group and choose **Export chat** (without media).
2. Open the app and upload the `.txt` or `.zip` file.
3. Rename or hide participants if you want.
4. Save the report as a PDF or an image.

## Privacy

Everything runs in your browser. The chat file is never uploaded to any server.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app (HTML, CSS and JavaScript) |
| `jszip.min.js` | Reads `.zip` exports |
| `manifest.webmanifest`, `icon-*.png` | Home screen install |

## Run locally

Open `index.html` in a browser. No build step is needed.

## License

MIT License. Copyright © 2026 gosagi-dev. See [LICENSE](LICENSE).
