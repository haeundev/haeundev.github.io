---
layout: post
title: Space Cleaners
description: Team AlienBusters 2023
date: 2023-10-20 15:01:35 +0900
image: '/images/spacecleaners-logo.png'
tags: [game, vr]
featured: true
---
Welcome to ‘Space Cleaners,’ a one-of-a-kind gaming experience that breaks away from the typical space shooter genre. Unlike most space games, you won’t be engaging in battles or destruction. Instead, you’ll compete in space debris towing contests, rescuing abandoned satellites and collecting broken turbines. But that’s not all – you’ll also venture to contaminated planets, fighting trash monsters and revitalizing the environment by growing plants. Join us in this cosmic cleanup mission and experience the fun and uniqueness of making space a cleaner place!

# Background and Purpose
In May 2023, South Korea successfully launched the Nuri rocket, demonstrating its capability to independently load and launch satellites. This has elevated South Korea's space industry to a globally trusted level, and the country is expected to continue leading efforts in space development. However, not just in South Korea but globally, active efforts are required to address the space debris problem caused by advances in space technology. Issues resulting from space debris, including fragments of satellites and other waste, are increasing. By 2023, there were nearly 9,000 satellites in Earth's orbit, and this number is expected to soar to 60,000 by 2030. Currently, over 100 trillion pieces of debris are believed to be circling the Earth. We've addressed this societal issue with an engaging 'Plogging' game. Derived from the Swedish 'plocka upp' (to pick up) and the English 'jogging', plogging is a global environmental movement that combines exercise with trash pickup. Taking inspiration from this, we designed the narrative of an "Aliens' Plogging Championship". Players navigate a spaceship through vast space, use nets to collect debris, and visit two extraterrestrial planets to purify their unique environments.

# Development Environment & Language

## Hardware
Meta Quest 2 VR HMD, PC (Windows, Mac)
## Software
Unity3D, OpenXR plugin, Blender, Illustrator, Photoshop
## System Design & Architecture
### Key foundational functionalities common across various modules include:

- ApplicationContext: Manages modules that must persist from game start to end. Operates during booting and loading stages, and during scene transitions.
- Addressable System & Related Custom Classes: Optimizes asset management using the addressable system.
- ScriptableObjects & Serialized JSON: Uses Google Spreadsheet API to serialize data directly from the web with a button click in the Unity editor. This allows for easy visualization and editing of game constants, types, etc. Functions like - Web requests are made universally accessible.
- SoundService: Manages audio. Uses asynchronous loading from addressables. In combat scenes where spatialized audio was necessary, this feature was added.
- Scenes - Booting, Loading, InGame: Systems load sequentially across scenes based on dependencies.
- Observer Pattern: Manages in-game events, minimizing unnecessary function calls and boosting frame rates.
- Optimization: Resource compression, lighting layer adjustments, and making certain objects static are part of the optimization process.
- Use of Singleton Pattern & Static Classes: They are designed when functionalities are required across multiple modules.

## Key Features of the Project
### Story
"Space Plogging Championship" is an inter-galactic space debris collection competition held annually, marking its 139th year. It's akin to a triathlon, where participants gather space debris, purify a jungle planet's air pollution by cultivating plants, and battle trash monsters on a desert planet to sort waste.
- Space
The player's spaceship is UFO-shaped, offering a 360-degree view of space. The cockpit allows tilt, rotation, and speed adjustments. Space employs a wrapping algorithm, enabling infinite flight. Tutorials are integrated into conversations. A plogging race map and current rankings are displayed.
- Jungle Planet Course
Players cultivate three distinct plants. Movement options include teleportation or smooth walking, with anti-nausea vignette effects. Color adjustments utilize hue shifts. With a healing-themed background score, NPCs guide and celebrate missions. Effects showcase nature's beauty and growth.
- Desert Planet Course
The most dynamic scene where players wear cartoonish boxing gloves to combat trash monsters. Upon defeating them, recyclable trash drops which players sort at designated stations. NPCs animate based on sorting accuracy.
- Other Technical Details
The game features an engaging dialogue system that offers diverse NPC responses based on player choices. Sand planet monsters utilize the A* algorithm for movement, and various interactions are managed using colliders and damage values. Particle effects, background music, and sound effects are strategically employed

![Game Scene](/images/spacecleaners-0.png)
<!-- *Photo by [Katie Emslie](https://unsplash.com/photos/B2-_qpgJm9Y) on [Unsplash](https://unsplash.com/)* -->

Integer euismod lacus luctus magna. Quisque cursus, metus vitae pharetra auctor, sem massa mattis sem, at interdum magna augue eget diam. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Morbi lacinia molestie dui. Praesent blandit dolor. Sed non quam. In vel mi sit amet augue congue elementum.

## Happiness in every moment
Morbi in dui quis est pulvinar ullamcorper. Nulla facilisi. Integer lacinia sollicitudin massa. Cras metus. Sed aliquet risus a tortor. Integer id quam. Morbi mi. Quisque nisl felis, venenatis tristique, dignissim in, ultrices sit amet, augue. Proin sodales libero eget ante. Nulla quam. Aenean laoreet. Vestibulum nisi lectus, commodo ac, facilisis ac, ultricies eu, pede. Ut orci risus, accumsan porttitor, cursus quis, aliquet eget, justo.

![Boy](/images/11-1.jpg)
*Photo by [Anthony Tran](https://unsplash.com/photos/6YMq73ydADI) on [Unsplash](https://unsplash.com/)*

Fusce nec tellus sed augue semper porta. Mauris massa. Vestibulum lacinia arcu eget nulla. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Curabitur sodales ligula in libero. Sed dignissim lacinia nunc. Curabitur tortor. Pellentesque nibh. Aenean quam. In scelerisque sem at dolor. Maecenas mattis. Sed convallis tristique sem. Proin ut ligula vel nunc egestas porttitor.

- Morbi in dui quis est pulvinar ullamcorper. Integer lacinia sollicitudin massa.
- Cras metus. Sed aliquet risus a tortor. Integer id quam. Morbi mi. Quisque nisl felis, venenatis tristique, dignissim in, ultrices sit amet, augue. Proin sodales libero eget ante. Nulla quam. Aenean laoreet.

Nulla quam. Aenean laoreet. Vestibulum nisi lectus, commodo ac, facilisis ac, ultricies eu, pede. Ut orci risus, accumsan porttitor, cursus quis, aliquet eget, justo. Sed pretium blandit orci. Ut eu diam at pede suscipit sodales. Aenean lectus elit, fermentum non, convallis id, sagittis at, neque. Nullam mauris orci, aliquet et, iaculis et, viverra vitae, ligula. Nulla ut felis in purus aliquam imperdiet. Maecenas aliquet mollis lectus. Vivamus consectetuer risus et tortor. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio.