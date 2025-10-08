# Quantum Music Composer  

**Quantum Music Composer** is an open-source project that explores the intersection of **quantum-inspired algorithms**, **Peruvian huayno rhythms**, and **jazz harmony**.  
It generates melodies using a **quantum-inspired random walk**, applies **Andean pentatonic scales** and **huayno rhythmic structures**, and harmonizes them with **ii–V–I jazz progressions**.  
The system outputs **MIDI files**, ready to be used in digital audio workstations (DAWs) or notation software.  

---

## 📖 Table of Contents  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Examples](#examples)  
- [Methodology](#methodology)  
- [Roadmap](#roadmap)  
- [Contributing](#contributing)  
- [License](#license)  

---

## ✨ Features  
- **Quantum-inspired random walk** to generate melodic contours.  
- **Huayno rhythmic cells** in 2/4 time with characteristic upbeat accents.  
- **Jazz harmonic framework** with ii–V–I cycles and optional swing.  
- **Optional Markov learner** to adapt melodic transitions from an external MIDI corpus.  
- **MIDI export** for playback, editing, and orchestration in any DAW.  
- **CLI interface** with configurable parameters (tempo, key, mode, swing, bars).  

---

## 📂 Project Structure 
quantum-music-composer/
├─ README.md # Project documentation
├─ LICENSE # License information
├─ requirements.txt # Python dependencies
├─ src/ # Core source code
│ ├─ quantum_walk.py # Quantum-inspired random walk generator
│ ├─ scales_rhythm.py # Huayno scale definitions and rhythm templates
│ ├─ harmony.py # Jazz harmonic progressions
│ ├─ learner.py # Markov chain learner for MIDI corpus
│ ├─ composer.py # Composition pipeline
│ └─ cli.py # Command-line interface
├─ examples/ # Example configurations and outputs
│ ├─ demo_config.json
│ └─ output_demo.mid
└─ data/ # Optional training data
└─ midi_corpus/

