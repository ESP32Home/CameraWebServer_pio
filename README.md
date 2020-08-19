# CameraWebServer_pio
The Arduino ESP32 Camera webserver example ported to platformio

# Usage
* copy `wifi_credentials_template.ini` to `wifi_credentials.ini` and update the credentials in the new file
* `pio run` or build from pio Home menu


# Modifications
* Activated the `CAMERA_MODEL_AI_THINKER` define
* moved main Arduino .ino file to `src/main.cpp`
* moved wifi credentials to a gitignored file `wifi_credentials.ini`
