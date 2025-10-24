# ha-medication-reminder

Non-intrusive medication reminder for Home Assistant (negative trigger)

## Prerequisities

- Works with Home Assistant
- Tested on iOS
- Works with any sensor. I bought this one: https://www.amazon.com/dp/B08R9PH4JT

## Usage

Negative trigger for once per day medication. At 8:00 AM, automation will send a push notification if the sensor has not been triggered in the last 2 hours.