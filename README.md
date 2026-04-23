# Rank File

A Progressive Web App for studying and memorizing US military rank insignia across all service branches.

## Features

- ✈️ **Fully Offline** - Doesn't require an internet connection
- 📱 **Mobile First** - Install as an app on your phone
- 🎯 **Spaced Repetition** - Leitner box system for efficient learning
- 🎖️ **All Services** - Army, Navy, Marines, Air Force, Coast Guard, Space Force
- 📊 **Progress Tracking** - Track your study sessions and mastery
- ⭐ **Starred Cards** - Mark difficult ranks for focused study
- 🔄 **Multiple Modes** - Flashcards, quiz, or mixed study modes

## Deployment to GitHub Pages

1. **Enable GitHub Pages:**
   - Go to your repository settings on GitHub
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save

2. **Push your changes:**
   ```bash
   git push origin main
   ```

3. **Access your app:**
   Your app will be live at: `https://logan-d-clark.github.io/Rank-File/`

## Installing on Mobile

### iOS (iPhone/iPad)
1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll and tap "Add to Home Screen"
4. Tap "Add" in the top right
5. The app icon will appear on your home screen

### Android
1. Open the app in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home Screen" or "Install App"
4. Follow the prompts

## Offline Usage

Once installed:
- All rank data is embedded in the app
- Study progress is saved locally
- Works completely offline
- No internet connection needed after first load
- Service worker caches the app automatically

## Study Tips

- Use the **Leitner Box** system for optimal retention
- **Star** difficult ranks to create focused review sessions
- Switch between **modes** to test different aspects (insignia → rank, rank → insignia)
- Study **by branch** or **all branches** depending on your needs
- The app tracks which ranks you've seen and how many times you've practiced

## Technical Details

- Single-file HTML app with embedded CSS and JavaScript
- Progressive Web App (PWA) with offline support
- Service Worker for caching
- localStorage for persistent data
- No external dependencies or frameworks
- Mobile-optimized with touch gestures
