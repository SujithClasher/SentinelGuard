# Sentinel Guard 🛡️

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Platform: Android">
  <img src="https://img.shields.io/badge/API-21+-blue" alt="API Level">
  <img src="https://img.shields.io/badge/Flutter-3.2.0+-blue" alt="Flutter Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
  <img src="https://img.shields.io/badge/Demo-App-orange" alt="Demo App">
</p>

<p align="center">
  <strong>🎬 Professional Demo | Parental Control App with Material Design 3</strong>
</p>

<p align="center">
  <a href="#-installation">📱 Download APK</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-getting-started">🚀 Getting Started</a> •
  <a href="#-demo">🎮 Demo</a> •
  <a href="#-screenshots">📸 Screenshots</a>
</p>

## 📱 Download & Installation

### 📱 APK Download & Demo Video
<div align="center">

**[🚀 DOWNLOAD APK - 168.6 MB](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)**

**[🎬 WATCH DEMO VIDEO](https://github.com/SujithClasher/SentinelGuard/blob/master/SentinelGuard%20by%20Team%20Monad.mp4)**

</div>

### ⚡ Quick Install (3 Steps)
1. **[Download APK](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)** (168.6 MB)
2. **Install**: Settings → Apps → Special access → Install unknown apps → Enable for your browser
3. **Launch**: Open downloaded APK file → Install → Open app

### 🎬 Demo Videos Available
- **[📹 Watch Repository Demo Video](https://github.com/SujithClasher/SentinelGuard/blob/master/SentinelGuard%20by%20Team%20Monad.mp4)** - Complete app walkthrough
- **[🎬 External Demo Video](https://drive.google.com/file/d/1VMnrHRDgMloydAC2Boe7ylFpo-toHmvJ/view)** - Alternative demo

**⚠️ Important:** This is a **demo application** showcasing parental control UI with realistic mock data. It does not provide real device monitoring.

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

### 🎯 Demo Features Showcase
- **Interactive Dashboard** - Beautiful Material Design 3 interface with "Alex's Phone" demo data
- **Screen Time Visualization** - Realistic usage patterns and statistics display
- **App Management Interface** - 45+ real Android apps with usage controls mockup
- **Web Filtering Categories** - 10+ content categories with blocking simulation
- **NSFW Scanner Demo** - Premium feature showcase with blur effects
- **Activity Reports** - Weekly usage charts and browsing history simulation

### 👶 Kids Mode Launcher
- Colorful, child-friendly interface design
- Timer display and app grid layout
- PIN-protected exit system (Demo PIN: `123456`)
- Visual feedback and animations

### 🌟 Premium Features Showcase
- **Blur Effects Demo** - Visual inappropriate content protection simulation
- **Feature Cards** - Premium upgrade prompts and comparisons
- **Analytics Mockup** - Usage statistics and reporting interface

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

**⚡ FAST DOWNLOAD** (81.4 MB):

**[🚀 DOWNLOAD APK NOW](https://github.com/SujithClasher/SentinelGuard/raw/master/build/app/outputs/flutter-apk/app-debug.apk)**

*💡 Direct download - no waiting, instant access*

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

### 📹 Demo Videos
<div align="center">

**[🎬 Watch Repository Demo](https://github.com/SujithClasher/SentinelGuard/blob/master/SentinelGuard%20by%20Team%20Monad.mp4)** | **[🎬 Watch External Demo](https://drive.google.com/file/d/1VMnrHRDgMloydAC2Boe7ylFpo-toHmvJ/view)**

*Complete app walkthrough showcasing all demo features!*

</div>

### Demo Information
- **Demo PIN**: `123456` (for exiting kids mode)
- **Demo Device**: "Alex's Phone" (Samsung Galaxy S24 Ultra)
- **Demo Data**: 7 days of realistic usage patterns and activity
- **Features**: 45+ real Android apps, browsing history, screen time data

### What You'll Experience
1. **Splash Screen** → Animated logo with Material Design 3
2. **Onboarding Flow** → 3-page introduction to demo features
3. **Setup Process** → Parent account creation with PIN
4. **Dashboard View** → Screen time: 5m, 4 apps used, 8 websites visited
5. **Kids Launcher** → Colorful interface with timer display
6. **App Management** → 45+ real apps with usage controls interface
7. **Web Filtering** → 10+ content categories with blocking simulation
8. **Premium Showcase** → Feature comparisons and upgrade prompts

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

This **demo application** showcases:
- Modern Flutter architecture patterns
- Provider state management
- Material Design 3 implementation
- Complex UI with custom widgets
- Professional animations and transitions
- Realistic mock data systems
- Production-quality code structure

### 🎯 Demo Architecture
- **Frontend-only** demonstration (no backend)
- **Realistic mock data** for all features
- **45+ real Android apps** with package names
- **7 days of usage history** simulation
- **Material Design 3** compliance
- **Responsive layouts** for all screen sizes

### 🚀 Built for Demonstration
- Perfect for **portfolio showcase**
- **UI/UX design** presentation
- **Flutter development** skills demo
- **Interactive prototyping**
- **Client presentations**

Built with ❤️ using Flutter

---

**⚠️ Demo Purpose**: This application demonstrates parental control UI/UX design and does not provide real device monitoring or parental controls. All data is simulated for demonstration purposes.
