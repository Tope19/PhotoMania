# PhotoMania

PhotoMania is a simple and delightful iOS app built with SwiftUI. The app allows users to fetch random images from an online source with the tap of a button. Designed with simplicity and a clean user interface, PhotoMania is perfect for those moments when you need inspiration or just want to explore random visuals.

## Features

- **Fetch Random Images**: Retrieve a new random image with a single tap.
- **SwiftUI Design**: Built with a modern and responsive SwiftUI layout.
- **Smooth User Experience**: Asynchronous image fetching ensures the app remains responsive.

## Screenshots

> *(Include screenshots of the app here, such as the default view and a loaded random image view.)*

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Tope19/PhotoMania.git
   ```
2. Open the project in Xcode:
   ```bash
   cd PhotoMania
   open PhotoMania.xcodeproj
   ```
3. Ensure you have Xcode 15.0 or later installed.
4. Build and run the app on your simulator or connected device.

## How It Works

1. On launch, the app displays a placeholder image.
2. Tap the "New Image" button to fetch a random image from the internet.
3. The app fetches the image asynchronously and displays it in a styled container.

## Technology Stack

- **SwiftUI**: For building declarative and responsive user interfaces.
- **URLSession**: To fetch images from an online source.
- **Combine**: For state management with `@StateObject` and `@Published`.

## File Structure

```
PhotoMania/
├── PhotoManiaApp.swift        // App entry point
├── ContentView.swift          // Main UI and logic
└── Assets.xcassets            // Image assets
```

## Future Enhancements

- Add a loading indicator while fetching images.
- Include options to save fetched images to the device.
- Allow users to specify dimensions for the random image.
- Support sharing images directly from the app.

## Contribution

Contributions are welcome! If you'd like to add a feature or fix an issue:

1. Fork this repository.
2. Create a new branch for your changes.
3. Open a pull request with your updates.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
