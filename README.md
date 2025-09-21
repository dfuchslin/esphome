# esphome

Collection of ESPHome devices


## Install

```
brew install esphome
```

## Flashing:

```
esphome run announcement-test.yaml
```

#### References

Really nice setup: Https://github.com/wolfg1969/my-esphome

Convert stereo to mono 16/44100 flac:
`ffmpeg -i "input.wav" -af aformat=s16:44100 -c:a flac -compression_level 12 -ac 1 "output.flac"`
