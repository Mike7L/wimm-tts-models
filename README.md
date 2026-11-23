# wimm-tts-models

Prebuilt Core ML (`.mlpackage`, INT8/FP16 for iOS 17+ and macOS 14+ Apple Neural Engine) + SQLite on-device Russian TTS asset bundles for Wimm (`TeraSpeech`).

## Credits & Licenses

- **TeraTTSv2 (`ru_f2`)** — upstream [`TeraSpace/TeraTTSv2`](https://huggingface.co/TeraSpace/TeraTTSv2) (OpenRAIL-M).
- **RUAccent** — upstream [`RUAccent`](https://github.com/Den4ikAI/ruaccent) dictionary and homograph/stress models (MIT).

## Reproducibility

Bundles in Releases are generated from upstream assets using `scripts/build_teratts_coreml.py` in [`Mike7L/wimm-core`](https://github.com/Mike7L/wimm-core).
