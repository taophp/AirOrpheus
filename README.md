# AirOrpheus
> Immersive soundscape creator - compose, mix and customize your sonic environments with ease.

** WORK IN PROGRESS **


AirOrpheus is a desktop application that allows you to create custom ambient soundscapes by mixing multiple audio tracks with fine-tuned controls. Create the perfect background atmosphere for work, relaxation, meditation, gaming, or creative activities.

## Features

- **Create Custom Soundscapes**: Mix multiple ambient sounds together to create your perfect sonic environment
- **Fine Control**: Adjust volume, balance, randomness and frequency of each sound
- **Library of Sounds**: Choose from categorized built-in sounds or import your own audio files
- **Save & Load**: Save your favorite combinations as presets and load them anytime

## Installation

### Building from Source

#### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (1.70.0 or newer)
- Audio development libraries:
  - Linux: `libasound2-dev` and `libjack-dev`
  - macOS: No additional dependencies
  - Windows: No additional dependencies

#### Build Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/AirOrpheus.git
cd AirOrpheus

# Build in release mode
cargo build --release

# The binary will be in target/release/airorpheus
```

## Usage

### Quick Start

1. Launch AirOrpheus
2. Click the "+" button to add sounds to your soundscape
3. Adjust volume sliders to balance your mix
4. Use the randomness sliders to control how frequently non-looping sounds play
5. Save your soundscape using File > Save Soundscape

### Creating a New Soundscape

1. Select sounds from the library panel
2. Adjust individual sound parameters:
   - Volume: Set the loudness of each sound
   - Balance: Position sounds in the stereo field
   - Randomness: Control timing and frequency for non-looping sounds
   - Loop: Enable/disable continuous playback
3. Save your creation for later use

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the GNU Affero General Public License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by [Ambient Mixer](https://www.ambient-mixer.com/)
- Default sounds sourced from [Freesound](https://freesound.org/) (see [CREDITS.md](CREDITS.md) for attribution)
