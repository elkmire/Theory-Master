# [Theory Master](https://elkmire.github.io/Theory-Master/)
click here^

## Overview
The Music Theory Tool is an interactive web application designed for musicians, composers, and music theory students. It provides a visual and auditory interface for exploring musical scales, chord progressions, and harmonic relationships.

## Core Features
- Interactive piano keyboard interface
- Real-time scale visualization
- Chord progression generator
- Circle of fifths integration
- Multiple scale types and musical modes
- Mood-based composition assistance
- Advanced chord voicing options

## User Interface Components

### 1. Piano Keyboard
- Two-octave range with clickable keys
- Color-coded visualization:
  - Root note: Pink (#ff006e)
  - Scale notes: Mint green (#00ff9d)
  - Circle of 5ths: Purple (#8a2be2)
  - Circle of 4ths: Orange (#FF8C00)
- Keyboard shortcuts available (A-J keys for first octave)

### 2. Scale and Key Controls
- Scale selector with multiple options:
  - Major/Minor scales
  - Modal scales (Dorian, Phrygian, etc.)
  - Exotic scales (Hungarian, Persian, Japanese, etc.)
- Key selector for all 12 chromatic notes
- Automatic complementary key display (fifth and fourth relationships)

### 3. Chord Progression Generator
- Number of chords selector (2-8 chords)
- Mood selection options:
  - Happy
  - Sad
  - Mysterious
  - Epic
  - Romantic
  - Melancholic
  - Dreamy
  - Tense
  - Peaceful
- Advanced chord options:
  - Seventh chords
  - Extended chords (9th/11th)
  - Complex mode for advanced harmonic variations

## Music Theory Concepts

### 1. Scale Systems
The tool supports various scale systems:

```
Standard Scales:
- Major (Ionian): [0, 2, 4, 5, 7, 9, 11]
- Natural Minor (Aeolian): [0, 2, 3, 5, 7, 8, 10]
- Harmonic Minor: [0, 2, 3, 5, 7, 8, 11]
- Melodic Minor: [0, 2, 3, 5, 7, 9, 11]

Modal Scales:
- Dorian: [0, 2, 3, 5, 7, 9, 10]
- Phrygian: [0, 1, 3, 5, 7, 8, 10]
- Lydian: [0, 2, 4, 6, 7, 9, 11]
- Mixolydian: [0, 2, 4, 5, 7, 9, 10]
- Locrian: [0, 1, 3, 5, 6, 8, 10]

World/Exotic Scales:
- Hungarian Minor: [0, 2, 3, 6, 7, 8, 11]
- Persian: [0, 1, 4, 5, 6, 8, 11]
- Japanese: [0, 2, 5, 7, 8]
- Arabic: [0, 2, 4, 5, 6, 8, 10]
- Egyptian: [0, 2, 5, 7, 10]
- Chinese: [0, 4, 6, 7, 11]
```

### 2. Chord Construction
The tool uses several chord-building systems:

#### Basic Triads
- Major: [0, 4, 7]
- Minor: [0, 3, 7]
- Diminished: [0, 3, 6]
- Augmented: [0, 4, 8]

#### Seventh Chords
- Major 7th: [0, 4, 7, 11]
- Minor 7th: [0, 3, 7, 10]
- Dominant 7th: [0, 4, 7, 10]

#### Extended Chords
- Major 9th: [0, 4, 7, 11, 14]
- Minor 9th: [0, 3, 7, 10, 14]
- Dominant 9th: [0, 4, 7, 10, 14]
- Major 11th: [0, 4, 7, 11, 14, 17]
- Minor 11th: [0, 3, 7, 10, 14, 17]

### 3. Mood-Based Progression Patterns

Each mood has associated chord progression patterns. Here are some examples:

```
Happy:
- I → IV → V → I
- I → VI → IV → V
- I → IV → I → V

Sad:
- I → VI → IV → V
- VI → IV → I → V
- I → III → VI → IV

Epic:
- I → V → VI → IV
- I → bVII → VI → V
- I → III → VI → VII

Mysterious:
- I → bII → IV → bVII
- I → VI → III → VII
- I → V → bVII → IV
```

## Advanced Usage

### 1. Complex Mode Features
When complex mode is enabled:
- Out-of-scale alterations are introduced
- Complementary scale notes are incorporated
- Chromatic alterations are applied
- Enhanced harmonic variety through modal mixture

### 2. Chord Substitution System
The tool includes a sophisticated chord substitution system for progression variation:
```javascript
Substitution Options:
I   → [I, III, VI]
IV  → [IV, II, VI]
V   → [V, VII, III]
VI  → [VI, IV, II]
II  → [II, IV, VII]
III → [III, VI, I]
VII → [VII, V, III]
```

### 3. Audio Engine Features
- Oscillator-based sound synthesis
- Envelope shaping for natural sound decay
- Polyphonic chord playback
- Different octave handling for bass notes
- Variable note duration based on context

## Best Practices

1. Scale Exploration:
   - Start with major and minor scales before exploring exotic ones
   - Use the color-coding system to understand scale relationships
   - Experiment with different keys to understand transposition

2. Chord Progression Creation:
   - Begin with simple progressions (4 chords)
   - Add complexity gradually through chord extensions
   - Use the mood selector to match your musical intention
   - Listen to the relationship between complementary keys

3. Advanced Composition:
   - Combine different moods for verse/chorus structures
   - Use complex mode sparingly for specific effects
   - Experiment with chord substitutions for variation
   - Pay attention to voice leading in extended chords

## Troubleshooting

Common Issues and Solutions:
1. No sound output:
   - Check browser audio permissions
   - Ensure audio context is initialized
   - Verify system audio settings

2. Visual display issues:
   - Refresh the page to reset the keyboard state
   - Check browser compatibility
   - Clear browser cache if colors aren't updating

3. Progression generation:
   - Reduce chord count if progressions seem too complex
   - Disable advanced modes for simpler patterns
   - Reset to default settings if results are unexpected

## Technical Specifications

- Audio: Web Audio API
- Frequency range: 261.63 Hz (C4) to 987.77 Hz (B5)
- Supported browsers: Modern versions of Chrome, Firefox, Safari, Edge
- Scale types: 19 different scale patterns
- Chord types: 12 basic and extended variations
- Progression patterns: 27 base patterns across 9 moods
