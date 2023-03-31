# SkootProject

SkootProject is a mobile application that provides users with various features to enhance their experience with their favorite soccer teams. Users can log in, view statistics for their favorite players, and access frequently asked questions.

## Repository Structure

<pre>
.
├── .vscode/                # VS Code configuration files
├── assets/                 # Static assets (images, fonts, etc.)
├── api/backend/            # Backend API integration
│   ├── TeamFavoris.js      # Favorite team management
│   └── SignIn.js           # Sign in functionality
├── FAQ/                    # FAQ-related components
│   ├── BottomTabNavigator.js # Bottom tab navigation for FAQ
│   ├── FAQPage.js           # FAQ page
│   └── ScreenPlayerStatistic.js # Player statistics screen
├── .firebaserc             # Firebase project configuration
├── .gitignore              # Files and directories to ignore by Git
├── App.js                  # Main application entry point
├── GlobalStyles.js         # Global styles for the application
├── GoogleService-Info.plist # Google services configuration for iOS
├── LoginPage.js            # Login page component
├── SkootProject.code-workspace # VS Code workspace file
├── app.json                # Expo configuration file
├── babel.config.js         # Babel configuration
├── database.rules.json     # Firebase Realtime Database rules
├── firebase.json           # Firebase project settings
├── firebaseConfig.js       # Firebase configuration for the app
├── metro.config.js         # Metro bundler configuration
├── package-lock.json       # Dependency version lockfile
├── package.json            # Dependency management file
└── playerData.js           # Player data (mock or fetched from API)
</pre>

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/username/SkootProject.git

Install the dependencies:

npm install

Start the development server:

npm start ios
