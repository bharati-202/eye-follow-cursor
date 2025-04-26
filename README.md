Eye Follow Cursor

An interactive project where the eyes of a character dynamically follow the cursor's movement in real-time. The eyes smoothly return to their default position when the cursor stops moving or leaves the browser window


Features

Real-Time Eye Movement: The pupils follow the cursor's movement in all directions (up, down, left, right).
Idle Behavior: When the cursor stops moving, the pupils smoothly return to their default position.
Smooth Transition: After being idle, the pupils start moving smoothly before transitioning to immediate movement.
Responsive Design: Works seamlessly across different screen sizes.

Technologies Used

HTML5: For structuring the webpage.
CSS3: For styling the eyes, pupils, and layout.
JavaScript: For implementing the cursor tracking logic and animations.


How It Works

Cursor Movement: The mousemove event tracks the cursor's position.
The pupils calculate their movement based on the angle and distance between the cursor and the center of the eyes.
Idle Detection: A setTimeout detects when the cursor stops moving.
If the cursor is idle for a specified duration, the pupils smoothly return to their default position.
Mouse Leave: The mouseleave event ensures that the pupils return to their default position when the cursor leaves the browser window.

Future Enhancements

Add blinking animations for the character's eyes.
Make the character react to specific areas of the screen (e.g., smile when hovering over a specific element).
Add touch support for mobile devices.


License

This project is open-source and free to use for personal and educational purposes.

