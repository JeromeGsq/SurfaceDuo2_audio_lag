# Surface Duo 2 - Audio Lag Issue Report

## Overview

This document outlines the audio latency bug encountered on the Surface Duo 2 device, providing a detailed description of the issue, steps to reproduce it, expected behavior, and actual results. The aim is to facilitate the identification and resolution of the issue by the Microsoft development team.

## Issue Description

Currently, users of the Surface Duo 2 are experiencing a noticeable audio lag issue, particularly noticeable while playing games on the device. This lag, approximately one second in duration, significantly impacts the usability of the Surface Duo 2 for gaming purposes. The delay between the action performed on the device and the corresponding audio feedback disrupts the gaming experience, making it challenging for users to engage in gameplay effectively.

## Detailed Issue 

When using the Surface Duo 2 for gaming, there is a perceptible delay in audio output relative to the on-screen actions. This latency, estimated to be around one second, creates a disconnect between the visual and auditory components of the game. For instance, if a user performs an action in the game, such as jumping or shooting, the sound associated with that action is heard with a noticeable delay. This issue is not isolated to a specific game but has been reported across various gaming applications on the Surface Duo 2.
The audio lag issue poses a significant problem for gamers, as timing and audio-visual synchronization are crucial elements of the gaming experience. The delay can lead to misinterpretations of game states, negatively affecting gameplay performance and enjoyment. Furthermore, this issue undermines one of the key advantages of the Surface Duo 2 - its dual-screen functionality, which is designed to enhance gaming and multimedia experiences.

- **Device Model:** Surface Duo 2
- **OS Version:** [Include the Android version and build number]
- **Application:** [If applicable, include the name and version of the application where the bug was observed]
- **Severity:** [Optional: Indicate the severity of the issue, e.g., minor, major, critical]

## Steps to Reproduce

1. Power on the Surface Duo 2 and unlock the device.
2. Launch a game or an application where audio cues play a significant role in gameplay.
3. Engage in gameplay and perform actions that trigger sound effects (e.g., jumping, shooting, etc.).
4. Observe the delay between the visual cue/action and the corresponding audio output.

## Expected Behavior

When engaging in gaming or any application that relies on audio feedback on the Surface Duo 2, users anticipate a seamless audio-visual experience where the sound is perfectly synchronized with the actions performed on the device. Specifically, for gaming applications, the expected behavior includes:

- Immediate Audio Feedback: Upon performing an action within a game, such as jumping, shooting, or any other interaction that generates sound, the audio feedback should be instantaneous. There should be no noticeable delay between the visual action on the screen and the corresponding audio cue.

- Synchronized Gameplay Experience: The gaming experience should be fully synchronized, with audio and visual elements complementing each other in real-time. This synchronization is crucial for games that rely heavily on timing and audio cues to provide an immersive and interactive gaming environment.

- Consistent Performance Across All Games: Regardless of the game or application being used, the audio performance should be consistent. Users expect the same level of audio-visual synchronization across all types of content, from fast-paced action games to more casual gaming experiences.

- Optimized Dual-Screen Functionality: Given the unique dual-screen design of the Surface Duo 2, users expect this feature to enhance their gaming experience without any compromise in performance. This includes expecting the device to handle audio processing efficiently, ensuring that the dual-screen functionality does not introduce any additional latency or synchronization issues.

In summary, the expected behavior for the Surface Duo 2, especially in the context of gaming, is a fluid and synchronized audio-visual experience that enhances gameplay rather than detracting from it. Users expect the device to deliver high-quality, real-time audio feedback that aligns perfectly with on-screen actions, ensuring an engaging and immersive gaming experience.

## Actual Behavior

When playing games on the Surface Duo 2, users are encountering an actual behavior that deviates from the expected seamless gaming experience. The specific issue observed is a one-second latency between the visual game input and the corresponding audio output. This means that when a player performs an action in the game, such as pressing a button to jump or shoot, the sound effect associated with that action is delayed by approximately one second.

This latency issue is not isolated to a single game but has been reported across various gaming applications on the Surface Duo 2. The problem persists regardless of the game's requirements for precision or the genre, affecting the overall gaming experience on the device. The delay in audio feedback is particularly detrimental to gameplay that relies on tight synchronization between audio and visual cues, as it can lead to mistimed reactions and a disjointed feeling during play.

Furthermore, the issue has been noted to impact the usability of the Surface Duo 2 for gaming purposes, as the lag creates a frustrating experience for players who expect immediate and synchronized audio responses to their in-game actions. This behavior is inconsistent with the high-performance hardware specifications of the Surface Duo 2 and the expectations set by its dual-screen design, which aims to enhance multimedia consumption and gaming activities

## Additional Information

- **Frequency of Occurrence:** happens all the time on specfic games or emulators
- **Workarounds:** [If you have found any workarounds, list them here]
- **Attachments:** [Attach any relevant screenshots, logs, or error messages]

## Contact Information

[Optional: Provide your contact information if you are open to follow-up questions. This could include an email address, GitHub username, or other contact methods.]

---

This issue report is created based on the guidelines provided in various resources on writing effective bug reports and README documents for software projects[1][2][3][5][7]. The structure and content are designed to provide the development team with a clear understanding of the issue and how to replicate it for further investigation.


## Sources

### Emulator 
- GBC emu: https://github.com/Rakashazi/emu-ex-plus-alpha?tab=readme-ov-file
- Game: https://jayrojones.itch.io/test-cart