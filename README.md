# ETHER's speech models (THE SCRIBE)

The speech models that [ETHER: Portal ITC Spirit Box](https://play.google.com/store/apps/details?id=ddt.radio.ghostbox.spiritcloud)
downloads when someone turns on THE SCRIBE (Pro, English). ETHER runs them on the phone with
[sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx); nothing is sent anywhere. The files are attached to the release
[`v1`](../../releases/tag/v1), each an unchanged copy, and ETHER checks every one against its SHA-256 below before using it.

## Kroko-EN-Community-128-L-Streaming-001

By Banafo ([Kroko ASR](https://huggingface.co/Banafo/Kroko-ASR)), licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The five `Kroko-EN-Community-128-L-Streaming-001-*` files
are the parts of the model's `.data` file, taken out unchanged (with Banafo's agreement) so that plain sherpa-onnx can load
them. They remain under CC BY-SA 4.0.

## SenseVoice-Small, int8

SenseVoice-Small by Alibaba Group ([FunAudioLLM](https://github.com/FunAudioLLM/SenseVoice)), int8 conversion by the
sherpa-onnx project (`sherpa-onnx-sense-voice-zh-en-ja-ko-yue-int8-2024-07-17`), used under the FunASR Model Open Source
License Agreement 1.1 ([LICENSE-FunASR-Model-1.1.txt](LICENSE-FunASR-Model-1.1.txt)).

## SHA-256

| File | SHA-256 |
|---|---|
| `Kroko-EN-Community-128-L-Streaming-001-decoder.onnx` | `5a16a66500ebfa261977239113faecc550aa1e3d18222a580d078dd6386e58e6` |
| `Kroko-EN-Community-128-L-Streaming-001-encoder.onnx` | `26e2fe9f7a61f47661dbd096b3359e12b04db45e72f1ab0f7af97a24e95c976c` |
| `Kroko-EN-Community-128-L-Streaming-001-header.json` | `0b2dd949c6eba4b439f034a561591510f6b7067fc998f536db298e224d587089` |
| `Kroko-EN-Community-128-L-Streaming-001-joiner.onnx` | `a33f20646e06b729b99fdbce411e7c30e83964ed7c681d590b0bdc78126051cf` |
| `Kroko-EN-Community-128-L-Streaming-001-tokens.txt` | `52b6eda67d5b046551a40f89afb994549d71e03c19e1e57d0549be202fb57c9b` |
| `sherpa-onnx-sense-voice-zh-en-ja-ko-yue-int8-2024-07-17-model.int8.onnx` | `c71f0ce00bec95b07744e116345e33d8cbbe08cef896382cf907bf4b51a2cd51` |
| `sherpa-onnx-sense-voice-zh-en-ja-ko-yue-int8-2024-07-17-tokens.txt` | `f449eb28dc567533d7fa59be34e2abca8784f771850c78a47fb731a31429a1dc` |
