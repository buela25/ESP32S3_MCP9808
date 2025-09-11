🌡️ Device Driver Development (MCP9808 Temperature Sensor) with Zephyr RTOS

This project is based on Shawn Hymel’s Zephyr Device Driver Workshop
, with modifications made to the Devicetree overlay to match the MCP9808 sensor's hardware configuration bought from DFrobot.

The entire setup runs in a Docker-based virtual environment, allowing isolated builds and easy development. The firmware is flashed to the target board, and sensor data is visualized through the local serial console.

📁 You can find the source code in:
workspace/apps/read_temp
