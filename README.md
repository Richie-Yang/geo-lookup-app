# Geolocation API Test

A simple frontend project to test the browser's Geolocation API and reverse geocoding.

## How to Use

### Method 1: Get Your Current Location
1. Open `index.html` in your web browser
2. Click the "Get My Location" button
3. Allow location access when prompted
4. Your location coordinates, country name, and address will be displayed

### Method 2: Lookup by Coordinates
1. Enter latitude and longitude values in the input fields
2. Click the "Lookup Country" button
3. The country name and address for those coordinates will be displayed

## Features

- Gets your current location using the browser's Geolocation API
- Displays latitude, longitude, accuracy, altitude, heading, speed, and timestamp
- **Reverse geocoding**: Gets country name and address from latitude/longitude coordinates
- Manual coordinate lookup: Enter any coordinates to get the country name
- Shows helpful error messages if location access is denied or unavailable

## How It Works

The app uses two APIs:
1. **Browser Geolocation API**: Gets your current location coordinates
2. **OpenStreetMap Nominatim API**: Performs reverse geocoding to convert coordinates to country name and address

## Requirements

- A modern web browser with Geolocation API support
- Location services enabled on your device (for "Get My Location" feature)
- Permission to access location (will be requested by the browser)
- Internet connection (for reverse geocoding)

## Notes

- This requires HTTPS or localhost to work properly (browsers restrict geolocation on insecure connections)
- If testing locally, you can simply open the file directly in your browser
- For production use, serve the file over HTTPS
- The reverse geocoding uses OpenStreetMap Nominatim API (free, no API key required)