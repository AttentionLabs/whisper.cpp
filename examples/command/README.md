# Command

This is modified from examples in [whisper.cpp](https://github.com/ggerganov/whisper.cpp).

## Usage

```bash
# On Raspberry Pi, use tiny or base models + "-ac 768" for better performance
./command -m ./models/ggml-tiny.en.bin -ac 768 -t 3 -c 0
```

## Building
```bash
# Need Cmake.
# See https://github.com/AttentionLabs/onnx-runtime/blob/main/raspberry-pi-4b/build.sh
sudo apt-get install libsdl2-dev --yes
```

```bash
make command
```