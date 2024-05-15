# GeoWake

GeoWake is an IoT alarm clock with geofencing capabilities with future plans using a Raspberry Pi and an e-ink display. - This is also my first ever project, so be nice :p

## Features
- Set an alarm to wake you up.
- Uses geofencing to disable the alarm when you are not at home.
- Displays time and alarm status on an e-ink display.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/yourusername/GeoWake.git`
2. Navigate to the directory: `cd GeoWake`
3. Create a virtual environment: `python -m venv env`
4. Activate the virtual environment: `source env/bin/activate` (on Windows: `.\env\Scripts\activate`)
5. Install the dependencies: `pip install -r requirements.txt`

## Running the Project
Run the main script:
```sh
python alarm_clock.py