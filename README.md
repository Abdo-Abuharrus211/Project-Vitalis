# Project Vitalis
A terminal-based stats monitor for your PC built in Go, using [Bubble Tea](https://github.com/charmbracelet/bubbletea) and [gopsutil](https://github.com/shirou/gopsutil) .

![thumbnail](thumbnail.png?raw=true)

## Idea
There are plenty of system monitors out there, several that are terminal-based, including the legendary `btop`.\
But none of these fit my needs and aesthetic, and more importantly, I wanted to build one myself. 
So I built this, to keep an eye out on PC vitals such as CPU usage, memory usage, and disk usage.

## Features
- **System Info**: displays PC name and OS + version
- **CPU Usage Monitoring**: Display real-time CPU usage
- **Memory Usage Monitoring**: Show current memory usage and available memory
- **Disk Usage Monitoring**: Provide details on disk usage and available space
  
#### What's Next?
- **GPU Stats**: Initially, there were blockers related to reading stats from the GPU, so this is a priority
- **UI Overhaul**: While the current UI is simple and clean, I think there's room for a more dynamic design
- **Cross-Platform**: Currently only tested on Linux, I'd like to make it compatible with Windows and macOS._// might work on Mac since Unix..._
- **Customizable**: Allow users to customize the display and update intervals
- **Network Activity Monitoring**: Track network upload and download speeds
- Introduce flow animation to progress bars.

## Issues
- The CPU temp readings aren't being read correctly, likely incorrect SensorKey being checked
- Table borders don't align with table background (See thumbnail)

## Instructions
I've yet to build this project as it's still a work in progress...

So to run it: 
1. Navigate to `ProjectVitalis/src/` in your terminal.
2. Enter `go run .`, then the TUI would appear in your terminal.

## License
This project is licensed under the MIT License. See the [License](/license.txt) file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgements
Special thanks to the authors of [Bubble Tea](https://github.com/charmbracelet/bubbletea), [Bubbles](https://github.com/charmbracelet/bubbles?tab=readme-ov-file), [Lip Gloss](https://github.com/charmbracelet/lipgloss), and [gopsutil](https://github.com/shirou/gopsutil) for their amazing libraries.

