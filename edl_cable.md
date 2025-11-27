# DIY EDL Cable Guide

**Materials Needed:**
* USB 2.0 Type-C cable
* Normally Open Tactile Button (optional but recommended)
* Breadboard (optional)
* Wire cutters/strippers

## 1. Prepare the Cable
* Cut the USB cable at least **15cm** from the Type-C header.
* Strip the outer casing to reveal the four internal wires.

## 2. Identify the Wires
*Use both color and physical texture to identify the correct wires.*

* **Black (GND):** Ground. Will **not** have fabric mixed with wire strands.
* **Green (D+):** Data+. **Will** have silky fabric mixed in.
* **Red (VCC):** Positive power. Will **not** have fabric.
* **White (D-):** Data-. **Will** have silky fabric mixed in.

## 3. Create the Short
You need to bridge **Green (D+)** and **Black (GND)**.

* **With Button:** Wire the button between Green and Black.
* **Without Button:** Twist Green and Black wires together (or use a breadboard).

## 4. How to Use
1.  **Short** the Green (D+) and Black (GND) wires (hold button or touch wires).
2.  **Plug** the cable into the device and computer while holding the short.
3.  **Release** the short immediately after connection (check device manager and make sure you have Qualcomm drivers installed) ("unplug fast").