# timebox.sh
This is a macOS command line timer that will continuously send a Notification
Center notifications when the specified duration passes until you clear it.

*This is a personal tool that is lacking polish.*

### A timer? Why?
It's surprisingly difficult to find a timer for macOS that:
- Lets you easily set arbitrary durations
- Is not resource intensive
- Displays a notification when the timer completes
- The notification ^ cannot be cleared without user intervention (e.g. for when
  you keep working even after the timer ends)

If only the timer app that exists on all smartphones worked on computers too,
huh? :)

## Usage:
Clone the app and add it to your PATH, e.g.:
```sh
# cd to the dir you want to clone into...
git clone https://github.com/mcomella/timebox.sh
ln -s timebox.sh/timebox ~/bin/timebox # Assumes ~/bin is in your PATH
```

Then run it:
```sh
timebox <duration-minutes>
```

To stop the timer, whether in progress or completed, type `ctrl+c` in the
terminal.
