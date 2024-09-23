# Portable Tinkering Lab App

The **Portable Tinkering Lab App** is a Flutter-based mobile application designed for students to explore and learn about electronic components and various experiments. It integrates video tutorials, a scanning feature for identifying components, and interactive learning modules, providing an immersive hands-on experience.

## Releases

You can find the latest releases of this project [here](https://github.com/swapisticated/Portable-Tinkering-Lab.git).

### Latest Releases
- [v0.1.0-alpha](https://github.com/swapisticated/Portable-Tinkering-Lab.git/releases/tag/v0.1.0-alpha) - Initial release


## Features

- **Video Tutorials:** Watch tutorials on different electronic components and their usage.
- **Component Detection:** Use the device's camera to scan and identify electronic components like buzzers and sensors using Teachable Machine and TensorFlow Lite models.
- **Offline Video Playback:** Download tutorial videos from Firebase on first use for offline playback, ensuring the app works without internet connectivity after the initial download.
- **Interactive Dashboard:** A sliding dashboard providing easy navigation through the app without using an AppBar.
- **Curriculum Section:** A collection of learning materials to support students with their educational curriculum.
- **Lab Section:** A dedicated space for tinkering with portable electronic experiments, supported by tutorials.
- **Scan & Explore:** Real-time component scanning using machine learning to help users identify components and learn about their functions.
- **Profile and Settings:** User profile and settings options for personalization and customization of the app.

#Tech Stack

Flutter: Framework for building the app.
Firebase: Used for storing and downloading video tutorials.
TensorFlow Lite: Machine learning models for component recognition.
Teachable Machine: For training models used in component detection.
video_player & chewie: Video playback packages for playing offline tutorial videos.

Installation

    Clone the repository:

    

    git clone https://github.com/your-username/portable-tinkering-lab-app.git
    cd portable-tinkering-lab-app

Install dependencies:

    flutter pub get

Setup Firebase:

    Follow the Firebase Setup Guide to connect Firebase to the app for video storage and management.
    Make sure to configure Firebase correctly for both Android and iOS.

Run the app:

bash

    flutter run

Usage

    Upon launching the app, users are greeted with a landing page with three primary options: Curriculum, Lab, and Scan.
    The Lab section guides students through various experiments and provides videos for practical hands-on learning.
    The Scan section allows users to scan electronic components and receive real-time identification and information.

Contributing

    Fork the repository.
    Create a new branch for your feature or bugfix.
    Commit your changes.
    Push the branch and open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.
