# FarCry 6

This script navigates through in-game menus to the built in benchmarking tool then runs it with the current settings.

## Prerequisites

- Python 3.10+
- FarCry6 installed via Ubisoft Game Launcher

## Output

report.json
- `resolution`: string representing the resolution the test was run at, formatted as "[width]x[heigt]", e.x. `1920x1080`
- `start_time`: number representing a timestamp of the test's start time in milliseconds
- `end_time`: number representing a timestamp of the test's end time in milliseconds
