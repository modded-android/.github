# Modded Android

### README is a WIP

## Overview
Modded Android is a full fork of the Android Open Source Project (AOSP), built from the ground up to return to the core principles of AOSP: openness, flexibility, and user control. Our mission is to provide a clean, customizable, and community-driven Android experience, free from bloatware and proprietary constraints, while staying true to the spirit of open-source development.

## Philosophy
Modded Android aims to:
- **Restore AOSP's Roots**: Focus on a lightweight, transparent, and customizable operating system, prioritizing user freedom.
- **Empower Users and Developers**: Offer extensive customization options and a modular framework for developers to build upon.
- **Maintain Openness**: Ensure all code is open-source, community-driven, and free from unnecessary vendor integrations.

## Features
- **Pure AOSP Base**: Built directly from AOSP, stripped of proprietary apps and services.
- **Enhanced Customization**: Advanced theming, granular privacy controls, and flexible system tweaks.
- **Performance Optimized**: Lightweight design for faster performance and better battery efficiency.
- **Community-Driven**: Regular updates driven by community feedback and contributions.
- **Developer-Friendly**: Comprehensive documentation and tools for building custom ROMs and apps.

## Getting Started
### Prerequisites
- A compatible Android device (check our [device support list](https://moddedandroid.org/devices)).
- Basic knowledge of flashing custom ROMs.
- A computer with ADB and Fastboot tools installed.

### Installation
1. **Download Modded Android**: Grab the latest build for your device from [our website](https://moddedandroid.org/downloads).
2. **Unlock Bootloader**: Follow device-specific instructions to unlock your device's bootloader.
3. **Flash the ROM**:
   - Boot into recovery mode (e.g., TWRP).
   - Wipe data, cache, and system partitions.
   - Flash the Modded Android ZIP file.
   - Optionally, flash GApps or other add-ons.
4. **Reboot**: Restart your device and enjoy Modded Android!

## Contributing
We welcome contributions from the community! To get involved:
- **Code Contributions**: Fork our repository on [GitHub](https://github.com/moddedandroid) and submit pull requests.
- **Bug Reports**: Report issues on our [issue tracker](https://github.com/moddedandroid/issues).
- **Feature Requests**: Share your ideas on our [community forum](https://moddedandroid.org/forum).
- **Documentation**: Help improve our docs by submitting updates or translations.

## Building from Source
To build Modded Android:
1. Clone the repository: `git clone https://github.com/moddedandroid/source.git`
2. Set up the build environment: Follow the [AOSP build guide](https://source.android.com/setup/build) with our custom manifest.
3. Build: `source build/envsetup.sh && lunch moddedandroid_<device>-userdebug && make -j$(nproc)`
4. Flash the resulting images to your device.

## Community and Support
- **Discord**: Chat with us on our [Discord server](https://inv.wtf/deadinside).
- **Documentation**: Find guides and FAQs at [docs.moddedandroid.org](https://contribute.awfixer.com).

## License
Modded Android is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), in line with AOSP. See the `LICENSE` file for details.

## Acknowledgments
- The Android Open Source Project for providing the foundation.
- Our amazing community of developers, testers, and users.
