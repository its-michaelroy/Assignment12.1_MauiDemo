# .NET MAUI Demo Project (Walkthrough Guide from Microsoft)

Welcome to the .NET MAUI Demo Project! This application demonstrates the capabilities of .NET Multi-platform App UI (.NET MAUI) for building cross-platform applications that run seamlessly on Android, iOS, macOS, Windows, and Tizen.

## Features

- **Cross-Platform Support**: Build once, deploy on Android, iOS, macOS (Catalyst), Windows (WinUI), and Tizen.
- **Responsive UI**: Leverages XAML for responsive and adaptive layouts.
- **Single Project Structure**: Showcases a unified project structure for targeting multiple platforms.
- **Custom Styling**: Includes reusable styles and themes defined in XAML resource dictionaries.
- **Interactive Controls**: Implements basic UI elements like buttons, labels, and event handlers.

## Getting Started

### Prerequisites

To build and run this project, ensure you have the following:

- **Visual Studio 2022** with the .NET Multi-platform App UI development workload installed.
- **.NET SDK 8.0** or higher.

### Building and Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/its-michaelroy2/Assignment12.1_MauiDemo_.git
   ```
2. **Open the Solution**:
   - Navigate to the project directory.
   - Open `Assignment12.1_MauiDemo_.sln` with Visual Studio 2022.

3. **Set the Startup Project**:
   - Ensure that `Assignment12.1_MauiDemo_` is set as the startup project.

4. **Choose a Target Platform**:
   - Use the toolbar to select a platform (e.g., Android Emulator, Windows Machine, or iOS Simulator).

5. **Build and Run**:
   - Press `F5` or click the **Start** button to build and launch the application.

## Project Structure

The project follows a well-organized structure to simplify cross-platform development:

- **`App.xaml` & `App.xaml.cs`**: Application entry point, managing global styles and resources.
- **`MainPage.xaml` & `MainPage.xaml.cs`**: Primary user interface page with interactive elements.
- **`MauiProgram.cs`**: Configures the application, including fonts and logging.
- **`Resources`**:
  - **Fonts**: Custom fonts for use in the app.
  - **Images**: Image assets such as icons and logos.
  - **Styles**: XAML styles and color definitions.
- **`Platforms`**:
  - **Android**: Platform-specific configurations and launch settings.
  - **iOS/MacCatalyst**: App delegates and `Info.plist` settings.
  - **Windows**: App and manifest files for Windows.
  - **Tizen**: Entry point and manifest for Tizen.

### Notable Files

- **`Assignment12.1_MauiDemo_.csproj`**: Defines target frameworks, dependencies, and build configurations.
- **`MainPage.xaml`**: Declares the UI layout, including a button that increments a counter.
- **`MainPage.xaml.cs`**: Contains the button click event logic for the counter.

## Dependencies

- **Microsoft.Maui.Controls**: Core library for MAUI controls.
- **Microsoft.Extensions.Logging.Debug**: Enables debug logging during development.

## Customization

### App Icon and Splash Screen

- Located in `Resources/AppIcon` and `Resources/Splash`.
- Configured in the `.csproj` file via `MauiIcon` and `MauiSplashScreen` entries.

### Styles and Themes

- Defined in `Resources/Styles/Colors.xaml` and `Resources/Styles/Styles.xaml`.
- Easily customize colors and styles to match your application's branding.
