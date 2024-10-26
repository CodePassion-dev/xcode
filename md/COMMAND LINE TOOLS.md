# Xcode Command Line Tools

## Simulators

```bash
# Customize simulator status bar
xcrun simctl status_bar booted override --time 9:41 --cellularBars 1 --wifiBars 1 --batteryLevel 8
# Clear the status bar customize
xcrun simctl status_bar booted clear
```

```bash
# Show touch indicator:
defaults write com.apple.iphonesimulator ShowSingleTouches 1
# Restart the iOS Simulator
```

## Push Notifications

## Build Projects

## Run Unit Tests

## Export App for Sistribution

## References

- <https://developer.apple.com/library/archive/technotes/tn2339/_index.html>
- <https://mac.install.guide>
