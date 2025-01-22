.NET MAUI Demo Project
This project is a demo application built using .NET Multi-platform App UI (.NET MAUI). It serves as a basic template to showcase the capabilities of .NET MAUI for building cross-platform applications targeting Android, iOS, macOS, Windows, and Tizen.
Features
•	Cross-Platform Support: Runs on Android, iOS, macOS (Catalyst), Windows (WinUI), and Tizen.
•	Responsive UI: Utilizes XAML for defining the user interface with responsive layouts.
•	Single Project Structure: Demonstrates the use of a single project to target multiple platforms.
•	Custom Styling: Includes custom styles and themes defined in XAML resource dictionaries.
•	Interactive Controls: Implements basic interactive elements like buttons and labels.
Getting Started
Prerequisites
•	Visual Studio 2022 with the .NET Multi-platform App UI development workload installed.
•	.NET SDK 8.0 or higher.
Building and Running the Project
1.	Clone the Repository:
   git clone https://github.com/yourusername/Assignment12.1_MauiDemo_.git
2.	Open the Solution:
•	Navigate to the project directory.
•	Open Assignment12.1_MauiDemo_.sln with Visual Studio 2022.
3.	Select the Startup Project:
•	Ensure that Assignment12.1_MauiDemo_ is set as the startup project.
4.	Choose the Target Platform:
•	In the toolbar, select the desired platform (e.g., Android Emulator, Windows Machine, iOS Simulator).
5.	Build and Run:
•	Press F5 or click the Start button to build and run the application.
Project Structure
•	App.xaml & App.xaml.cs: Entry point of the application, handling global styles and resources.
•	MainPage.xaml & MainPage.xaml.cs: Main user interface page with interactive elements.
•	MauiProgram.cs: Configures the MAUI app, fonts, and logging.
•	Resources:
•	Fonts: Custom fonts used within the app.
•	Images: Image assets like icons and logos.
•	Styles: XAML styles and color definitions.
•	Platforms:
•	Android: Platform-specific configurations and launcher.
•	iOS/MacCatalyst: Platform-specific app delegates and info plist.
•	Windows: App.xaml and manifest files for Windows.
•	Tizen: Main entry point and manifest for Tizen.
Notable Files
•	Assignment12.1_MauiDemo_.csproj: Project file specifying target frameworks and dependencies.
•	MainPage.xaml: Defines the UI layout, including a button that increments a counter.
•	MainPage.xaml.cs: Contains the logic for the counter button click event.
Dependencies
•	Microsoft.Maui.Controls: Core MAUI controls library.
•	Microsoft.Extensions.Logging.Debug: Enables debug logging during development.
Customization
•	App Icon and Splash Screen:
•	Located in Resources\AppIcon and Resources\Splash.
•	Defined in the .csproj file with MauiIcon and MauiSplashScreen entries.
•	Styles and Themes:
•	Defined in Resources\Styles\Colors.xaml and Resources\Styles\Styles.xaml.
•	Customize colors and styles to match your branding.
Contributing
Contributions are welcome! Please feel free to submit issues or pull requests.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgements
•	Thanks to the .NET MAUI team and community for providing comprehensive resources and documentation.
   