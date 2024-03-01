
# MentionAlarmFlutter

TeamsMentionAlert is a Flutter-based Android application designed to provide real-time alerts with an alarming sound whenever the user is mentioned in Microsoft Teams. This project aims to enhance the visibility of important notifications, ensuring that critical mentions do not go unnoticed.

## Features

- **Real-Time Notifications:** Receive immediate alerts when mentioned in Microsoft Teams.
- **Custom Alarming Sounds:** Choose from a selection of alarming sounds for notifications.
- **Microsoft Teams Integration:** Seamlessly integrates with Microsoft Teams using the Microsoft Graph API.
- **User-Friendly Interface:** Easy to navigate UI for setting preferences and viewing mention history.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Flutter SDK
- Android Studio or Visual Studio Code with Flutter and Dart plugins installed
- A Microsoft Azure account for accessing Microsoft Graph API
- Firebase account for handling notifications

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/bannawandoor27/MentionAlarmFlutter.git
```
2. **Navigate to the project directory**:
   ```bash
   cd TeamsMentionAlert
   ```
3. **Install dependencies**
   ```bash
   flutter pub get
   ```
4. **Running the App**
     ```bash
     flutter run
     ```
## Usage

After launching the app, log in with your Microsoft Teams account to start receiving alert notifications for mentions. You can customize the alert sound and other preferences in the app settings.

1. **Login to Microsoft Teams:** Open the app and use your Microsoft Teams credentials to log in.
2. **Customize Alert Sounds:** Navigate to the settings section to select your preferred alert sound for mentions. The app provides a variety of sounds to ensure you don't miss critical notifications.
3. **Notification Preferences:** Adjust notification settings such as vibration, LED blink (if supported by the device), and the priority of alerts to tailor the notification experience to your needs.
4. **View Mention History:** The app maintains a log of all the mentions you've received, allowing you to review missed or previous alerts at any time.
5. **Stay Alerted:** Ensure the app is running in the background to receive real-time alerts. The app is designed to consume minimal resources while providing immediate notifications.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. Whether it's fixing bugs, adding new features, improving documentation, or spreading the word, your contributions are welcome.

Here's how you can contribute:

1. **Fork the Project**: Start by forking the repository. This allows you to make changes without affecting the original project.

2. **Create your Feature Branch**: Make your changes in a new branch. This keeps the project organized and makes it easy to review your contribution. Use a clear and descriptive name for your branch, such as `git checkout -b feature/YourAmazingFeature`.

3. **Commit your Changes**: Once you've made your changes, commit them to your branch. Use clear and meaningful commit messages that explain what you've done and why. For example, `git commit -m 'Add a new alert sound option for mentions'`.

4. **Push to the Branch**: Upload your changes to GitHub. This makes them available for review. Use `git push origin feature/YourAmazingFeature`.

5. **Open a Pull Request**: Go to the original repository you forked and click on "Pull Request" to start the process. Ensure your pull request describes what you've changed and why. It's also helpful to reference any related issues.

### Pull Request Guidelines

- Ensure your code follows the project's code style and guidelines.
- Update the README.md with details of changes to the interface or new environment variables.
- Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [ConventionalCommits](https://www.conventionalcommits.org/en/v1.0.0/).

### Reporting Bugs

- Use the issue tracker to report bugs.
- Describe the bug and how to reproduce it.
- Include any error messages, screenshots, or additional information that could be helpful.

### Suggesting Enhancements

- Feel free to suggest enhancements via the issue tracker.
- Explain the suggested enhancement and its benefits.
- Discuss how it can be implemented or how it would change the user experience.

Your contributions, whether big or small, make a significant difference. We appreciate your effort to help improve this project!
