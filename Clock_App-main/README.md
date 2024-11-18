# Flutter Clock App  

A feature-rich Flutter application that provides clock functionalities, including alarm, timer, stopwatch, and a general clock interface.

## Features  
- **Alarm**: Set and manage alarms with custom tones.  
- **Clock**: Displays the current time with an attractive clock UI.  
- **Timer**: Countdown timers for various tasks.  
- **Stopwatch**: A precise stopwatch for time tracking.  

## Project Structure  

```plaintext
├── assets
│   ├── fonts               # Custom font files
│   ├── add_alarm.png       # Icon for adding alarms
│   ├── alarm_icon.png      # Icon for alarms
│   ├── clock_icon.png      # Icon for the clock
│   ├── stopwatch_icon.png  # Icon for the stopwatch
│   ├── timer_icon.png      # Icon for the timer
│
├── lib
│   ├── constants           # Contains constants used across the app
│   ├── alarm_screen.dart   # UI and logic for the Alarm screen
│   ├── clock_screen.dart   # UI and logic for the Clock screen
│   ├── clock_view.dart     # Reusable clock widget
│   ├── homepage.dart       # Main navigation screen
│   ├── main.dart           # Application entry point
│   ├── stop_watch.dart     # UI and logic for the Stopwatch
│   ├── timer_screen.dart   # UI and logic for the Timer
│
├── test                    # Contains unit and widget tests
├── README.md               # Project documentation
├── analysis_options.yaml   # Linting and analysis rules
├── pubspec.lock            # Locked package dependencies
├── untitled1.iml           # IntelliJ project file
