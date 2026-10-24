# Dragon Reader voice pack: Kokoro v1.0, half precision

- `model.onnx`: Kokoro-82M v1.0 (hexgrad, https://huggingface.co/hexgrad/Kokoro-82M), Apache-2.0, as exported by
  sherpa-onnx (k2-fsa, https://github.com/k2-fsa/sherpa-onnx, Apache-2.0), with its weights converted to float16 by
  Dragon Reader's `tools/kokoro-fp16/fp16.py`. Inputs and outputs are unchanged (float32).
- `voices.bin`, `tokens.txt`, `LICENSE`: unchanged from sherpa-onnx's `kokoro-int8-multi-lang-v1_0` release.
- `espeak-ng-data/`: eSpeak NG data (https://github.com/espeak-ng/espeak-ng), GPL-3.0-or-later, unchanged from the
  same release; source at the eSpeak NG repository.
