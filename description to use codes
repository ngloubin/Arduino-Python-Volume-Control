# Arduino Volume Control Project

This project allows you to control the system volume using a potentiometer connected to an Arduino. The Arduino sends the potentiometer values to the computer, which uses Python to adjust the system volume in real-time.

## Serial Port Configuration

In the Python code, you need to specify the serial port where the Arduino (or another microcontroller, such as Adafruit boards) is connected. Depending on the operating system, the port will be different.

### Serial Port Configuration (Linux and Windows)

- **Linux**: The serial port for USB devices is usually `/dev/ttyUSB0`, `/dev/ttyACM0`, etc. To find the correct port, run `ls /dev/tty*` before and after plugging in the device.
  - **Example for Linux**: 
    ```python
    arduino_port = "/dev/ttyUSB0"  # Adjust to the correct port in Linux
    ```

- **Windows**: The serial port on Windows is represented as "COMx", where "x" is the port number (for example, `COM6`, `COM3`).
  - **Example for Windows**: 
    ```python
    arduino_port = "COM6"  # Adjust to the correct port in Windows
    ```
  - **Change Port**: If your Arduino is connected to a different port, simply change the port number to the correct one (for example, `COM3`, `COM4`). You can find the correct port in the **Device Manager**, under "Ports (COM & LPT)".

### Summary

- **Linux**: Set the serial port as `/dev/ttyUSB0` or `/dev/ttyACM0`, depending on your system's configuration.
- **Windows**: Set the serial port as `COMx`, where "x" is the port number (for example, `COM6`).

Make sure to adjust the serial port in the Python code based on where the Arduino or another microcontroller is connected to your system.

## Requirements

- Arduino board
- Potentiometer connected to the Arduino
- Python 3.x
- PyCaw library (for Windows)
