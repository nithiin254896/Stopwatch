# Stopwatch

A simple, accurate, and responsive stopwatch built using HTML, CSS, and JavaScript. This project provides a functional stopwatch that can start, stop, and reset, displaying the elapsed time in hours, minutes, seconds, and milliseconds.

Features
Start: Begin counting the elapsed time in intervals of 10 milliseconds.
Stop: Halt the stopwatch at its current time.
Reset: Clear the current time and reset the stopwatch to 00:00:00:000.
How It Works
HTML: The structure of the stopwatch interface, including buttons for starting, stopping, and resetting the stopwatch.
CSS: Styling for the stopwatch display and buttons, making the interface clean and user-friendly.
JavaScript: The core functionality, including time calculation, updating the display, and managing the interval timer.
JavaScript Breakdown
Variables:

milliseconds, seconds, minutes, hours: Track the elapsed time.
displaySW: The HTML element where the time is displayed.
timeRef: Holds the reference to the interval timer created by setInterval.
Functions:

updateTime(): Increments the time variables, formats them, and updates the display.
Event listeners for the buttons:
start-btn: Starts the interval timer.
stop-btn: Stops the interval timer.
reset-btn: Stops the interval timer, resets the time variables, and updates the display.
