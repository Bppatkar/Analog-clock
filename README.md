# Analog-clock with JavaScript 🕒 [Live](https://bppatkar.github.io/Analog-clock/)

A simple analog clock built using **JavaScript**, **HTML**, and **CSS**. The clock dynamically updates in real-time, showcasing the positions of the hour, minute, and second hands. This project demonstrates the use of CSS for styling and JavaScript for logic to simulate an analog clock.

---

## Features
- **Real-Time Functionality**: The clock updates every second to reflect the current time accurately.
- **CSS Styling**: A clean and modern design with a circular clock face and hour indicators (12, 3, 6, 9).
- **Dynamic Hands**:
  - Hour hand updates smoothly.
  - Minute hand adjusts incrementally with seconds.
  - Second hand moves precisely every second.

---

## How It Works
1. **HTML Structure**:
   - A `div` structure represents the clock face and hands (hour, minute, second).
   - Indicators for 12, 3, 6, and 9 are positioned accurately.

2. **CSS Styling**:
   - Styles for the clock face, hands, and center pivot.
   - Smooth rotations using `transform-origin` for realistic movement.

3. **JavaScript Logic**:
   - Retrieves the current time using `Date()` object.
   - Calculates the angles for each hand based on the current time:
     - Seconds → 360° divided into 60 parts (6° per second).
     - Minutes → 360° divided into 60 parts (6° per minute).
     - Hours → 360° divided into 12 parts (30° per hour).
   - Updates the positions using `setInterval()` to animate the rotation of the hands.

---

## Project Structure
- **HTML**: Defines the structure of the clock, including the hands and face.
- **CSS**: Styles the clock face, center point, and hand movements.
- **JavaScript**: Handles the logic for updating the hand positions in real-time.

---

