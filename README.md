# Geolocation API Test

A simple frontend project to test the browser's Geolocation API.

## How to Use

1. Open `index.html` in your web browser
2. Click the "Get My Location" button
3. Allow location access when prompted
4. Your location coordinates and details will be displayed

## Features

- Gets your current location using the browser's Geolocation API
- Displays latitude, longitude, accuracy, altitude, heading, speed, and timestamp
- Shows helpful error messages if location access is denied or unavailable

## Requirements

- A modern web browser with Geolocation API support
- Location services enabled on your device
- Permission to access location (will be requested by the browser)

## Notes

- This requires HTTPS or localhost to work properly (browsers restrict geolocation on insecure connections)
- If testing locally, you can simply open the file directly in your browser
- For production use, serve the file over HTTPS
