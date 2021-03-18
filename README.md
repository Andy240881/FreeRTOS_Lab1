# FreeRTOS_Lab1
* Must use MultiTask, e.g.  One for LED ,  other for Button.
    * Inter process communication (IPC).
* LED have two state
    * The green LED lights up for 5 seconds, then turns to a red LED lights up for 5 seconds (green LED off), and then switches back to the green LED lights up for 5 seconds (red LED off), and so on.
    * The red LED blinking.
* If the button is pressed, the LED will switch to another state.
    * Debounce.
    * Edge detection.
