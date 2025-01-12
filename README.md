# Piano SVG Collection

# repo

https://github.com/pleabargain/piano_SVG

A collection of SVG files illustrating piano chords, chord progressions, scales, and music theory concepts. This repository serves as a visual reference for musicians learning piano theory and chord structures.

# motivation
a) I'm learning piano and I want to visualize the chords and chord progressions

b) it was fun to make :)

## Contents

### Individual Chords
- Basic chords (A through G)
- Sharp chords (A♯, C♯, D♯, F♯, G♯)
- Full piano keyboard layout (`piano.svg`)

### Chord Visualization Rules
- All chords start with their root note as the leftmost key
- Keys are highlighted in pink to show which ones to play
- Clear note labels for all keys
- Comments in SVG describe the role of each note in the chord (root, third, fifth, etc.)

### Major Scales
- Natural scales (A through G)
- Sharp scales (F♯, G♯, A♯/B♭)
- Flat scales (D♭, E♭)
Each scale visualization shows:
- All eight notes of the scale
- Highlighted keys in pink
- Clear note labels
- Enharmonic equivalents where applicable

### Music Theory Concepts
- `circle_of_fifths.svg` - Visual representation of the Circle of Fifths, a fundamental concept in music theory showing the relationship between different keys

### Common Chord Progressions
- `I_IV_V_progression.svg` - The I-IV-V progression, one of the most common chord progressions in popular music
- `I_vi_IV_V_progression.svg` - The I-vi-IV-V progression, another popular progression used in many songs
- `i_III_IV_V_VI_progression_A_minor.svg` - The House of the Rising Sun progression (Am - C - D - F - E)
- `i_III_IV_V_VI_progression_C_minor.svg` - A minor key progression showing the relationship between minor and major chords in the natural minor scale

### Style Guide
- `style_guide.json` - Comprehensive documentation of SVG styling patterns used across the collection, including colors, dimensions, spacing, typography, and key ordering rules
- Single chord SVGs now use full-window dimensions (960x1120 pixels) for enhanced visibility
- Consistent scaling of all elements (keys, fonts, spacing) to maintain proportions at larger size

### SVG Dimensions
- Single Chord Visualizations: 960x1120 pixels for optimal visibility
  - Piano keys scaled proportionally (white keys: 64px width, black keys: 48px width)
  - Larger font sizes for better readability (title: 80px, key labels: 40px)
  - Centered layout with 256px spacing on each side
- Multiple Chord Progressions: 120px per chord width (maintained for progression layouts)

## Usage

These SVG files can be:
- Opened in any web browser
- Imported into vector graphics software (like Inkscape or Adobe Illustrator)
- Embedded in web pages or documentation
- Used as visual aids for music education

## File Naming Convention

- Basic chords are named as `[Note]_chord.svg` (e.g., `C_chord.svg`)
- Sharp chords are named as `[Note]_sharp_chord.svg` (e.g., `C_sharp_chord.svg`)
- Major scales are named as `[Note]_major_scale.svg` (e.g., `c_major_scale.svg`)
- Chord progressions use Roman numeral notation (e.g., `I_IV_V_progression.svg`)

## Purpose

This collection is designed to help:
- Music students visualize chord structures and scales on a piano
- Teachers create educational materials
- Musicians reference common chord progressions and scales
- Anyone learning music theory understand key concepts through visual aids

## Recent Updates
- Updated single chord SVG dimensions to 960x1120 pixels for enhanced visibility
- Added chord visualization rule: chords must start with root note
- Added minor key progression visualization (i-III-IV-V-VI in C minor)
- Created style guide documentation (style_guide.json)
- Added major scales collection including natural, sharp, and flat scales
- Added G# major scale visualization
- Added A#/Bb major scale visualization with proper note labeling
- Updated file naming conventions to include scales
- Expanded README documentation to cover scale visualizations
