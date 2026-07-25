[README.md](https://github.com/user-attachments/files/30368894/README.md)
# SHIFT//SYNTH Staffing Scheduler V3

This version keeps the retro vaporwave look while making the interface easier to read.

## Main changes

• Larger standard text and stronger contrast
• Fewer glow effects and no moving panel effects
• Simpler buttons, cards, schedule rows, and staffing blocks
• Employee Number is now the required employee identifier
• Names are optional and are only shown as a secondary note
• Timeline rows and schedule labels use employee numbers
• Excel and CSV imports can use Employee Number, Employee ID, Badge Number, Number, or ID
• Import merging matches employees by number rather than by name
• Older saved data is migrated so it can still open

## Spreadsheet import

The easiest spreadsheet layout uses these columns:

Employee Number | Optional Name | Shift | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday | Sunday

The Optional Name column can be completely blank or left out.

Weekday cells may contain values such as:

• 6:00 AM-2:00 PM
• 6a-2p
• 0600-1400
• OFF

The included `schedule_import_template_v3.xlsx` file is ready to use.

## Run the app

Open `SHIFT_SYNTH_SCHEDULER_V3.html` or `index.html` in a modern browser.

The current draft and saved versions are stored in that browser. Use Export Backup to save a portable JSON backup.
