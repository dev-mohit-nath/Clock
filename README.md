# Clock System in C

This repository provides a simple implementation of a clock system in the C programming language. The program displays the current time and allows users to set, update, and view time in a basic text-based interface.

## Features
- Display the current system time.
- Set a custom time manually.
- Simulate time progression.
- Option to display time in 12-hour or 24-hour format.

## Requirements
- A C compiler (e.g., GCC)
- A terminal or command prompt for execution

## Usage

### Clone the Repository
```bash
git clone <repository-url>
cd clock_system_c
```

### Compile the Program
```bash
gcc clock_system.c -o clock_system
```

### Run the Program
```bash
./clock_system
```

## Example Output
```
1. Display Current Time
2. Set Time
3. Simulate Time Progression
4. Exit
Choose an option: 1

Current Time: 14:30:45

1. Display Current Time
2. Set Time
3. Simulate Time Progression
4. Exit
Choose an option: 2

Enter hour (0-23): 15
Enter minute (0-59): 45
Enter second (0-59): 20
Time updated successfully.
```

## File Structure
```
clock_system_c/
├── clock_system.c    # Main source code file
└── README.md         # Documentation
```

## Functions Overview
- **`void display_time()`**: Prints the current time.
- **`void set_time(int hour, int minute, int second)`**: Allows the user to set a custom time.
- **`void simulate_time()`**: Simulates the passage of time.

## Contribution
Feel free to fork this repository, open issues, and submit pull requests to improve the project.

## License
This project is licensed under the MIT License.
