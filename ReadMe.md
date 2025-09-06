# 🏏 Stump'd - Cricket Challenge App  

## 🚀 Features

- **🎮 Three Unique Challenges**: Test your cricket knowledge across different formats
- **📊 Real Player Stats**: Featuring legendary cricketers and their actual statistics
- **🎯 Target-Based Gameplay**: Strategic placement of players to hit challenging targets
- **📱 Cross-Platform**: Works on both iOS and Android devices
- **⚡ Fast & Responsive**: Built with React Native for smooth performance
- **🔒 Offline-First**: All data stored locally for instant access

## 🏆 Challenges

### 🏏 Runs Challenge
- **🎯 Target**: 700,000 runs
- **🧑‍🏫 Players**: 10 legendary batters
- **🔢 Slots**: 10x multiplier (1x to 10x)
- **🎲 Strategy**: Place your best batters in higher multiplier slots

### 🎳 Wickets Challenge
- **🎯 Target**: 10,000 wickets
- **🧑‍🏫 Players**: 7 elite bowlers
- **🔢 Slots**: 7x multiplier (1x to 7x)
- **🎲 Strategy**: Allocate your top wicket-takers wisely

### 💯 Centuries Challenge
- **🎯 Target**: 700 centuries
- **🧑‍🏫 Players**: 5 century machines
- **🔢 Slots**: 5x multiplier (1x to 5x)
- **🎲 Strategy**: Maximize centuries with smart placement

## 🎮 How to Play

1. **Select a Challenge** from the bottom navigation
2. **View Players** as they appear one by one
3. **Drag & Drop** players into multiplier slots
4. **Lock In** your choices (no changes after placement!)
5. **Reveal Score** and see how close you got to the target
6. **Challenge Friends** to beat your high score!

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher) or yarn (v1.22 or higher)
- Expo CLI (`npm install -g expo-cli`)
- Android Studio (for Android) or Xcode (for iOS)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Stumpd.git
cd Stumpd/Code

# Install dependencies
npm install
# or
yarn install

# Start the development server
npx expo start
```

### Running the App

- **iOS Simulator**: Press `i` in the terminal
- **Android Emulator**: Press `a` in the terminal
- **Physical Device**: Scan the QR code with Expo Go app

## 🏗️ Project Structure

```
Code/
├── assets/                  # Static assets and data files
│   ├── batsman.json         # Batters data with career statistics
│   ├── bowlers.json         # Bowlers data with career statistics
│   └── centuries.json       # Century scorers data
│
├── navigation/              # Navigation configuration
│   └── AppNavigator.tsx     # Main navigation setup with bottom tabs
│
├── screens/                 # App screens
│   ├── BattingChallengeScreen.tsx    # Runs challenge implementation
│   ├── BowlingChallengeScreen.tsx    # Wickets challenge implementation
│   └── CenturiesChallengeScreen.tsx  # Centuries challenge implementation
│
├── types/                   # TypeScript type definitions
│   └── index.ts             # Shared interfaces and types
│
├── App.tsx                  # Root component
└── package.json             # Project dependencies and scripts
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- All cricket statistics and player data are for educational purposes only
- Built with ❤️ using React Native and Expo

---

<div align="center">
  Made with ❤️ by Pritish | 
  <a href="https://github.com/pritish2403">GitHub</a> • 
  <a href="https://pritishdivate.vercel.app">Website</a>
</div>
