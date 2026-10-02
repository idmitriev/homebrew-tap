# idmitriev/homebrew-tap

Homebrew casks for [Vibeshed](https://github.com/idmitriev/vibeshed).

```
brew install --cask idmitriev/tap/vibeshed
```

Releases are signed with a Developer ID and notarized by Apple, so Vibeshed opens without Gatekeeper warnings.

Upgrading from 0.6.0 or earlier (ad-hoc signed builds): macOS sees the new signature as a different app, so re-grant Accessibility, Input Monitoring, and other permissions once. Remove the old Vibeshed entries in System Settings → Privacy & Security, then re-add them.
