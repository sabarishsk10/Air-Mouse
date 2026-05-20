AirMouse: The Next Generation of Input Devices

The AirMouse is a next-generation input device designed to replace conventional mice, which require a surface to function. Instead, it uses motion sensing to provide a seamless, more intuitive experience.

This project utilizes the MPU6050 sensor to calculate rotation angles and rotational speed using its built-in gyroscope and accelerometer. Required Libraries

To implement this project, the following libraries are needed:

ESP32-BLE-Mouse - https://github.com/sirfragles/ESP32-BLE-Mouse
Adafruit MPU6050 - https://github.com/adafruit/Adafruit_MPU6050
Adafruit BusIO (Dependency) - https://github.com/adafruit/Adafruit_BusIO
Adafruit Unified Sensor Driver (Dependency) - https://github.com/adafruit/Adafruit_Sensor
The first two libraries are directly included in the code, while the latter two are required dependencies.

Enhancements & Features

Kalman Filtering: We have implemented Kalman filtering to smooth noisy sensor data, enhancing accuracy by predicting and correcting measurements.

Button Controls: The device features four buttons for left click, right click, scroll up, and scroll down, making navigation effortless.

Rechargeable Battery: A TP4056 lithium battery charging module has been integrated to enable convenient recharging, making it a fully standalone product.

This innovation eliminates the need for a physical surface, offering a futuristic alternative to traditional mice
