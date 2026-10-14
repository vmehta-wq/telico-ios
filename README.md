# Telico iOS

Telico’s iOS application is based on Linphone. Original Belledonne Communications and contributor notices are preserved.

## Download corresponding source

[Telico 1.0 build 2 source release](https://github.com/vmehta-wq/telico-ios/releases/tag/v1.0-build.2)

Download **Telico-1.0-2-source.tar.gz** from the release assets. It contains the modified application, build instructions, pinned Swift package sources, Liblinphone SDK 5.5.18 source, and exact SDK dependency source archives. GitHub’s automatic Source code downloads contain only this release index; use the named asset for the application and dependencies.

The application retains GPLv3 notices; the SDK includes AGPLv3 and component-specific licenses. See LICENSE.txt, AGPL-3.0.txt and component notices in the archive. No Telico credentials or signing material are included. Public dependency test fixtures may contain upstream test keys/certificates.

## Build

Extract the asset and read README.txt and application/release/README.txt. Open application/LinphoneApp.xcodeproj in Xcode, use the Linphone scheme and pinned Package.resolved. Your own Apple signing setup is required for physical devices. Pinned package definitions download SDK binaries; corresponding SDK sources are included separately.

This beta source publication is not approval of Apple distribution licensing, export compliance, privacy declarations or production push delivery. These remain separate release gates.

Privacy policy: https://telico.ca/privacy
