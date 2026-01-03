# Abhiraj's Portfolio & Dev Tools

## Short Description
A comprehensive Flutter portfolio app showcasing projects, featuring powerful developer tools (Calculator, Unit Converter, Stopwatch, Timer, JSON/HTML/CSS/JS editors), an integrated web browser, and interactive games - all in one elegant package.

## Long Description

Abhiraj Portfolio & Dev Tools is a feature-rich mobile application that combines a professional portfolio showcase with practical developer utilities. Built with Flutter and Material Design 3, this app demonstrates expertise in UI/UX design, software development, and modern tech stack implementation.

### Key Features:

**Portfolio Showcase**
- Stunning hero section with animated particle background and gradient effects
- Dynamic project display with Firebase Realtime Database integration
- Offline-first architecture with intelligent caching using SharedPreferences
- Smooth animations and professional saffron-themed design
- Direct contact integration via email and GitHub with clipboard fallback
- Floating "Get In Touch" button with smart visibility
- Settings dialog for customizable default tab selection

**Interactive Games**
- **No. Quests**: Number-based puzzle game with custom splash screen and navigation
- **WordFinder**: Word search puzzle game with dedicated home screen
- Grid-based game selection with custom card designs
- Independent game navigation with proper back button handling

**Tools & Utilities**
- **Calculator**: 
  - Professional scientific calculator with iPhone-style percentage functionality
  - Real-time calculation with chain operations support
  - History tracking with Hive local storage (last 100 calculations)
  - Swipe-to-delete and copy-to-clipboard features
  - Smart number formatting with scientific notation
  - Haptic feedback for enhanced user experience
  - Modern dark theme with saffron accent colors
- **Unit Converter**: 
  - 8 conversion categories: Length, Weight, Temperature, Area, Volume, Speed, Time, Data
  - 50+ units with accurate conversion formulas
  - Real-time conversion as you type
  - Swap button to reverse conversion direction
  - Custom temperature formulas (Celsius, Fahrenheit, Kelvin)
  - Professional dropdown menus with unit symbols
  - Base unit system for precise calculations
- **Stopwatch**: 
  - High-precision timing with millisecond accuracy (30ms refresh rate)
  - Lap recording with fastest/slowest lap indicators
  - Start/Stop/Resume and Reset functionality
  - Scrollable lap list with lap number, lap time, and total time
  - Color-coded laps (green for fastest, red for slowest)
  - Professional circular action buttons
  - Tabular figures for clean number alignment
- **Timer**: 
  - Countdown timer with circular progress indicator
  - 7 quick presets: 1m, 3m, 5m, 10m, 15m, 30m, 1h
  - Visual progress ring with color change (red warning at ≤10 seconds)
  - Start/Pause/Resume and Reset controls
  - Completion alert with haptic feedback
  - Scrollable interface for better mobile experience
  - Solid saffron background for selected presets
- **Web Viewer**: 
  - Full-featured in-app browser with JavaScript support
  - Smart URL editing with clickable header
  - Navigation controls (back, forward, reload, home)
  - Automatic file download support for 70+ file types
  - Quick links to popular websites (YouTube, Instagram, GitHub, Portfolio)
  - System back button integration for seamless navigation
  - Bottom navigation auto-hide for immersive browsing experience
- **WhatsApp Status Saver**: Coming Soon

**CS (Computer Science) - Developer Tools**
- **JSON Editor & Viewer**: 
  - Dual-mode interface (Editor & Viewer tabs)
  - Syntax highlighting with real-time validation
  - Tree view visualization with expandable nodes
  - Format, validate, copy/paste, and sample data features
  - Color-coded values and detailed error messages
  - Sample JSON template for quick reference
- **HTML/CSS/JS Editor**: 
  - CodePen-like web development environment
  - Three separate editors (HTML, CSS, JS) with syntax highlighting
  - Live WebView preview with real-time auto-update (800ms debounce)
  - Resizable layout with draggable divider between editors and preview
  - Independent editor instances for each language
  - ZIP export functionality to Download/Abhiraj/ folder
  - Smart button visibility (tap same tab twice to toggle)
  - Full JavaScript execution support with console logs
  - Default templates for quick start
