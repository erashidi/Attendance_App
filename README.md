# Attendance App

A Python desktop application designed to streamline classroom attendance tracking.

## Screenshot

![Attendance App](assets/attendance_app.png)

## What It Does

The application loads a class roster from an Excel file and displays students one at a time for attendance entry.

## Features

- Load a class roster from Excel
- Display students one at a time
- Record attendance with keyboard shortcuts
- Go back to correct the previous student
- Save attendance back to the roster
- Automatically create a column for today's date

## Attendance Controls

- `1` = Present
- `0` = Absent
- `-` = Present but not following

## How to Run

1. Create and activate a virtual environment
2. Install dependencies:

   pip install -r requirements.txt

3. Run:

   python attendance_app.py

## Download

A standalone Windows executable is available under the repository's **Releases** section.

Download `attendance_app.exe` and run it directly. Python is not required.

## Sample Roster Format

The app expects an Excel file with student names in the first two columns:

| First Name | Last Name |
|------------|-----------|
| Maya       | Chen      |
| David      | Smith     |

A fake sample roster is included in this repository as:

`Fake_Random_Names.xlsx`

## Run from Source

1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies:

   `pip install -r requirements.txt`

4. Run:

   `python attendance_app.py`