[README.md](https://github.com/user-attachments/files/30380279/README.md)
# SHIFT//SYNTH Scheduler V5 - Smart Generator Build

A standalone browser scheduler for designing, generating, comparing, importing, and exporting 24/7 staffing plans.

## New in V5

- Smart schedule generator that runs locally in the browser
- Plain language interpreter for common rules such as “9 people work 12s and 9 people work 8s”
- Separate start-time pattern groups with exact employee counts
- Main shift length, days per week, and optional extra short shift hours
- Employee number prefix and starting number controls
- Balanced, weekday, midday, lean weekend, and minimum-first coverage priorities
- Consecutive, balanced, or spread-out workday preferences
- Automatic distribution of days off using a constraint-based optimizer
- Generated drafts open automatically in the Full Week view
- Clean V5 storage starts with a blank draft instead of sample employees

## Generator example

Enter:

`9 people work 12s starting at 6 AM and 6 PM. 9 people work 8s starting at 6 AM, 2 PM, and 10 PM. Keep at least 3 people working. Prioritize noon to 6 PM Monday through Friday.`

Select **Interpret description**, review the generated pattern groups, and select **Generate draft**.

The generator is an on-device rules and optimization engine. It does not send employee or schedule data to an AI service and does not require an API key.

## Existing features

- Employee Number as the unique identifier
- Optional employee names or notes
- Daily timeline and full seven-day schedule views
- Two-hour staffing counts beginning at 6:00 AM
- Excel, CSV, and JSON import
- PDF, Excel, and JSON export
- Saved schedule versions and staffing comparisons

## Run it

Open `SHIFT_SYNTH_SCHEDULER_V5.html` or `index.html` in a modern browser.

Excel and direct PDF operations load browser export libraries from the internet when first used. The smart generator itself works offline.
