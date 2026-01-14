# Rainforest SDK

[![Swift](https://img.shields.io/badge/Swift-6.0-orange.svg)](https://swift.org)
[![Platforms](https://img.shields.io/badge/Platforms-iOS-blue.svg)]()

Tap to Phone enables merchants to accept contactless payments directly on a compatible device.

Rainforest currently supports processing Tap to Phone payments utilizing the Rainforest iOS SDK. Your platform's iOS application can embed Rainforest's SDK and securely initiate and process in-person payments using the device's built-in NFC capabilities.

---

## Installation

### Option 1: Xcode

To add this package to your project using Xcode:

1. Select **File** > **Add Packages...**
2. Enter the repository URL in the search bar:
   `https://github.com/rainforestpay/ios-sdk`
3. Set the **Dependency Rule** to _Up to Next Major Version_.
4. Click **Add Package**.

### Option 2: Via Terminal

If you are developing in VS Code or a headless environment, use the Swift CLI to manage the dependency.

1. **Navigate** to your project's root directory.
2. **Add the dependency** automatically by running:
   ```bash
   swift package add-dependency "https://github.com/rainforestpay/ios-sdk" --from 1.0.0
   ```
