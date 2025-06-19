# Digital-Clock
This project is a real-time digital clock application developed in C that displays the current system time and date in the terminal. 
It continuously updates every second, providing a live view of the time alongside the full date. 
The program gives users the option to choose between two time formats: 24-hour or 12-hour (AM/PM), with the 12-hour format set as the default. 
Once the preferred format is selected, the clock runs in an infinite loop, clearing the screen on each iteration to display the refreshed time and date cleanly.
The implementation leverages standard C libraries such as `<time.h>` for retrieving and formatting system time, and `<unistd.h>` to pause execution for one second between updates. 
The code is modular, with separate functions handling screen clearing, time formatting, and date formatting. 
The `clear_screen()` function uses preprocessor directives to support both Windows and Unix-based systems, enhancing the program's portability. 
The use of `strftime()` allows for flexible and readable formatting of both time and date. 
This project is a practical example of working with time-related functions in C and demonstrates how to create a responsive, user-interactive terminal utility.
