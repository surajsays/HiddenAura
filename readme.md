Positive Petals 🌱

Positive Petals is a cross-platform application designed to help users break bad habits and build positive behaviors. Each time users resist their cravings and choose healthier actions, their virtual tree grows, symbolizing progress and self-discipline. If they fail to resist, they can confess, causing the tree to wither. At the end of each month, users can evaluate their journey while preserving their tree's growth.
Features

    Habit Tracking: Click "I Will Do It" to grow your virtual tree and resist cravings.
    Progress Visualization: A growing tree to symbolize your journey towards self-improvement.
    Monthly Reflection: Review your progress without punishing yourself.
    Confession Mode: If you falter, confess, and see how it impacts your progress visually.
    Cross-Platform Support: Available on web, desktop, and mobile platforms.
    Offline Mode: Works seamlessly even without an internet connection.

Tech Stack

    Frontend: Built with Dioxus, a modern framework for building user interfaces in Rust.
    Backend: Rust-based logic for offline and online data synchronization.
    Platform Support: Supports web, desktop, and mobile (experimental).
    Database: Local storage for offline data persistence (SQLite/sled).

Installation
Prerequisites

    Rust installed on your system.
    Dioxus CLI for managing builds and serving the app.

Steps

    Clone the repository:

git clone https://github.com/surajsays/HiddenAura.git
cd HiddenAura

Install Dioxus CLI:

cargo install dioxus-cli

Run the project for your desired platform:

    Web:

dx serve --platform web

Desktop:

dx serve --platform desktop

Mobile:

        dx serve --platform mobile

How It Works

    Daily Usage:
        Open the app whenever you feel the urge for a habit.
        Click the "I Will Do It" button to grow your tree.

    Monthly Reset:
        At the end of each month, decide if you want to indulge as a reward without affecting your progress.

    Confessions:
        If you fail to resist, confess honestly, and watch how your tree responds visually.

Contributing

This is a personal learning project by surajsays under the repository HiddenAura. Contributions are not expected, but if you'd like to suggest improvements, feel free to fork the repository and open a pull request. For major changes, open an issue first to discuss your ideas.
License


You are free to use, modify, and distribute this project, provided that the license notice and copyright are retained.

For more details, refer to the LICENSE file in this repository.
Future Plans

    Add community features like group challenges.
    Support for customizable trees and visual themes.
    Advanced analytics and insights into user progress.
    Integrate Tauri for enhanced desktop support.

Contact

For queries or suggestions, reach on Instagram: surajsays.me.
