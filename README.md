# Digital Clock and Calendar

A responsive digital clock and calendar built using HTML, CSS, and JavaScript. This project displays the current time, date, and day of the week. It updates the time every second, ensuring users see the exact time with a clean, user-friendly interface.

![image](https://github.com/user-attachments/assets/f7516120-0c8d-46cb-b3ed-c2c8db482605)

## Features

- **Real-Time Clock**: Displays the current hour, minutes, and seconds, updating every second.
- **Date and Day Display**: Shows the current date, day of the week, month, and year.
- **Responsive Design**: Works well on both desktop and mobile devices.
- **User-Friendly Interface**: Organized layout with a sleek design for easy reading.

## Technologies Used

- **HTML5**: Structure of the digital clock and calendar layout.
- **CSS3**: Styling and layout adjustments, including responsive design.
- **JavaScript**: Handles real-time updates for clock and calendar.

## File Structure

- `index.html`: HTML structure of the clock and calendar.
- `styles.css`: Contains all CSS styles for layout and design.
- `script.js`: JavaScript code for updating time and date.

## How It Works

1. **Clock**: 
   - The JavaScript function updates every second using `setInterval`.
   - `getHours()`, `getMinutes()`, and `getSeconds()` methods from the `Date` object are used to display the current time in `HH:MM:SS` format.
   - Leading zeros are added to single-digit hours, minutes, and seconds for consistency.

2. **Calendar**:
   - The calendar section retrieves the current date, day, month, and year using the `Date` object.
   - Arrays for weekdays and months are used to display the day and month names.
   - Leading zeroes are added for single-digit dates.

To view 
