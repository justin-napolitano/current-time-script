# Current Time Script

A simple Bash script that outputs the current date and time in ISO 8601 format including timezone offset. This utility provides a consistent timestamp format useful for logging, scripting, or any automation requiring a standardized date-time string.

## Features

- Outputs current date and time in the format: `YYYY-MM-DDTHH:MM:SS±HH:MM`
- Uses standard Bash and the Unix `date` command
- Lightweight and easy to integrate into other scripts or workflows

## Tech Stack

- Shell scripting (Bash)
- Unix `date` command

## Getting Started

### Prerequisites

- Bash shell
- `date` command (available on most Unix-like systems)

### Installation

Clone or download the repository, then save the script file `current_time.sh` to your local machine.

### Usage

Make the script executable:

```bash
chmod +x current_time.sh
```

Run the script:

```bash
./current_time.sh
```

Example output:

```
date = "2024-07-13T14:27:45-06:00"
```

## Project Structure

- `current-time.sh` - The main Bash script that outputs the current time.
- `README.md` - This readme file.
- `index.md` - Additional documentation with usage and metadata.

## Future Work / Roadmap

- Add support for different output formats (e.g., UTC, Unix timestamp).
- Include options to customize output via command-line arguments.
- Improve portability across different Unix-like systems and shells.
- Add automated tests to verify output format consistency.

---

This project is provided as-is without warranty. You may modify and use it as needed.
