# Unity Gaming Services Samples

![alt_text](~Documentation/Images/dont-markup.svg "Don't: Download a zip of this repository. It won't include the submodule content.")
![alt_text](~Documentation/Images/do-markup.svg "Do: Clone this repository using the '--recurse-submodules' option. -or- Navigate to a submodule you want, and clone or download a zip of the individual repo.")

This repository serves as a hub for multiple sample Unity projects which demonstrate features of Unity Gaming Services SDKs.

> **Note**: The Unity Gaming Services are currently in Open Beta. To participate in the Unity Gaming Services Open Beta and use the new services, go to the
[Unity Dashboard](https://dashboard.unity3d.com/) &gt; Explore Services &gt; Unity Gaming Services Beta Details, and click Join now.

## Getting Started

Clone this repository with all submodules (one for each sample project).

```bash
git clone --recurse-submodules https://github.com/Unity-Technologies/com.unity.services.samples
```

If you're only interested in an individual sample you can follow the links in the sections below to the specific repos and clone them from there.

## Overview

### Game Operations Samples

See the [Game Operations Samples repo](https://github.com/Unity-Technologies/com.unity.services.samples.game-operations)
to get started with exploring samples that implement various Unity Gaming Services,
such as Authentication, Economy, Remote Config, Cloud Code, and Cloud Save.

![alt_text](~Documentation/Images/game-operations-samples-screen-shot-1.png "samples starting menu")

This collection of samples is designed to guide developers to use multiple Unity Gaming Services in a single project.
These samples demonstrate how various services can be used together to:
* Address and implement typical backend game use cases and game design elements
* Resolve specific development tasks
* Show the efficiency you can achieve in your game backend by leveraging the Unity Gaming Services packages in your project

![alt_text](~Documentation/Images/game-operations-samples-screen-shot-2.png "example of having live seasonal content in a game")

### Game Lobby Sample

See the [Game Lobby Samples repo](https://github.com/Unity-Technologies/com.unity.services.samples.game-lobby)
to get started with exploring samples that implement Unity Gaming Services, such as Relay and Lobby.

![alt_text](~Documentation/Images/game-lobby-samples-screen-shot-1.png "an example lobby list")

This sample demonstrates how to use the Lobby and Relay packages to create a typical game lobby experience.
Players can host lobbies that other players can join using a public lobby list or lobby code,
and then connect with Relay to use Unity Transport ("UTP") for basic real-time communication between them.
Relay allows players to securely communicate with each other while maintaining connection anonymity.

![alt_text](~Documentation/Images/game-lobby-samples-screen-shot-2.png "an example lobby")
