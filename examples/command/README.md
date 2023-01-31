# Command

This is modified from examples in [whisper.cpp](https://github.com/ggerganov/whisper.cpp).

## Usage

```bash
# On Raspberry Pi, use tiny or base models + "-ac 768" for better performance
./command -m ./models/ggml-tiny.en.bin -ac 768 -t 3 -c 0
```

## Building

```bash
# Install SDL2 on Linux
sudo apt-get install libsdl2-dev

# Install SDL2 on Mac OS
brew install sdl2

make command
```