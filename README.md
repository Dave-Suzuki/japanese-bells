@ -0,0 +1,84 @@
# 日本の鐘 Japanese Bells

A minimalist web-based musical instrument featuring traditional Japanese bell sounds. Play melodies using your keyboard, touch screen, or USB MIDI controller.

🎐 **[Live Demo](https://dave-suzuki.github.io/japanese-bells/)**

## Features

### 🎵 Four Traditional Bell Types
- **Fūrin (風鈴)** - Wind chimes with bright, delicate tones
- **Kagura (神楽)** - Shrine bells with ceremonial resonance  
- **Orin (おりん)** - Singing bowls with meditative sustain
- **Bonshō (梵鐘)** - Temple bells with deep, profound vibrations

### 🎹 Multiple Input Methods
- **Computer Keyboard** - Two rows (Q-P and A-L) mapped to notes
- **Touch Screen** - Tap keys on mobile devices
- **USB MIDI** - Connect any MIDI keyboard for velocity-sensitive playing

### 🎼 Authentic Japanese Scales
- Hirajoshi - Traditional pentatonic scale
- Yo - Bright, folk-inspired scale
- In - Dark, mysterious scale
- Iwato - Ancient ceremonial scale
- Akebono - Dawn scale with unique intervals
- Okinawa - Southern island scale
- Chromatic - All 12 tones for experimental playing

### 🎛️ Audio Controls
- **Volume** - Master output level
- **Reverb** - Spatial depth and ambience
- **Harmonics** - Overtone intensity for richer tones
- **Sustain** - Extended decay time
- **Octave Shift** - ±2 octave range adjustment

### 🌸 Visual Experience
- Falling cherry blossom petals
- Starfield background
- Minimal, Speldosa-inspired interface
- Mobile-responsive design

## Usage

### Keyboard Controls
- **Letter Keys** - Play notes
- **Space Bar** - Play harmonic chord
- **Ctrl/Cmd + Key** - Sustain notes
- **Shift + Key** - Accent (louder) notes

### MIDI Setup
1. Connect USB MIDI keyboard before opening the page
2. Allow browser permission for MIDI devices
3. Look for "MIDI ✓" indicator
4. Play notes starting from C3 (MIDI note 48)
5. Use sustain pedal (CC 64) for sustained notes

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Web Audio API for sound synthesis
- Web MIDI API for controller support
- Responsive design for all screen sizes
- Real-time convolution reverb
- Multiple oscillator synthesis with overtones

## Local Development

1. Clone this repository
2. Open `index.html` in a modern browser (Chrome, Edge, or Opera recommended for MIDI support)
3. No build process required

## Browser Compatibility

- **Full Support**: Chrome, Edge, Opera (including MIDI)
- **Partial Support**: Firefox, Safari (no MIDI)
- **Mobile**: iOS Safari, Chrome Mobile (touch only, no MIDI)

## Credits

Inspired by traditional Japanese instruments and the minimalist design of Klevgrand's Speldosa.

## License

MIT License - Feel free to use and modify for your projects.
