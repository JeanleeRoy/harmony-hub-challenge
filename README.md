# Harmony Hub: ES6+ Syntax Demo

A digital music studio application showcasing modern JavaScript (ES6+) features including rest/spread operators, destructuring, template literals, and default parameters.

## About

Harmony Hub is a demonstration of ES6+ features applied to audio processing and music production functions. The project implements a Digital Audio Workstation interface with various utility functions for managing tracks, playlists, audio effects, and instrument tuning.

## Features

1. **Track Metadata Formatter**
   - Formats track information (title, artist, genres) using template literals and rest parameters
   - Accepts a variable number of genres and generates clean HTML output
   - Example output:
      ```html
      <div class="track-title">Bohemian Rhapsody</div>
      <div class="track-artist">Queen</div>
      <div class="track-genres">Rock, Progressive Rock, Opera Rock</div>
      ```

2. **Playlist Creator**
   - Creates playlists using the spread operator to combine arrays
   - Accepts an existing playlist and any number of new track IDs
   - Returns a new array with all tracks merged

3. **Audio Effect Merger**
   - Merges audio effect configurations using object spread syntax
   - Combines default and custom effect objects
   - Custom effects override default values

4. **Mix Assignment**
   - Assigns mix parameters with default values using object spread
   - Automatically adds `isMuted` property set to false
   - Preserves all original parameters (volume, pan, etc.)

5. **Instrument Tuning Check**
   - Retrieves instrument tuning frequencies using destructuring and default parameters
   - Returns specified instrument frequency or defaults to 440 Hz (standard A4)

## Installation

```bash
npm install
```

## Usage

Start the development server:

```bash
npm run dev
```

Run tests:

```bash
npm test
```

## Preview

![Harmony Hub DAW Interface](https://raw.githubusercontent.com/JavaScript-Certification/images/refs/heads/main/images/training/7-1/harmony-hub.jpg)

## Technologies

- JavaScript ES6+
- Vite
- Tailwind CSS
- Vitest
