# Task Breaker - iOS App (Swift)

**Task Breaker** is an iOS app designed to help users break down complex tasks into smaller, actionable components, reducing anxiety and increasing productivity. Built entirely in Swift, the app leverages Gemini AI for task breakdown and provides an intuitive interface for managing tasks.

## Features

- **Task Input**: Users can type in a task that they need to complete.
- **AI-Powered Task Breakdown**: Leveraging Gemini AI, the app breaks down complex tasks into simpler steps, making them easier to tackle.
- **Task List Management**: Users can add, view, and delete tasks easily.
- **Interactive UI**: Built with SwiftUI, the app provides a modern, responsive user experience.
- **Progress Tracking**: View and mark tasks as complete to keep track of progress.

## Getting Started

### Prerequisites
- Requires Xcode 15.0 or later.
- Targeting iOS 15.0 or later.
- A valid API key from Google AI Studio to use Gemini AI.

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/task-breaker-swift.git
   ```
2. Open the project in Xcode:
   ```sh
   cd task-breaker-swift
   open TaskBreaker.xcodeproj
   ```
3. Add the Gemini AI SDK to your project:
   - Go to **File > Add Packages** in Xcode.
   - Add the package URL: `https://github.com/google/generative-ai-swift`.
4. Build and run the project on a simulator or a physical device.

## Usage
1. Open the app and enter a complex task in the text field.
2. Tap on **Break Down Task** to let Gemini AI generate simpler components for your task.
3. View the generated sub-tasks in a list format and mark them as completed once done.
4. Add and delete tasks from the list as needed.

## Technologies Used
- **Swift & SwiftUI**: For building a native iOS user interface.
- **Gemini AI**: Used for AI-driven task breakdown.
- **CoreData**: For storing tasks locally on the device.

## Roadmap
- **Siri Integration**: Adding the ability for users to add tasks via Siri voice commands.
- **Local Notifications**: Reminders for incomplete tasks.
- **Dark Mode Support**: Provide a dark mode option for users who prefer reduced screen brightness.

## Contribution
Feel free to fork the repository and submit pull requests for new features or bug fixes. Contributions are welcome to make the app even more effective.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.



