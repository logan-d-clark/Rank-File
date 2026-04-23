# Quick Deployment Guide

## Step 1: Push to GitHub

```bash
git push origin main
```

## Step 2: Enable GitHub Pages

1. Go to: https://github.com/logan-d-clark/Rank-File/settings/pages
2. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click "Save"

## Step 3: Wait for Deployment

- GitHub will build and deploy (usually takes 1-2 minutes)
- Check the Pages section for the green checkmark
- Your app will be live at: https://logan-d-clark.github.io/Rank-File/

## Step 4: Install on Your Phone

### iPhone/iPad:
1. Open Safari and go to your GitHub Pages URL
2. Tap Share button (square with arrow up)
3. Tap "Add to Home Screen"
4. Tap "Add"

### Android:
1. Open Chrome and go to your GitHub Pages URL
2. Tap the three dots menu
3. Tap "Add to Home Screen" or "Install App"

## Offline Usage

✅ **First load:** The app caches everything automatically
✅ **After that:** Works 100% offline, even on airplanes
✅ **Your progress:** Saved locally on your device
✅ **Updates:** Next time you have WiFi, the app auto-updates

## Testing Offline Mode

1. Install the app on your phone
2. Open it once with WiFi (to cache everything)
3. Turn on Airplane Mode
4. Open the app - it should work perfectly!

## Troubleshooting

**App not installing?**
- Make sure you're using Safari (iOS) or Chrome (Android)
- Clear browser cache and try again

**Not working offline?**
- Open the app once with internet first
- Check that service worker registered (check browser console)

**Updates not showing?**
- Hard refresh the page (Ctrl+Shift+R or Cmd+Shift+R)
- Or delete and reinstall the app
