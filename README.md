# Virtual Camera Exploration
Unreal Engine project containing experiments with virtual cameras using live link.

## Instructions

### Initial Configuration

1. Go to Project Settings > Engine > Rendering > Default Settings > Advanced, and set the "Frame Buffer Pixel Format" to "8bit RGBA".
2. Go to Project Settings > Plugins > UDP Messaging > Transport, and set the "Unicast Endpoint" to your computer's IP address plus a ":0" at the end.
3. Go to Project Settings > Plugins > UDP Messaging > Transport > Static Endpoints, and set two new endpoints, one containing your computer's IP address and the other your phone's IP address.

## Credits

This project was implemented in [Unreal Engine v5.3](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-5.3-release-notes?application_version=5.3) using [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/virtual-cameras-in-unreal-engine?application_version=5.3), [Take Recorder](https://dev.epicgames.com/documentation/en-us/unreal-engine/take-recorder-in-unreal-engine?application_version=5.3), [Apple ARKit](https://dev.epicgames.com/documentation/en-us/unreal-engine/developing-for-arkit-in-unreal-engine?application_version=5.3), [Remote Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/using-the-remote-session-plugin-for-ios-development-in-unreal-engine?application_version=5.3) and [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/live-link-in-unreal-engine?application_version=5.3).
It benefits from the use of Andrew S. Hamilton's [Rural Australia Asset Pack](https://www.unrealengine.com/marketplace/en-US/product/rural-australia) for the environment.

For further information, please contact me at fsnap@protonmail.com.
