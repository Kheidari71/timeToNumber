# Time Calculator

A beautiful web application to calculate total hours from multiple time periods.

## Features

- **Multiple Time Entries**: Add as many time periods as you need
- **Precise Calculations**: Calculates exact hours with decimal points
- **Modern UI**: Beautiful, responsive design with smooth animations
- **Easy to Use**: Simple input fields for hours and minutes
- **Real-time Results**: Instant calculation with detailed breakdown

## How to Use

1. **Open the Application**: Double-click on `index.html` to open it in your web browser

2. **Add Time Entries**: 
   - The app starts with one time entry
   - Click the green "Add Time Entry" button to add more entries
   - Each entry has start time and end time fields

3. **Enter Times**:
   - Use the format HH:MM (hours:minutes)
   - For example: 7:21 means 7 hours and 21 minutes
   - 9:49 means 9 hours and 49 minutes

4. **Calculate Total**:
   - Click the "Calculate Total Hours" button
   - View the result with decimal precision (e.g., 17.166 hours)

## Example Calculation

Using your example:
- Entry 1: 7:21 to 9:49
- Calculation: (9-7) hours + (49-21) minutes = 2 hours + 28 minutes = 2.467 hours

## Features

- **Add/Remove Entries**: Use the + button to add more time periods, × to remove
- **Overnight Support**: Handles time periods that span midnight
- **Detailed Breakdown**: Shows individual entry calculations
- **Responsive Design**: Works on desktop and mobile devices

## Technical Details

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Works offline
- Cross-browser compatible

## Usage Tips

- Enter times in 24-hour format
- Minutes should be between 0-59
- Hours should be between 0-23
- Empty fields are treated as 0
- The app automatically handles minute overflow (converts 70 minutes to 1 hour 10 minutes) 