# Command line Note Taking

## Getting Started

**npm i** to install the relevant dependancies

## basic functionality use

The application is designed to add, remove, list and read short notes. To use the application run 'node app.js' followed by one of the following arguments

1. **add** (add an item to list - takes 2 arguments **title** and **body** )
   _e.g node app.js add --title="Dentist" --body="I have a dentist appointmend next Tuesday at 15:00"_

2. **remove** (removes item from list - takes 1 argument **title**)
   _e.g node app.js remove --title="Dentist"_

3. **list** (lists all items - no arguments required)
   _e.g node app.js list_

4. **read** (will read the body of a specific list item - takes 1 argument **title**)
   _e.g node app.js read --title="Dentist"_
