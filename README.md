# Stopwatch

A simple, elegant, and functional stopwatch web application built with HTML, CSS, and JavaScript.

## Features

- **Start/Stop Functionality**: Easily start and pause the stopwatch
- **Reset**: Clear the timer and return to 00:00:00:00
- **High Precision**: Displays time in hours:minutes:seconds:centiseconds
- **Responsive Design**: Beautiful frosted glass UI with gradient background
- **Smooth Animations**: Hover effects on buttons for better user experience
- **Real-time Updates**: Updates every 10 milliseconds for accuracy

## Project Structure

```
STOPWATCH/
├── index.html      # HTML structure
├── index.js        # JavaScript logic
├── style.css       # Styling and animations
└── README.md       # Documentation
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Gradient backgrounds, backdrop filters, and transitions
- **JavaScript (ES6)**: Timer logic and DOM manipulation

## How to Use

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. **Click Buttons**:
   - **Start**: Begin the stopwatch
   - **Stop**: Pause the stopwatch
   - **Reset**: Clear the timer and return to 00:00:00:00

## Features Breakdown

### Styling
- Gradient background (blue tones)
- Frosted glass container effect with blur and transparency
- Color-coded buttons:
  - Green: Start
  - Red: Stop
  - Blue: Reset
- Responsive hover effects for better UX

### JavaScript Logic
- `start()`: Initiates the timer if not already running
- `stop()`: Pauses the timer and stores elapsed time
- `reset()`: Clears all values and resets display
- `update()`: Calculates and displays time in real-time

## Time Display Format

The stopwatch displays time as: **HH:MM:SS:CS**
- HH: Hours (00-23)
- MM: Minutes (00-59)
- SS: Seconds (00-59)
- CS: Centiseconds (00-99)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- [ ] Lap time functionality
- [ ] Keyboard shortcuts (spacebar to start/stop)
- [ ] Local storage to save stopwatch history
- [ ] Dark/Light theme toggle
- [ ] Audio notification when timer completes

## License

This project is open source and available for personal and educational use.

## Author

Created as a JavaScript practice project.

---

Feel free to fork, modify, and improve this project!
