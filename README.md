# 🌸 BloomFX - Grow digital flowers with your hands

[![Download BloomFX](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Suwals772/BloomFX/releases)

BloomFX creates digital flowers in real-time. The software uses your computer camera to track your hand movements. It turns your gestures into procedural flower animations. You see the flowers grow and bloom on your screen as you move your hands through the air.

## 🖥️ System Requirements

BloomFX works on Windows 10 and Windows 11. Your computer needs these items to run the program correctly:

*   Processor: Intel Core i5 or equivalent processor.
*   Memory: 8 GB of RAM.
*   Camera: A standard integrated or USB webcam.
*   Graphics: Hardware with support for OpenGL 3.3 or higher.
*   Storage: 500 MB of available disk space.

Ensure you have a steady internet connection for the initial download. The program requires good lighting in your room so the camera tracks your hand position without errors.

## 📥 How to Install

Follow these steps to set up the software on your Windows computer:

1. Visit [this page to download](https://github.com/Suwals772/BloomFX/releases) the latest version.
2. Locate the file named BloomFX_Installer.exe in your downloads folder.
3. Double-click the file to start the setup process.
4. Follow the prompts on your screen.
5. Click Finish to complete the installation.

The installer creates a shortcut on your desktop. You use this icon to start the program whenever you want to use the system.

## 🎮 How to Use BloomFX

Open the application by double-clicking the BloomFX icon on your desktop. The program starts your webcam automatically.

### Initial Setup
The first time you open the app, it asks for permission to access your camera. Select Yes or Allow to let the program see your hand movements. The application window displays your camera feed with the digital flowers overlaid on the image.

### Hand Tracking
Hold your hand in front of the camera. The software detects your palm and fingers. Keep your hand inside the frame for the best performance. If the flowers do not appear, adjust your lighting or move your hand closer to the camera lens.

### Creating Flowers
Move your hand to guide the growth of the flowers. The software uses mathematical curves to generate shapes. 
*   Move your hand slowly to create long, elegant stems.
*   Make quick circles to sprout petals.
*   Keep your hand steady to let the flower bloom fully.

## 🛠️ Troubleshooting

If the program fails to start or the camera feed remains black, follow these steps to fix the issue:

*   **Check Camera Privacy:** Go to Windows Settings, select Privacy & Security, and ensure Camera access is on for desktop applications.
*   **Close Background Apps:** Other programs like Zoom or Skype might use the camera. Close those apps before you start BloomFX.
*   **Update Drivers:** Ensure your webcam drivers are current. Use the Device Manager in Windows to check for updates.
*   **Lower Resolution:** If the animation feels slow, move your hand slower or clean your camera lens.

If the program closes unexpectedly, restart your computer. This clears the memory and allows the camera hardware to reset.

## ⚙️ Technical Details

BloomFX relies on computer vision libraries to interpret hand gestures. It captures video frames and processes them to identify specific points on your hand. The system maps these points to a coordinate grid. It then draws lines and shapes using Bézier curves. This process happens many times per second to create smooth, fluid animations. The procedural generation ensures that every flower looks unique based on your specific hand path.

## 🛡️ Privacy

BloomFX processes all video data on your local computer. It does not send images or video feeds to external servers. Your movements remain private. The application discards all camera data as soon as you close the window.

## 📝 Frequently Asked Questions

**Do I need a special camera?**
No. A standard laptop webcam works perfectly.

**Does it work in dark rooms?**
The camera needs enough light to see your hand. If the room is dark, the software struggles to track your movements. Use a desk lamp or sit near a window.

**Can I save the flowers I create?**
The current version focuses on real-time animation. Future updates may include a screen capture feature.

**Can I run this on a Mac?**
This version is for Windows computers only.

Keywords: ai, animation, augmented-reality, beizer-curves, computer-vision, hand-tracking, mediapipe, opencv, procedural-generation, python