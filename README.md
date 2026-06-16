# PhishingGuard - AI Powered Phishing Protection

**PhishingGuard** is a smart, privacy-first Chrome extension that detects phishing websites in real-time using machine learning.

## Features

- **Local AI Protection**: Lightweight XGBoost model runs directly in your browser (no data sent)
- **Hybrid Mode**: Optional cloud backend with powerful server-side AI
- **Fast & Lightweight**: Browser model under 450 KB
- **Privacy Focused**: Full control — cloud mode can be turned off anytime
- **Real-time Detection**: Analyzes URLs instantly in the background

## How It Works

1. **Chrome Extension** extracts features from the visited URL
2. **Local Model** (ONNX) gives instant prediction
3. **Server Model** (optional) provides higher accuracy when enabled

---

## Installation (Simple & Proper Way)

### Method 1: Load as Unpacked Extension (Recommended for Testing)

1. Download the latest release from [GitHub Releases] or clone the repository.
2. Open Google Chrome.
3. Go to `chrome://extensions/`
4. Enable **Developer mode** (toggle in the top right corner).
5. Click **"Load unpacked"**.
6. Select the `extension` folder from the downloaded project.
7. The extension should now appear and start working.
