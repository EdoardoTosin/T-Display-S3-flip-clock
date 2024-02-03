# flip-clock for T-Display-S3

Forked from [GitHub - MakersFunDuck/T-Display-S3-flip-clock-](https://github.com/MakersFunDuck/T-Display-S3-flip-clock-)

## Requirements

- T-Display-S3 (device)

- Arduino IDE (or PlatformIO)

- Modified libraries from [T-Display-S3/lib](https://github.com/Xinyuan-LilyGO/T-Display-S3/tree/main/lib) needs to be copied inside `Arduino/libraries`

## How to

1. **Clone Repository**
   
   Clone the repository with the following command:
   
   ```sh
   git clone https://github.com/EdoardoTosin/T-Display-S3-flip-clock
   ```

2. **Create Secrets File**
   
   Create a file named `arduino_secrets.h` in the root directory of your project. Add the following code to this file:
   
   ```c
   #define WIFI_SSID                    "your_ssid"
   #define WIFI_PASSWORLD               "your_password"
   ```
   
   Replace `your_ssid` and `your_password` with your actual WiFi ssid and password.

2. **Upload Sketch**
   
   After setting up the secrets file, you can now upload the sketch to your Arduino device.
