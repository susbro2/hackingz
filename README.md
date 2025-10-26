# Terminal Adventure Game

A cross-platform terminal-style adventure game built with Flutter and Dart.

## Features

- Terminal-style interface with green text on black background
- Command-based gameplay (help, look, move, take items)
- Cross-platform support (Android, Windows, Linux, macOS)
- Command history with arrow key navigation
- Simple adventure game mechanics

## Available Commands

- `help` - Show available commands
- `look` - Examine current location
- `inventory` or `inv` - Show inventory
- `status` - Show player status
- `north/south/east/west` - Move in directions
- `take <item>` - Pick up items
- `clear` - Clear terminal screen

## Running the Game

### Android
```bash
flutter run -d android
```

### Desktop (Windows/Linux/macOS)
```bash
flutter run -d windows
flutter run -d linux
flutter run -d macos
```

## Game Locations

- **Home**: Starting room with a key on the desk
- **Hallway**: Connects home to garden
- **Garden**: Contains a coin to collect

## Development

Built with Flutter 3.10+ and Dart 3.0+. The game uses a simple state management system and command parser for terminal-style interaction.