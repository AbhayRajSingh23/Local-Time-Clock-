# Your Local Time

This project displays a digital clock that shows the local time of the user's device. The time updates every second to provide an accurate, real-time display. The clock is styled with a modern look using CSS.

## Features

- Real-time local time display.
- Updates every second to show the current time.
- Responsive design with a modern style.

## Technologies Used

- **HTML**: Provides the structure of the webpage.
- **CSS**: Styles the webpage for a clean and modern appearance.
- **JavaScript**: Handles the dynamic updating of the time.

## How to Use

1. Clone or download the project files to your local machine.
2. Open the `index.html` file in any web browser.
3. The current local time of your device will be displayed and updated every second.

## Code Explanation

### JavaScript Code

The JavaScript code selects the element with the ID `clock` and sets an interval to update the inner HTML with the current time every second:

```javascript
const clock = document.getElementById('clock');

setInterval(function () {
  const date = new Date();
  clock.innerHTML = date.toLocaleTimeString();
}, 1000);
```
#[Live Demo](https://abhayrajsingh23.github.io/Local-Time-Clock-/)
