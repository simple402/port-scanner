# Port Scanner

This Python script is a simple port scanner that checks for open ports on a specified target host. It uses multithreading to scan ports concurrently, making the process faster and more efficient.

## Features

- Scans ports from 1 to 65535.
- Uses multithreading for concurrent scanning.
- Displays open ports.
- Handles socket errors and unexpected exceptions.
- Provides a banner with scan details.

## Requirements

- Python 3.x
- `socket` library (included in Python standard library)
- `threading` library (included in Python standard library)

## Usage

To use the port scanner, run the script from the command line with the target hostname or IP address as an argument:

```sh
python scanner.py <target>
