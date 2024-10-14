# DEV Tracker Plugin

The **DEV Tracker** plugin helps developers monitor and manage the time spent on projects directly within IntelliJ IDEA.
Whether you are tracking productivity, managing time efficiently, or curious about your development habits, this plugin
offers an easy-to-use interface for keeping track of your work.

## Features

- **Automatic time tracking**: Tracks the time spent on each project automatically as you work.
- **Project-wise tracking**: Monitors and displays time spent on individual projects.
- **Non-intrusive notifications**: Get reminders after working continuously for a predefined amount of time.
- **Customizable settings**: Adjust reminders and tracking frequency to fit your workflow.
- **Simple UI**: Seamless integration into IntelliJ with easy-to-read time logs.

## Installation

### Option 1: Install via JetBrains Marketplace

1. Go to **File > Settings > Plugins** in IntelliJ IDEA.
2. Search for "**Development Time Tracker**".
3. Click **Install** and restart IntelliJ IDEA.

### Option 2: Manual Installation

1. Download the latest release of the plugin from the [Releases page](https://github.com/doquocviet.sept3rd/DEVTracker)
   (if available).
2. Open IntelliJ IDEA and navigate to **File > Settings > Plugins**.
3. Click the **Installation plugin from disk** button.
4. Select the downloaded plugin file and click **OK**.
5. Restart IntelliJ IDEA.

## Usage

Once installed, the plugin automatically starts tracking time as you work on different projects in IntelliJ.
Here’s how to use it:

1. **View tracked time**: Go to the plugin's tab in the bottom panel (or find it under **View > Tool Windows >
   Development Time Tracker**) to view the total time spent on all projects.
2. **Project-specific tracking**: The plugin will automatically track time per project and display the total time for
   each project.
3. **Reminders and Notifications**: The plugin will notify you if you have been working continuously for a specific
   period (this can be customized in settings).

### Customization

You can configure the plugin’s behavior by navigating to **File > Settings > Development Time Tracker** and adjusting:

- **Reminder frequency**: Set the interval after which you want to receive notifications.
- **Time tracking window**: Choose whether to track time for each session or overall project duration.

## Contributing

If you would like to contribute to the project, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and write tests.
4. Submit a pull request to the `main` branch.

### Code Style

- The plugin is built with **Java**.
- We use **Lombok** to minimize boilerplate code, and **Apache Commons Lang** for utility functions.

## License

This project is licensed under the MIT License, see the [LICENSE](https://www.sunecos.com) file for details.

## Contact

For questions, support, or feedback, feel free to contact us at:  
Email: [support@sunecos.com](mailto:support@sunecos.com)  
Website: [www.sunecos.com](http://www.sunecos.com)

## Acknowledgements

- This plugin uses **Apache Commons Lang** and **Commons Collections** to simplify common operations.
- The Icon used in this plugin is by [Do Quoc Viet - Founder Sunecos](https://www.sunecos.com).
