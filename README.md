
---

# Play with AI or Multiplayer Pong Game

A classic Pong game featuring both AI and multiplayer modes. Developed in C++ from scratch with the Windows API, this game offers a nostalgic experience with modern functionality and fullscreen support.

## Features
- **Fullscreen Mode**: Enjoy a fullscreen gaming experience.
- **AI Mode**: Play against a computer-controlled opponent.
- **Multiplayer Mode**: Challenge a friend in local multiplayer.
- **Intuitive Controls**: Use keyboard controls for smooth gameplay.

## Project Files
- `game.cpp`: Contains the game logic and simulation.
- `platform_common.cpp`: Common platform-specific functions and utilities.
- `renderer.cpp`: Handles rendering and drawing operations.
- `utils.cpp`: Utility functions used across the project.
- `win32_platform.cpp`: Platform-specific code for Windows.

## Getting Started

### Prerequisites
- **Visual Studio**: Ensure you have Visual Studio installed. This project is set up for Visual Studio 2019 or later.

### Setup in Visual Studio

1. **Open the Project**:
   - Launch Visual Studio.
   - Open the solution file (`.sln`) in your project directory or create a new project and add the existing source files.

2. **Change Build Configuration**:
   - Go to the **Solution Explorer**.
   - Right-click on the solution or project and select **Properties**.
   - Navigate to **Configuration Properties** > **General**.
   - Change **Configuration Type** from **Application** to **Windows Application**. This ensures the project builds as a Windows application rather than a console application.

3. **Set Up Build and Debug Options**:
   - Go to **Configuration Properties** > **Linker** > **System**.
   - Set **Subsystem** to **Windows**.

4. **Build the Project**:
   - Click on **Build** in the top menu and select **Build Solution**.
   - This will compile the project and generate the executable.

5. **Run the Game**:
   - Press **F5** or click **Start Debugging** to run the game.

## Controls
- **Arrow Keys**: Move paddle up and down.
- **W/S**: Move paddle up and down (alternative controls).
- **Enter**: Start a new game.
- **Esc**: Exit the game.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to adjust any details as needed for your specific project setup!
