# Sentinel Guard 🛡️

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Platform: Android">
  <img src="https://img.shields.io/badge/API-21+-blue" alt="API Level">
  <img src="https://img.shields.io/badge/Flutter-3.2.0+-blue" alt="Flutter Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

<p align="center">
  <strong>A premium, production-ready Flutter parental control app with Material Design 3, built for Android 15+.</strong>
</p>

<p align="center">
  <a href="#-installation">📱 Download APK</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-getting-started">🚀 Getting Started</a> •
  <a href="#-demo">🎮 Demo</a> •
  <a href="#-screenshots">📸 Screenshots</a>
</p>

## 📱 Download & Installation

### APK Download
<div align="center">

**[🚀 DOWNLOAD APK NOW - 81.4 MB](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)**

[![Download APK](https://img.shields.io/badge/Download-APK-brightgreen?style=for-the-badge&logo=android)](https://github.com/SujithClasher/SentinelGuard/releases/download/v1.0.0/sentinel-guard-v1.0.0.apk)

</div>

### ⚡ Quick Install (3 Steps)
1. **[Download APK](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)** (81.4 MB)
2. **Install**: Settings → Apps → Special access → Install unknown apps → Enable for your browser
3. **Launch**: Open downloaded APK file → Install → Open app

### 🎬 Before Installing - Watch Demo
**[🎬 See App Demo Video](https://drive.google.com/file/d/1VMnrHRDgMloydAC2Boe7ylFpo-toHmvJ/view)** - Complete walkthrough of all features!

**🔗 Direct Links:**
- **Primary Download**: [sentinel-guard-debug.apk](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)
- **Alternative**: [GitHub Release](https://github.com/SujithClasher/SentinelGuard/releases) (when available)

**Full Installation Guide**: [Detailed Steps](#detailed-installation-steps)

## 📋 Detailed Installation Steps<a id="detailed-installation-steps"></a>

1. **Download the APK file** using either:
   - **[🚀 DOWNLOAD APK NOW - 81.4 MB](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)**
   - Click the "Download APK" badge above (requires GitHub release)
2. **Enable "Install from Unknown Sources"** in Android settings (Settings → Apps → Special access → Install unknown apps)
3. **Open the downloaded APK file** and follow the installation prompts
4. **Launch the app** and complete the setup process
5. **Grant permissions** for full functionality (Usage Stats, Overlay, etc.)

### System Requirements
- **Android Version**: 8.0 (API 26) or higher
- **Storage**: 50MB free space
- **RAM**: 2GB minimum
- **Permissions**: Usage Stats, Overlay, Device Admin (for full functionality)

## ✨ Features

### 🎯 Core Monitoring Features
- **Real-time Dashboard** - Track all children's activities at a glance
- **Screen Time Management** - Set daily limits, bedtimes, and tech-free schedules
- **App Management** - Block/allow apps with custom time limits
- **Web Filtering** - 10+ content categories with 1000+ blocked sites
- **NSFW Content Scanner** - AI-powered inappropriate content detection
- **Activity Reports** - Detailed analytics and browsing history

### 👨‍👩‍👧‍👦 Multi-Child Support
- Manage up to 5 children from one account
- Individual profiles with custom avatars
- Per-child settings and limits
- Real-time device status monitoring

### 👶 Kids Mode
- Colorful, child-friendly launcher interface
- Shows only approved apps
- Countdown timer for remaining screen time
- Request system to ask parents for more time
- PIN-protected exit

### 🌟 Premium Features
- **Real-Time Blur** - Automatically blur inappropriate content
- **Study AI** - AI homework helper and learning assistant
- **Advanced Analytics** - Deep insights and predictive alerts

## 🎨 Design Highlights

- **Material Design 3** with custom color schemes
- **Dark/Light Mode** support
- **Smooth Animations** using animate_do package
- **Responsive Layouts** for phones and tablets
- **Premium Gradients** throughout the UI
- **Glassmorphism Effects** for modern look

## 🏗️ Architecture

### State Management
- Provider pattern for app-wide state
- Reactive UI updates
- Centralized data management

### Project Structure
```
lib/
├── main.dart                 # App entry point with navigation
├── theme/                    # Theming and styles
│   ├── app_theme.dart
│   ├── colors.dart
│   └── text_styles.dart
├── models/                   # Data models
│   ├── child_profile.dart
│   ├── app_usage.dart
│   ├── website_category.dart
│   ├── activity_report.dart
│   └── screen_time_limit.dart
├── providers/                # State management
│   └── app_state.dart
├── screens/                  # All UI screens
│   ├── auth/                 # Splash, onboarding, setup
│   ├── parent/               # Parent dashboard & controls
│   └── child/                # Kids launcher
├── widgets/                  # Reusable components
│   ├── custom_app_bar.dart
│   ├── child_profile_card.dart
│   ├── usage_chart_card.dart
│   ├── app_tile.dart
│   ├── stat_card.dart
│   ├── premium_feature_card.dart
│   ├── blur_overlay_widget.dart
│   ├── loading_shimmer.dart
│   └── empty_state_widget.dart
└── data/                     # Dummy data service
    └── dummy_data.dart
```

## 📸 Screenshots

<div align="center">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/dashboard.png" alt="Dashboard" width="300" style="margin: 10px;">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/kids_mode.png" alt="Kids Mode" width="300" style="margin: 10px;">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/app_control.png" alt="App Control" width="300" style="margin: 10px;">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/web_filtering.png" alt="Web Filtering" width="300" style="margin: 10px;">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/nsfw_scanner.png" alt="NSFW Scanner" width="300" style="margin: 10px;">
  <img src="https://raw.githubusercontent.com/SujithClasher/SentinelGuard/master/screenshots/premium_features.png" alt="Premium Features" width="300" style="margin: 10px;">
</div>

**📂 View all screenshots**: [screenshots/](https://github.com/SujithClasher/SentinelGuard/tree/master/screenshots) folder

## 🚀 Getting Started

### For Users (APK Installation)

**⚡ FAST DOWNLOAD** (81.4 MB): **[Click here to download APK](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)**

*Alternative*: [GitHub Release](https://github.com/SujithClasher/SentinelGuard/releases) (when available)
2. **Install the APK**:
   - Enable "Install from Unknown Sources" in Settings
   - Open the downloaded `.apk` file
   - Follow installation prompts
3. **Launch and Setup**:
   - Open Sentinel Guard from app drawer
   - Complete the initial setup wizard
   - Grant necessary permissions (Usage Stats, Overlay)
4. **Configure Features**:
   - Set up child profiles
   - Configure app permissions
   - Enable web filtering categories

### For Developers (Source Code)

#### Prerequisites
- **Flutter SDK**: 3.2.0 or higher
- **Android Studio**: Latest version with Android SDK
- **Android Device/Emulator**: Android 8.0+ (API 26+)

#### Development Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/SujithClasher/SentinelGuard.git
   cd SentinelGuard
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run on connected device:**
   ```bash
   flutter run
   ```

4. **For release build:**
   ```bash
   flutter build apk --release
   ```

#### Project Structure
```
lib/
├── main.dart                 # App entry point
├── screens/                  # UI screens organized by feature
│   ├── auth/                # Onboarding and setup
│   ├── parent/              # Parent dashboard and controls
│   └── child/               # Kids launcher interface
├── services/                # Business logic and API services
├── models/                  # Data models and entities
├── providers/               # State management
├── widgets/                 # Reusable UI components
└── theme/                   # Styling and theming
```

## 🎮 Demo & Testing

### 📹 App Demo Video
<div align="center">

**[🎬 Watch Demo Video](https://drive.google.com/file/d/1VMnrHRDgMloydAC2Boe7ylFpo-toHmvJ/view)**

*See the app in action with a complete walkthrough of all features!*

</div>

### Demo Credentials
- **Parent PIN**: `123456` (for exiting kids mode)
- **Demo Data**: Pre-loaded with realistic usage data for testing
- **Test Device**: "Alex's Phone" with 45+ installed apps

### What You'll See After Installation
1. **Splash Screen** → Animated logo with gradient background
2. **Onboarding** → 3-page introduction to app features
3. **Setup Screen** → Create parent account with PIN
4. **Parent Dashboard** → Screen time: 4h 35m, 12 blocked apps, 3 requests pending
5. **Kids Mode** → Colorful launcher with approved apps and timer
6. **App Control** → 45+ real apps (YouTube, Instagram, Discord, etc.)
7. **Web Filtering** → Content categories with browsing history
8. **Premium Features** → Upgrade prompts and feature comparisons

### Test Scenarios
1. **Parent Dashboard**: View screen time stats, app usage, and activity feed
2. **Kids Mode**: Launch from dashboard, see timer countdown, exit with PIN `123456`
3. **App Management**: Search apps, set time limits, handle permission requests
4. **Web Filtering**: Toggle content categories, view browsing history
5. **Premium Features**: Explore upgrade options and premium functionality

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow Flutter best practices and coding standards
- Write tests for new features
- Update documentation as needed
- Ensure compatibility with minimum Android API 26

## 📞 Support & Contact

### Issues & Bug Reports
- [Report Issues](https://github.com/SujithClasher/SentinelGuard/issues)
- [Feature Requests](https://github.com/SujithClasher/SentinelGuard/issues)

### Technical Support
For technical questions or support:
- Check the [Wiki](https://github.com/SujithClasher/SentinelGuard/wiki) for detailed guides
- Review closed issues for common solutions
- Create a new issue with detailed information

## 📋 Changelog

See [CHANGELOG.md](CHANGELOG.md) for a detailed list of changes and version history.

## 🎯 Key Screens

### Authentication Flow
1. **Splash Screen** - Animated logo with gradient background
2. **Onboarding** - 3-page swipeable introduction
3. **Setup** - Create parent account with PIN

### Parent Mode
1. **Dashboard** - Overview with stats, children cards, and activity timeline
2. **Child Profiles** - Manage all children with detailed profiles
3. **App Management** - Control app access with pending requests
4. **Screen Time** - Daily limits, bedtimes, and schedules
5. **Web Filtering** - Category-based content blocking
6. **NSFW Scanner** - Detect and review suspicious content
7. **Activity Reports** - Analytics with charts and export
8. **Premium Features** - Upgrade prompts with feature comparison
9. **Settings** - Notifications, security, theme, and account

### Kids Mode
- **Launcher** - Grid of approved apps with remaining time display
- **Request System** - Ask parent for app access or more time
- **PIN Protection** - Secure exit requiring parent PIN

## 📊 Data Models

### Child Profile
- Name, age, avatar, device info
- Daily limits and bedtime settings
- Real-time usage tracking
- Device status (active/paused)

### App Usage
- 7-day usage history
- Time limits per app
- Block/allow status
- Category classification

### Activity Reports
- Browsing history with risk levels
- YouTube watch history
- Blocked attempts counter
- NSFW detections

## 🎨 Theme & Colors

### Color Palette
- **Primary**: Deep Purple (#6750A4) - Trust & Security
- **Secondary**: Teal (#26A69A) - Growth & Safety
- **Tertiary**: Amber (#FFA726) - Kids Mode
- **Semantic**: Red/Green/Orange/Blue for status

### Typography
- Headlines: Bold system font (32sp, 24sp, 20sp)
- Body: Regular system font (16sp, 14sp, 12sp)
- Kids Mode: Larger, bold text for readability

## 🔧 Packages Used

- **provider** ^6.1.1 - State management
- **fl_chart** ^0.66.0 - Beautiful charts
- **shimmer** ^3.0.0 - Loading skeletons
- **animate_do** ^3.1.2 - Smooth animations
- **font_awesome_flutter** ^10.6.0 - Icon library
- **intl** ^0.19.0 - Date formatting

## 🎯 Production Ready Features

✅ **Material Design 3** compliance  
✅ **Null Safety** enabled  
✅ **Responsive** layouts  
✅ **Dark Mode** support  
✅ **Error Handling** throughout  
✅ **Loading States** for all async operations  
✅ **Empty States** with helpful messages  
✅ **Smooth Animations** and transitions  
✅ **Accessibility** labels and touch targets  
✅ **Edge-to-Edge** Android 15 support  

## 🔮 Future Enhancements

- Backend integration with Firebase/REST API
- Real device monitoring with WorkManager
- Actual ML model for NSFW detection
- Geofencing and location tracking
- Real-time notifications with FCM
- Cross-platform iOS support
- Multi-language support
- Cloud backup and sync

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Flutter Team** for the amazing framework
- **Material Design Team** for the design system
- **Dart Team** for the programming language
- **Community Contributors** for their valuable feedback and suggestions

## 📊 Project Status

[![GitHub Stars](https://img.shields.io/github/stars/SujithClasher/SentinelGuard?style=social)](https://github.com/SujithClasher/SentinelGuard)
[![GitHub Forks](https://img.shields.io/github/forks/SujithClasher/SentinelGuard?style=social)](https://github.com/SujithClasher/SentinelGuard)
[![GitHub Issues](https://img.shields.io/github/issues/SujithClasher/SentinelGuard)](https://github.com/SujithClasher/SentinelGuard/issues)

**Version**: 1.0.0
**Last Updated**: October 2025
**Maintenance**: Active

---

<div align="center">
  <p><strong>Built with ❤️ using Flutter</strong></p>
  <p>
    <a href="#sentinel-guard-">Back to top ↑</a>
  </p>
</div>

## 👨‍💻 Developer Notes

This app demonstrates:
- Modern Flutter architecture patterns
- Provider state management
- Material Design 3 implementation
- Complex UI with custom widgets
- Production-ready code organization
- Professional-grade animations
- Comprehensive dummy data

Built with ❤️ using Flutter

---

**Note**: This is a frontend-only demo with dummy data. Real parental control features require:
- Android Device Admin permissions
- Usage Stats API access
- Accessibility Service for monitoring
- Background services
- Server-side filtering database
