# TimeMaster

A simple timer application written in assembly language that simulates a digital clock, displaying hours, minutes, and seconds. This program runs in a DOS environment and supports basic timer operations like start, stop, and reset.

## Features

- **Real-Time Display**: Shows the time in HH:MM:SS format.
- **Commands**: 
  - **S**: Start the timer.
  - **E**: Stop the timer.
  - **R**: Reset the timer to 00:00:00.
- **Exit**: Press ESC to exit the program safely.

## Getting Started

### Prerequisites
- An x86 emulator or a DOS environment (e.g., [DOSBox](https://www.dosbox.com/))
- An assembler (e.g., [NASM](https://www.nasm.us/))

### Running the Program
1. Assemble the code:
   ```bash
   nasm -f bin TimeMaster.asm -o TimeMaster.com
   ```
2. Open the DOS emulator and run the .com file:
   ```bash
   TimeMaster.com
   ```
## How It Works
- The program uses basic assembly operations to increment seconds, minutes, and hours, displaying the time dynamically.
- Custom routines handle the timer commands, input processing, and time conversion.

###Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request with your improvements.

## Author

**[Joseph George](https://github.com/Joseph-George1)**
