---

# Go CLI Reminder


## Overview

The Go CLI Reminder is a command-line tool that enables you to schedule and receive reminders at specific times. It uses natural language time parsing to make setting reminders a breeze.

## Features

- Schedule reminders using "hh:mm" time format.
- Easy-to-use command-line interface.
- Desktop notifications to alert you when it's time.
- Set multiple reminders, they will display one by one.

## Usage

1. **Installation**: Clone this repository and build the Go program using `go build`.

2. **Set a Reminder**:
   ```bash
   ./GoCLIReminder <hh:mm> <text message>
   ```

3. **Examples**:
   ```bash
   ./GoCLIReminder 15:30 "Call Mom"
   ./GoCLIReminder 09:00 "Meeting with the Team"
   ```

4. **Running in the Background**:
   - Reminders will be displayed as desktop notifications when the scheduled time arrives.

5. **Multiple Reminders**:
   - You can set multiple reminders, and they will be shown one after the other.

6. **Note**: Ensure that you have the required dependencies mentioned in the code.

## Dependencies

- Go (Golang)
- External Go packages (specified in `import` statements)
- Desktop environment for notifications (Linux, macOS, or Windows)

## Contributions

Contributions are welcome! If you'd like to enhance this project, feel free to fork and submit pull requests.

