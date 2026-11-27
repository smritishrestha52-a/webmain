# Week 12 – React Effects & useEffect

## GitHub task: Weather Dashboard

This folder contains a complete, GitHub Pages-ready Weather Dashboard for the Week 12 homework.

### Features
- Search by city name using the Open-Meteo Geocoding API.
- Search by latitude and longitude.
- Fetch current temperature, weather description, wind speed, humidity, precipitation and feels-like temperature.
- Loading and error states.
- `useEffect` with a dependency on the search request.
- `AbortController` cleanup to cancel an older request when a new search starts.
- Bonus: browser geolocation with `navigator.geolocation`.
- Responsive layout.

## Publish
1. Upload this folder as `week12` in the existing `webmain` repository.
2. Commit the changes to `main`.
3. Open `https://smritishrestha52-a.github.io/webmain/week12/`.

The page uses React 18 and Babel from CDNs, so no npm installation or build step is needed for GitHub Pages.
