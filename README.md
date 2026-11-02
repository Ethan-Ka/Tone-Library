# Tone Library

# Project Goal

I play a lot of songs that each need a different setup across my guitar, pedals, and amp. Remembering where every knob goes is tedious. This project gives me one place to store those settings and pull them up quickly. I pick a song from a sidebar, and a panel shows my whole signal chain set exactly how that song needs it.

# MVP Scope

Version 1 will:

- Store settings for 2+ songs in a JSON file
- Show a sidebar listing all the songs
- Load a song's settings when it is clicked
- Draw SVG knobs rotated to saved values
- Show pedal on/off status
- Show pickup selector position
- Show the pedals in signal chain order


# Future plans

- Customizable and modular pedal display and UI
- A form to add/edit songs in the JSON file
- Saving changes in the browser
- Import/Export JSON files
- Searching songs
- Multiple settings per song (chorus and verse or something)

# Tech Stack

HTML, CSS, JavaScript
JSON 
Python `http.server` 
Google Fonts
JSONLint

# Build Plan
 
1. Set up repo
2. Write the settings data
3. Load the data
4. Build the song sidebar
5. Draw SVGs and UI
6. Render a panel with correct knob positions
7. Connect the sidebar to the UI
8. Polish, finish, and handle edge cases