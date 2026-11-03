# VoidTube

A lightweight iOS 12+ YouTube web client shell, designed with older devices such as iPhone 6 in mind.

## Current scope (v0.1)
- Lightweight UIKit app with a `WKWebView`
- Opens YouTube's mobile website (`https://m.youtube.com`)
- No account sign-in is required for basic browsing
- Login is not implemented in this first version; Google may block sign-in inside embedded web views

## Build an unsigned IPA with GitHub Actions
1. Create a new **public or private** GitHub repository named `VoidTube`.
2. Upload the contents of this folder to the repository (not the containing folder itself).
3. Open **Actions** and enable workflows if GitHub asks.
4. Run **Build unsigned IPA** from the Actions tab.
5. Download the `VoidTube-unsigned-ipa` artifact from the completed run.

The IPA is unsigned. Installing it requires a compatible signing/install method. Since your iPhone is jailbroken with AppSync Unified, installation may be possible, but this workflow does not guarantee installation or runtime compatibility.

## Notes
- Deployment target: iOS 12.0
- This is a web wrapper, not an official YouTube app and not a native YouTube API client.
- YouTube features, playback, and availability depend on YouTube's website and its current policies.
- 
