<div id="top"></div>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://mapty.netlify.app/">
    <img src="./ImgsAndCharts/logo.png" alt="Logo" height="80"  >
  </a>
  <h1 align="center">Mapty</h1>

  <p align="center">
    <a href="https://mapty.netlify.app/">View Demo</a>
    ·
    <a href="https://github.com/SalahShallapy/Mapty/issues">Report Bug</a>
  </p>
</div>

Mapty is a geolocation-based workout tracking application that allows users to log their running and cycling activities. Built with JavaScript and the Leaflet.js library, it provides an interactive map to record workout details such as distance, duration, pace, and elevation gain. Users can visually track their activities, store data locally, and view a list of all workouts.

<!-- ABOUT THE PROJECT -->

## Project Overview

![mapty preview](./ImgsAndCharts/overview.png)

### Flowchart

<img src='./ImgsAndCharts/Mapty-flowchart.png' alt='flowchart' >

### Architecture

<img src='./ImgsAndCharts/Mapty-architecture-final.png' alt='architecture' >

## Features:

- Display location on map
- Submit workouts on any location on the map
- Select workout type : (running / cycling)
- Logs running and cycling workouts with distance, duration, and optional metrics (cadence or elevation gain).
- Interactive map using Leaflet.js for selecting workout locations.
- Auto-generates workout descriptions based on date and type.
- Displays workouts as markers on the map with detailed popups.
- Renders workout details in a list view with activity icons.
- Animates to specific workout locations on click.
- Stores all workout data in local storage for persistence.

## Usage:

1.  Open the app and allow geolocation access to display your current location.
2.  Click on the map to open the workout form.
3.  Enter workout details:
    - Select type: Running or Cycling.
    - Input distance (km) and duration (min).
    - Optionally input cadence (spm) for running or elevation gain (m) for cycling.
4.  Submit the form to log the workout.
5.  View logged workouts in the list and as markers on the map.
6.  Click on a workout in the list to animate to its location.

## Project Structure

```
Mapty
│      .prettierrc
│      index.html
│      README.md
│      style.css
│      script.js
│
└─── ImgsAndCharts ------> all images
```

## Installation

To get started with the project locally:

1. Clone the repository:
   ```bash
   git clonehttps://github.com/SalahShallapy/Mapty
   ```
2. Open the Project
   Navigate to the project folder and open the index.html file in your preferred web browser to start playing.

3. Requirements
   No additional dependencies are required. The project entirely in the browser using vanilla JavaScript, HTML, CSS and you can view it online using this [demo](https://mapty.netlify.app/)

## Note

- workouts logging page for Cycling and Running using map from [Leaflet library](https://leafletjs.com/SlavaUkraini/index.html)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>
