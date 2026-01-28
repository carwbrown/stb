# Shut the Box 🎲

A mobile game built with React Native and Expo, bringing the classic dice game "Shut the Box" to iOS and Android.

## About the Game

Shut the Box is a traditional pub game where players attempt to "shut" numbered tiles (1-9) by rolling dice. The goal is to achieve the lowest score possible by flipping down tiles.

### How to Play

1. **Setup**: Each player starts with tiles 1-9 face up
2. **Roll**: Roll two dice (or one die if remaining tiles sum to 6 or less)
3. **Flip**: Choose any combination of face-up tiles that equal the dice total
4. **Repeat**: Continue rolling and flipping until no valid moves remain
5. **Score**: Your score is the sum of remaining face-up tiles (lower is better!)
6. **Winner**: The player with the lowest score wins

### Example Turn
- Roll: 7 (3 + 4)
- Valid moves: flip 7, flip 3+4, flip 1+6, flip 2+5, flip 1+2+4, etc.

## Tech Stack

- **React Native** - Cross-platform mobile development
- **Expo** - Development platform and build tooling
- **Expo Router** - File-based navigation
- **TypeScript** - Type safety and better DX
- **EAS Build** - Cloud builds for iOS and Android
- **EAS Submit** - App Store and Play Store submission

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npx expo start
```

In the output, you'll find options to open the app in a:
- [Development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go)

## Project Structure

```
stb/
├── app/                   # Expo Router screens
├── components/            # Reusable UI components
├── hooks/                 # Custom hooks
├── constants/             # Theme, colors, config
├── assets/                # Images, sounds
└── scripts/               # Build/utility scripts
```

## Future Ideas

- **Tournament Mode**: Multiple rounds with cumulative scoring
- **Battle Royale**: Elimination rounds (top scores get eliminated each round, Fall Guys style)
- **Online Multiplayer**: Play with friends remotely
- **Achievements**: Unlock rewards for perfect games, streaks, etc.

## License

MIT
