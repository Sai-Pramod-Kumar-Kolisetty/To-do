# To-Do App

A simple browser-based to-do list built with plain HTML, CSS, and JavaScript.

## Overview

This app lets users add, complete, edit, and delete tasks. Tasks are stored in browser `localStorage`, so they remain available after refreshing the page.

## Features

- Add new tasks using the input field and plus button
- Mark tasks as completed with a custom checkbox
- Edit existing task text inline
- Delete tasks
- Filter tasks by:
  - All
  - Active
  - Completed
- Clear all completed tasks
- Persistent task storage using `localStorage`
- Responsive dark-themed UI with animated task entry

## How to Use

1. Open `index.html` in your browser.
2. Type a task in the input field.
3. Click `+` or press `Enter` to add the task.
4. Click the checkbox to toggle completion.
5. Use the `Edit` button to change a task.
6. Use the `Delete` button to remove a task.
7. Click filter buttons to show `All`, `Active`, or `Completed` tasks.
8. Click `Clear completed` to remove all finished tasks.

## Implementation Details

- `index.html` contains the full app markup, styles, and script in one file.
- CSS styles create a polished card-based layout with modern dark gradient colors.
- JavaScript handles:
  - task creation
  - state management
  - rendering filtered lists
  - edit, delete, and toggle actions
  - localStorage persistence

## File

- `index.html` — single-file app with HTML, CSS, and JavaScript

## Notes

- No build tools or dependencies are required.
- Best viewed in modern browsers with JavaScript enabled.
- Tasks are saved per browser profile and device.
