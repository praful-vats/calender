# Minimalist Calendar

A sleek, full-screen calendar web application featuring a minimalist design with real-time clock display.

## Features

- **Clean, Minimalist Interface**: Large typography and minimal visual elements for distraction-free planning
- **Real-time Clock**: Always displays the current time at the top of the calendar
- **Event Management**: Add, view, and delete events with color categorization
- **Color Coding**: Events can be categorized with red, yellow, or blue indicators
- **Responsive Design**: Works on desktop and mobile devices
- **Persistent Storage**: Events are saved to local storage and persist between sessions
- **Month Navigation**: Easily switch between months

## Usage

### Viewing the Calendar

- The current month is displayed by default
- Days with events show colored dots corresponding to event categories
- The current day is highlighted with a light blue background
- Use the < and > buttons to navigate between months

### Managing Events

- Click on any day to view events for that day
- Click the ⨁ button in the bottom left to add a new event
- When viewing events, click "Add New Event" to add more events to the selected day
- Events can be deleted from the event view modal

### Event Categories

Events can be categorized using three colors:
- **Red**: High priority events or important deadlines
- **Yellow**: Medium priority events or personal appointments
- **Blue**: Low priority events or general reminders

## Installation

1. Download all files to a directory on your computer
2. Open `index.html` in any modern web browser

Alternatively, host the files on a web server to access the calendar online.

## Technical Details

- Built with vanilla JavaScript, HTML, and CSS
- No external dependencies or libraries required
- Uses localStorage API for data persistence
- Implements a responsive design that works across devices

## Customization

The calendar can be easily customized by modifying the CSS:

- Change colors in the CSS variables
- Adjust font sizes and spacing
- Modify the event dot colors
- Change the add button appearance

## Browser Compatibility

Works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is available for personal and commercial use.

## Acknowledgements

Design inspired by minimalist calendar applications with a focus on readability and ease of use.