# Fire Alarm Detection System 🔥
 smart fire detection system using [Arduino / Raspberry Pi] that detects fire and alerts users through buzzer and visual indicators. Optionally integrates ML and IoT.

## Features
- Detects fire via flame/gas/smoke sensor
- Triggers buzzer and LED alert
- (Optional) Sends notification using GSM / Firebase
- (Optional) Uses OpenCV + ML for video-based fire detection

## Requirements
- Arduino UNO / Raspberry Pi
- Flame Sensor / MQ-2 / Pi Camera
- Python 3.8+, OpenCV (for Pi version)

## Setup
```bash
pip install -r requirements.txt
python fire_detection.py