- **Markdown Editor & Viewer**:
  - Dual-mode interface (Editor & Viewer tabs)
  - Syntax highlighting for markdown in editor
  - Live preview with real-time rendering
  - Support for headings, bold, italic, links, lists, blockquotes, code blocks
  - Clickable links in viewer
  - Selectable text in preview
  - Copy/paste, download, and sample markdown features
  - Downloads to Download/Abhiraj/Markdown/ folder
  - Comprehensive markdown sample template included
- **MCS Syllabus**: 
  - Complete Master of Computer Science curriculum viewer
  - Unified expandable interface: Courses → Semesters → Subjects → Units
  - Single-screen navigation with expandable sections for better UX
  - Rich topic details with definitions, explanations, examples, and key points
  - Case studies with descriptions and images
  - Offline-first with intelligent caching for instant loading
  - Pull-to-refresh functionality
  - Image support for topics and case studies
  - Color-coded sections for better organization
  - Works perfectly offline with cached data
  - Firebase Realtime Database integration with background sync
  - State management remembers expanded sections
  - Visual indicator for cached vs. live data

**Web Viewer**
- Full-featured in-app browser with JavaScript support
- Smart URL editing with clickable header
- Navigation controls (back, forward, reload, home)
- Automatic file download support for 70+ file types
- Quick links to popular websites (YouTube, Instagram, GitHub, Portfolio)
- System back button integration for seamless navigation
- Bottom navigation auto-hide for immersive browsing experience

**User Authentication**
- Secure email/password authentication via Supabase
- Email verification system
- Session management with persistent login
- Sign up and login screens with validation
- Automatic deep link handling for email verification

**Download Manager**
- Supports documents, archives, executables, images, audio, video, code files, fonts, and more (70+ file types)
- Automatic permission handling for Android 6-13+
- Organized file storage in dedicated Abhiraj folders
- Real-time download notifications with proper file naming

**Technical Highlights**
- Material Design 3 with custom saffron color scheme (FF9933)
- Firebase Realtime Database integration with offline caching
- Hive local database for calculator history persistence
- Local storage with SharedPreferences for settings, cache, and syllabus data
- Advanced WebView implementation with download handling
- Permission management for storage access
- Responsive design optimized for mobile devices
- Clean architecture with proper state management
- Custom particle animation painter for hero section
- Gradient backgrounds and smooth transitions throughout
- Cache-first loading strategy for instant app startup
- Comprehensive offline support for all features
- Automatic background data synchronization
- Haptic feedback throughout the app for better UX
- Real-time calculations and conversions
- Professional typography with tabular figures

**App Architecture**
- Three main screens: Games & CS Tools, Tools & Utilities, Profile
- Scrollable tab bar for Tools & Utilities (Calculator, Converter, Stopwatch, Timer, Web Viewer)
- Bottom navigation with auto-hide functionality
- Supabase authentication service for secure user login and email verification
- Firebase Realtime Database service for project data management
- Calculator service with Hive storage for history persistence
- Converter service with base unit conversion system
- Syllabus service with cache-first loading and background sync
- Settings service for user preferences
- Deep link service for email verification and navigation
- Structured data models (Project, Syllabus, Topic, Unit, CaseStudy, CalculationHistory, UnitCategory)
- Comprehensive error handling and fallbacks
- Unified expandable syllabus screen with three-level hierarchy
- Nested MaterialApp for game navigation (No. Quests & WordFinder)
- Image caching with Flutter's built-in cache manager
- Professional dark theme with consistent saffron accent (#FF9933)
- Responsive design optimized for mobile devices
- Smart caching strategy with offline support

Perfect for developers, tech enthusiasts, and anyone looking for a powerful all-in-one mobile toolkit with a beautiful, modern interface combining productivity tools with entertainment.
