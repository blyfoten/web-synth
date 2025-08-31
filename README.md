# Web-Synth with Just Intonation

**[🎹 Try it now!](https://html-preview.github.io/?url=https://github.com/blyfoten/web-synth/raw/refs/heads/main/index.html)**

A simple web-based synthesizer that can be played directly in the browser. 
It uses the Web Audio API to generate sound and offers basic features for exploring different tuning systems:

## 🎹 Features

### Keyboard
- **Simple keyboard** with one octave (7 white + 5 black keys)
- **Polyphony** - play multiple notes simultaneously
- **Touch/Mouse support** - works on most devices
- **Sliding/Glissando** - hold down a key and slide between others for smooth transitions
- **Visual feedback** - active keys are highlighted

### Tuning
- **Equal Temperament** - standard Western tuning
- **Just Intonation** - pure tuning with mathematically perfect intervals
- **Key selection** - choose root note for Just Intonation
- **Real-time switching** - switch between tunings while playing

### Sound Shaping
- **Waveforms**: Sine, Triangle, Sawtooth, Square
- **ADSR envelope**: Attack, Decay, Sustain, Release
- **Filter**: Low-pass with cutoff & resonance
- **Delay**: Mix, time, feedback
- **Reverb**: Mix, decay time, room-size, pre-delay
- **Volume control**

### Oscilloscope
- **Triggered visualization** - stable, synchronized waveform display
- **C-referenced time** - shows exactly 2 C wavelengths for comparison
- **Color coding** - each note has its own color
- **Real-time updates** - see differences between Equal and Just intonation

## 🎵 Usage

### Basic playing
1. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari)
2. Click or tap keys to play notes
3. Use multiple fingers for polyphony

### Advanced techniques
- **Sliding**: Hold down a key and slide between others for glissando effects
- **Tuning comparison**: Switch between Equal and Just to hear differences
- **Key exploration**: Change root note in Just mode for different intervals
- **PANIC button**: Stop all notes immediately

### Sound shaping
- **Waveform**: Choose between different oscillators for different timbres
- **Filter**: Shape the sound with cutoff and resonance
- **Envelope**: Control attack and release for different articulations
- **Effects**: Add delay and reverb for depth and space

## 🔧 Technical Details

### Tuning Systems
- **Equal Temperament**: 12-tone equal temperament (2^(1/12))
- **Just Intonation**: 5-limit pure tuning with perfect intervals
- **Intervals**: Unison (1:1), Minor Second (16:15), Major Second (9:8), Minor Third (6:5), Major Third (5:4), Perfect Fourth (4:3), Tritone (45:32), Perfect Fifth (3:2), Minor Sixth (8:5), Major Sixth (5:3), Minor Seventh (9:5), Major Seventh (15:8)

### Oscilloscope
- **Trigger**: Synchronizes all waveforms to upward zero crossing
- **Time window**: Shows exactly 2 C wavelengths for consistent reference
- **Phase comparison**: Shows phase differences between intervals in different tunings

### Web Audio API
- **Oscillators**: Real-time sound generation
- **Filter**: BiquadFilter for sound shaping
- **Effects**: Delay and Convolver for reverb
- **Analysis**: FFT for waveform visualization

## 📁 Project Structure

- `index.html` – Complete application (HTML, CSS, JavaScript)
- `README.md` – This documentation

The project is completely self-contained and requires no server or external dependencies.

## 🎯 Use Cases

- **Music education**: Understand differences between tuning systems
- **Composition**: Explore just intonation for new timbres
- **Experimentation**: Test different sound shaping and effects
- **Learning**: Simple way to explore Web Audio API concepts

## 🔮 Future Ideas

- MIDI support for external controllers
- More waveforms and sound modules
- Preset system for sound settings
- Recording and export functions
- More tuning systems (Pythagorean, Meantone, etc.)

## 📄 License

MIT License - see below for full license text.

---

**MIT License**

Copyright (c) 2024 Web-Synth

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

*Created to explore mathematics, music, and web technology.*
