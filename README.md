# Roster to Calendar

Convert LMH Emergency Department roster spreadsheets into calendar files you can import into Google Calendar, Apple Calendar, or Outlook.

## How to use

1. Upload your Excel roster file (.xlsx)
2. Select your name from the dropdown
3. Preview your shifts
4. Download as:
   - **Google Calendar CSV** - import via Google Calendar > Settings > Import
   - **.ics file** - open directly with Apple Calendar, Outlook, or any calendar app

## Privacy

All processing happens in your browser. No data is uploaded to any server.

## Supported shift types

| Shift | Time |
|-------|------|
| AM | 7:30 AM - 4:30 PM |
| PM | 3:00 PM - 11:59 PM |
| C/S | 8:00 AM - 6:00 PM |
| AMC | 7:30 AM - 4:30 PM |
| PMC | 3:00 PM - 11:59 PM |
| N | 9:00 PM - 7:30 AM (+1) |
| S10 | 10:00 AM - 7:00 PM |
| P12 | 12:00 PM - 9:00 PM |
| A10 / A10P | 10:00 AM - 7:00 PM |
| A9 | 9:00 AM - 6:00 PM |
| A7 / A7T | 7:00 AM - 4:00 PM |
| A8C/S | 8:00 AM - 6:00 PM |
| A8T | 8:00 AM - 5:00 PM |
| P1 | 1:00 PM - 10:00 PM |
| P2 / P2SIC | 2:00 PM - 11:00 PM |
| AL, PDL, ML, LSL, RDO, etc. | All day |

Unrecognised shift codes are included as all-day events.

## Hosting

This is a single `index.html` file with no dependencies to install. To host it:

1. Push to a GitHub repository
2. Go to Settings > Pages > set source to `main` branch
3. Share the link with your colleagues

## License

MIT
