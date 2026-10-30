# Aquarium Logger

A command-line tool, written in Bash, for logging aquarium water test results and
warning me when a reading is outside a safe range.

## Project Goal

When I test my aquarium water, I only have the numbers from today's test, so I can't
tell whether ammonia is creeping up or nitrates are building toward a water change.
This tool saves every test and flags unsafe readings so problems are caught early,
before they hurt my fish.

## MVP Scope

- Add a reading by entering pH, ammonia, nitrite, nitrate, and temperature
- Validate input so bad values never reach the data file
- Save each reading with a date to `readings.csv`
- Warn when a reading is outside the safe range for a freshwater tank
- View recent readings as a table

## Future Plans (Schedule)

- Trend graphs showing how each parameter changes over time
- Water-change reminders based on nitrate levels and the last water change
- Fish stocking and compatibility checker
- Saltwater and custom safe ranges
- Support for multiple tanks

## Tech Stack

- **Language:** Bash
- **Commands:** `read`, `date`, `awk`, `echo`, `tail`, `column`, `grep`, `sort`
- **Data storage:** plain CSV file (`readings.csv`)
- **Version control:** Git and GitHub
- No external libraries or installs required

## Setup and Usage

*Coming soon. This section will be filled in as the commands are built.*

## Docs

Eisenhower Matrix and system diagram go in the `docs/` folder.
