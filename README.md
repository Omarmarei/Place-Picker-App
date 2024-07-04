# PlacePicker App

The PlacePicker app allows users to create and manage a collection of places they want to visit or have visited.

## Technologies Used
- React
- JavaScript

## Hooks Used
- `useState`
- `useRef`
- `useEffect`
- `useCallback`

## Components

### App
The main component managing the application state and rendering other components.

### Places
Renders a list of places with the ability to select or remove them.

### Modal
Manages the visibility of a modal dialog used for delete confirmation.

### DeleteConfirmation
Displays a confirmation message for deleting a place with a progress bar indicating the time remaining before deletion.

### ProgressBar
A reusable component that visualizes a progress bar.

## Features
- Displays available places sorted by distance using geolocation.
- Allows users to add and remove places from their collection.
- Persists selected places using localStorage.

## Developer
- Developed by Omar Marei in 2024 as a project to practice React development techniques.
