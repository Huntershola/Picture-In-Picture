# Picture-in-Picture Project

## Description

The Picture-in-Picture Project is a web application that allows users to capture their screen and display it in a small floating window, commonly referred to as picture-in-picture mode. This feature enables users to continue watching a video or participating in a video call while performing other tasks on their computer.

## Key Features

- **Screen Capture:** Users can capture their screen using the browser's native media capture API (`navigator.mediaDevices.getDisplayMedia()`).

- **Picture-in-Picture Mode:** The captured screen is displayed in a small floating window that can be moved and resized, allowing users to watch videos or participate in video calls while multitasking.

- **User Interaction:** The application includes user interface elements such as a button to start screen capture and toggle picture-in-picture mode.

## How It Works

1. **Screen Capture:** When the user clicks on the screen capture button, the application requests permission to capture the user's screen using the `navigator.mediaDevices.getDisplayMedia()` method.

2. **Picture-in-Picture Mode:** After successfully capturing the screen, the application enters picture-in-picture mode by calling `videoElement.requestPictureInPicture()`. This creates a small floating window containing the captured screen.

3. **User Interaction:** The application provides user interface elements to control the screen capture and picture-in-picture mode, such as buttons to start/stop screen capture and toggle picture-in-picture mode.

## Installation

Clone the repository:  https://github.com/Huntershola/Picture-In-Picture.git


Open `index.html` in a web browser to launch the application.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Contributions

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.




