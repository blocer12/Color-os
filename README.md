# ColorOS 17-Style Launcher for Samsung Galaxy Tab A7 Lite

A lightweight Android Home Launcher inspired by **ColorOS 17's Living Flow Design**, built specifically for the **Samsung Galaxy Tab A7 Lite** (8.7" 1340×800 TFT display, MediaTek Helio P22T, 3GB/4GB RAM, Android 11–14).

## Features Included
- **Living Flow & Liquid Acrylic UI**: Translucent rounded cards (`26dp–28dp` radii) with subtle borders, avoiding heavy real-time GPU blur so scrolling stays smooth on the Helio P22T.
- **Global Floating Island Navigation**: Bottom floating pill housing Home, Mind Space, and All Apps toggles alongside up to 6 pinned dock apps.
- **Flexible Feedback Physics**: `SpringAnimation` (`androidx.dynamicanimation`) touch compression and elastic rebound on icons and navigation buttons.
- **Mind Suggest Header**: Live clock, date, and battery percentage card, plus instant local app search.
- **Galaxy Tab A7 Lite Adaptive Grid**: Automatically switches between **5 columns (portrait)** and **7 columns (landscape)**.
- **Full Android Launcher Integration**: Declares `CATEGORY_HOME` + `CATEGORY_DEFAULT` and `QUERY_ALL_PACKAGES` for Android 11+ (API 30–34), with long-press Pin/Unpin, App Info, and Uninstall actions.

## How to Build & Install
1. Open the extracted `ColorOS17TabLauncher` folder in **Android Studio** (Jellyfish or newer).
2. Let Gradle sync (requires internet on your PC to fetch AndroidX & Material dependencies).
3. On your **Galaxy Tab A7 Lite**, enable **Developer Options -> USB Debugging**, connect via USB-C, and click **Run** (or run `./gradlew installDebug`).
4. Press the Home button on your tablet and select **ColorOS 17 Tab Launcher -> Always** (or set it under *Settings -> Apps -> Choose default apps -> Home app*).
