# Oroo_nights_soundscape
# Oroo Nights: Layered Nocturnal Soundscape

**Short Description:**  
Oroo Nights: a 5-minute interactive soundscape capturing ritual, tension, and ancestral presence through layered audio design.

**Full Description:**  
A layered, immersive nocturnal soundscape exploring tension, ritual, and ancestral presence. Designed for interactive web playback with Tone.js, this project models the progression of a sacred night through five audio layers — from exterior ambience to intimate interior spaces, natural warnings, the main procession, and optional narration. Includes audio assets, documentation, and visualizations for developers, sound designers, and creative technologists.

---

## 🎧 Overview

Oroo Nights is a **5-minute soundscape experience** built around the progression of a ritualistic night. The design uses **five main audio layers** with transitions, dynamic textures, and psychoacoustic effects to immerse the listener. The project is structured for web playback using Tone.js, allowing optional layer toggling, volume adjustment per layer, and interactive exploration.

**Key Features:**
- Layered audio with dynamic transitions
- Psychoacoustic design to simulate proximity, tension, and immersion
- Interactive web-ready implementation using Tone.js
- Optional narration layer for context and explanation
- Audio assets and visualizations included

---

## 🗂 Layers

**Layer 1: Exterior Ambience**  
- Continuous natural environment: crickets, soft winds, leaves rustling  
- Duration: 5 minutes (fades in/out at beginning and end)  
- Dynamic spatialization: airborne perspective moving closer to the house  

**Layer 2: Bedroom / Interior Ambience**  
- Sounds inside a 10x12 ft bedroom: fan, analog clock, subtle breathing, bed creaks, blanket rustles  
- Emotional pacing: calm → tense → restless  
- Windows half-open, garden activity subdued  

**Layer 3: Natural Warning**  
- Warning sounds from outside: night owl, distant vehicle, lone dog barking  
- Subtle animal movement, crickets honoring the environment  
- Transition segment introduces bullroarer faintly  

**Layer 4: Main Procession / Ritual**  
- Bullroarer (deep, reverberating), whip cracking, traditional drums, chanting  
- Single gunshot at height of procession  
- Ascending and descending auditory perspective simulating procession passing by  

**Layer 5: Optional Narration**  
- Voiceover explaining each layer  
- Can be toggled on/off  
- Drop-down menu to explore each layer description  
- Layer-wide volume control

---

## ⏱ Timeline / Automation

| Time (mm:ss) | Layer Focus | Description |
|--------------|------------|-------------|
| 00:00–00:30  | L1         | Silence → fading crickets, soft wind ambient |
| 00:30–01:30  | L1         | Leaves rustle, intermittent small animal sounds, dynamic wind swells |
| 01:30–02:00  | L1→L2      | Transition to bedroom, ambient exterior muffled |
| 02:00–02:45  | L2         | Bedroom ambience, fan, clock, breathing, mattress shifts |
| 02:45–03:00  | L2→L3      | Interior fades out slightly, exterior sounds re-emerge |
| 03:00–03:45  | L3         | Night owl, lone dog, distant vehicle, ambient swell |
| 03:45–04:15  | L3→L4      | Bullroarer faint introduction, crescendo into main procession |
| 04:15–04:50  | L4         | Main procession: bullroarer, whip, drums, chants, gunshot |
| 04:50–05:00  | L4→L1 end  | Descending fade, ambient wind and crickets, return to calm |

> Note: All layers are designed to blend dynamically; transitions simulate spatial and emotional movement.

---

## 🗃 Audio Assets

All audio files are included in `/audio_assets/`:

| Layer | File Example | Notes |
|-------|-------------|-------|
| L1    | layer1_crickets_base.wav | Continuous 5-min loop with fades |
| L2    | layer2_room_ambience.wav | Tiled room with fan, breathing, bed creaks |
| L3    | layer3_dog_bark.wav | Lone dog, night owl, distant vehicle |
| L4    | layer4_bullroarer.wav | Bullroarer, drums, whip, chanting |
| L5    | layer5_narration.mp3 | Optional narration (toggleable) |

> Files should be prepared with **24-bit WAV** or **high-quality MP3** (44.1 kHz or 48 kHz) for best fidelity.  

---

## 🧠 Psychoacoustic Notes

- **Layer 1:** Airborne perspective → dynamic pan & fade to simulate distance  
- **Layer 2:** Close-quarters perception; breathing changes to reflect emotional tension  
- **Layer 3:** Distant warning cues; high-frequency animal cues for subtle alerting  
- **Layer 4:** Rhythm and reverberation simulate procession passing by; low-frequency resonance for immersive depth  
- **Layer 5:** Narration optional; maintains a neutral spatial center  

> Careful layering and dynamic automation ensure each element is **heard in context without masking other layers**.

---

## 🚀 Implementation Notes

- Built for **web playback using Tone.js**  
- Layers can be **toggled and volume-controlled individually**  
- Fully modular structure to allow future expansion or modification  
- Potential for interactive visualizations or generative elements  

---

## 🔗 Links & Resources

- [Live Demo Placeholder – GitHub Pages](#)  
- [Oroo Nights PDF Overview](docs/oroo_nights_soundscape_overview.pdf)  
- [Psychoacoustic Notes PDF](docs/psychoacoustic_insights_notes.pdf)  

---

## 📜 License

Specify your license here (e.g., MIT, Creative Commons).  

---

## 🙏 Acknowledgements

- Sound design inspired by traditional ritual elements and immersive spatial audio techniques  
- Tone.js and open-source web audio ecosystem  


