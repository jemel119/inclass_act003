# Cyber-Tactile Control Studio (Flutter):

A interactive 3D Neomorphic control deck built with Flutter & Dart, demonstrating advanced micro-interactions and state management, with the theme: **Race Car Dashboard**.

## Features:
- **3D Mechanical Tactile Buttons**: Built using dual opposing `BoxShadow` physics and `GestureDetector`. Four race-inspired controls: **NITRO**, **DRIFT**, **BURNOUT**, and **PIT STOP**; each depress and pop back with a physical push-button feel.
- **Live State Management**: Real-time tap counts, energy calibration sliders, and status monitors track every command fired from the dashboard.
- **Overload Warning System**: Crossing 80% on the Power Calibration slider shifts the whole screen into a warning-red "overload" palette, simulating a car redlining.
- **Adaptive Theme System**: Seamless switching between Dark Cyber Mode and Light Neomorphic Mode.
- **Modular Component Design**: Reusable `TactileButton` custom widget architecture — swap icon/label/color to retheme instantly.

## 🛠 Tech Stack:
- **Framework**: Flutter
- **Language**: Dart
- **Key Widgets**: `StatefulWidget`, `GestureDetector`, `AnimatedContainer`, `Slider`, `Wrap`

## ▶️ Run It:
```
flutter run
```
