# Event Management System

## Project Overview

The **Event Management System** is a Python-based application designed to manage events chronologically, allowing users to add, delete, and view events based on their scheduled dates. A custom binary heap data structure is implemented to prioritize events by date, ensuring efficient management and retrieval. This project avoids using built-in priority queues or heaps, following the assignment’s guidelines for custom ADT (Abstract Data Type) implementations.

## Features

- **Add Event**: Add an event with a specific name and date.
- **Delete Event**: Delete an event by name.
- **View Events**: Display all events in chronological order.
- **Custom Binary Heap**: Implements a priority queue for efficient date-based sorting without relying on built-in Python ADTs.

## Requirements

- **Python 3.x**: This project was developed and tested on Python 3.x. Ensure Python 3.x is installed.
- **IDE/Editor**: The code was written in PyCharm but is compatible with other Python editors such as VS Code, Jupyter Notebook, or a text editor with Python support.

## Usage Instructions

1. **Run the Program**: Execute the main script to start the application.
   ```bash
   python main.py

## Example Usage

When you run the program, you will see a menu like this:

Event Management System
1. Add Event
2. Delete Event
3. View Events
4. Exit
Enter your choice: 1

Enter event name: Meeting
Enter event date (YYYY-MM-DD): 2023-11-15
Event 'Meeting' added.
## Testing

Unit tests are provided to validate each functionality:

1. Navigate to the `tests` directory.
2. Run the test file:
   ```bash
   python -m unittest test_event_manager.py
## Future Improvements

- **GUI Interface**: Add a graphical user interface for improved user experience, making it easier for users to interact with the application.
  
- **Recurring Events**: Implement support for recurring events, allowing users to schedule events that repeat on a daily, weekly, or monthly basis.

- **Event Notifications**: Include reminders for upcoming events, helping users stay informed and prepared for their scheduled activities.
