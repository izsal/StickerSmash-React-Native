# Sticker Smash App

A mobile app that allows users to choose a photo, add stickers, and save the resulting image.

## Features

- Choose a photo from the device's library
- Add stickers to the photo
- Save the resulting image to the device's library
- Reset the photo to its original state
- Use a modal to select stickers

## Requirements

- Expo framework
- React Native
- Expo Image Picker
- Expo Media Library
- React Native Gesture Handler
- Dom-to-image library

## Installation

1. Clone the repository
2. Install dependencies using `npm install` or `yarn install`
3. Start the app using `expo start`

## Usage

1. Open the app and choose a photo from the device's library
2. Add stickers to the photo by selecting them from the modal
3. Save the resulting image to the device's library
4. Reset the photo to its original state by pressing the "Reset" button

## Code Structure

The app is built using React Native and Expo. The code is organized into the following components:

- `App.js`: The main app component
- `components`: A directory containing the following components:
  - `ImageViewer.js`: A component that displays the chosen photo
  - `EmojiSticker.js`: A component that displays a sticker
  - `EmojiPicker.js`: A component that allows the user to select stickers
  - `EmojiList.js`: A component that displays a list of stickers
  - `IconButton.js`: A component that displays an icon button
  - `CircleButton.js`: A component that displays a circular button
  - `Button.js`: A component that displays a button

## Styles

The app uses a dark theme with a black background and white text. The styles are defined in the `styles` object in `App.js`.

## License

This code is licensed under the MIT License.
