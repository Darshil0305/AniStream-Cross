# AniStream-Cross

A cross-platform anime streaming application built with Flutter, providing seamless anime watching experience across Android, Android TV, Windows, and other platforms.

## 📱 Features

- **Cross-platform Support**: Native apps for Android, Android TV, Windows, macOS, Linux, and web
- **Hi Anime API Integration**: Access to vast anime library with high-quality streaming
- **Multiple Video Qualities**: Support for 720p, 1080p, and other quality options
- **Search & Discovery**: Advanced search functionality with filters and recommendations
- **Watchlist Management**: Save and organize your favorite anime series
- **Episode Tracking**: Keep track of watched episodes and progress
- **Offline Support**: Download episodes for offline viewing (where supported)
- **Responsive UI**: Adaptive interface optimized for different screen sizes
- **Dark/Light Theme**: Customizable themes for better viewing experience
- **TV Remote Support**: Full Android TV remote navigation support

## 🛠️ Tech Stack

- **Framework**: Flutter 3.x
- **Language**: Dart
- **State Management**: Provider/Riverpod
- **HTTP Client**: Dio
- **Database**: Hive/SQLite
- **Video Player**: video_player/better_player
- **API**: Hi Anime API
- **Platforms**: Android, Android TV, Windows, macOS, Linux, Web

## 📋 Prerequisites

Before running this application, make sure you have:

- Flutter SDK (3.0.0 or higher)
- Dart SDK (2.17.0 or higher)
- Android Studio or VS Code with Flutter extensions
- For Android: Android SDK and device/emulator
- For Windows: Visual Studio 2022 with C++ workload
- For macOS: Xcode (latest version)

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Darshil0305/AniStream-Cross.git
cd AniStream-Cross
```

### 2. Install Dependencies

```bash
flutter pub get
```

### 3. Platform-Specific Setup

#### Android/Android TV
```bash
flutter run -d android
```

#### Windows
```bash
flutter run -d windows
```

#### macOS
```bash
flutter run -d macos
```

#### Linux
```bash
flutter run -d linux
```

#### Web
```bash
flutter run -d web
```

## 🔧 API Setup

### Hi Anime API Configuration

1. The application uses the Hi Anime API for fetching anime content
2. No additional API key setup is required as Hi Anime provides free access
3. Base API endpoint is configured in `lib/services/api_service.dart`

### Custom API Configuration (Optional)

If you want to use a different API or configure custom endpoints:

1. Create a `.env` file in the root directory:
```env
API_BASE_URL=https://your-custom-api.com
API_KEY=your_api_key_if_required
```

2. Update the API service configuration in `lib/services/api_service.dart`

## 🎯 Usage Guide

### Getting Started

1. **Launch the App**: Open AniStream-Cross on your preferred platform
2. **Browse Anime**: Use the home screen to discover popular and trending anime
3. **Search**: Use the search functionality to find specific anime titles
4. **Watch Episodes**: Select an anime and choose episodes to stream
5. **Manage Watchlist**: Add anime to your watchlist for easy access
6. **Track Progress**: The app automatically tracks your viewing progress

### Navigation

- **Home**: Discover new and popular anime
- **Search**: Find specific titles with advanced filters
- **Watchlist**: Access your saved anime collection
- **Settings**: Customize app preferences and themes
- **Profile**: Manage your viewing history and preferences

### TV Navigation (Android TV)

- Use D-pad for navigation
- OK/Select button to choose options
- Back button to return to previous screen
- Menu button for additional options

## 🤝 Contributing

We welcome contributions to AniStream-Cross! Here's how you can help:

### Getting Started

1. **Fork the Repository**
   ```bash
   git fork https://github.com/Darshil0305/AniStream-Cross.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow Flutter/Dart coding conventions
   - Add tests for new functionality
   - Update documentation as needed

4. **Test Your Changes**
   ```bash
   flutter test
   flutter analyze
   ```

5. **Submit a Pull Request**
   - Provide a clear description of changes
   - Link related issues
   - Ensure all tests pass

### Contribution Guidelines

- **Code Style**: Follow official Dart style guide
- **Commit Messages**: Use conventional commit format
- **Documentation**: Update README and code comments
- **Testing**: Add unit and integration tests
- **Performance**: Optimize for cross-platform performance

### Areas for Contribution

- 🐛 Bug fixes and performance improvements
- ✨ New features and platform support
- 🎨 UI/UX enhancements
- 📱 Platform-specific optimizations
- 🧪 Test coverage improvements
- 📚 Documentation updates

### Issue Reporting

When reporting issues, please include:
- Platform and version
- Flutter/Dart version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Hi Anime API for providing anime content
- Flutter team for the amazing cross-platform framework
- Open source contributors and the anime community

## 📞 Support

If you encounter any issues or have questions:

- Create an [issue](https://github.com/Darshil0305/AniStream-Cross/issues)
- Join our community discussions
- Check the [Wiki](https://github.com/Darshil0305/AniStream-Cross/wiki) for additional documentation

---

⭐ **Star this repository if you find it helpful!**
