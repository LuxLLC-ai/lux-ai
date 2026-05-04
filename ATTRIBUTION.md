# Third Party Attribution

## Mistral AI — Ministral 3B Instruct 2512

Lux is built on the base model weights of Ministral 3B Instruct 2512, 
developed by Mistral AI and released under the Apache 2.0 License.

The original model weights were retained as the foundation because the 
training was sound and deserved respect. Everything built around those 
weights — the engine, voice pipeline, on-device quantization, companion 
behavior, and Android architecture — was independently designed and built 
by the Clarity Project.

No Mistral infrastructure is used or accessed. Lux runs entirely on your 
device. Nothing leaves.

We are grateful to Mistral AI and the open source community whose work 
made privacy-first AI possible.

Original model: https://huggingface.co/mistralai/Ministral-3-3B-Instruct-2512

## Whisper.cpp

Speech recognition provided by whisper.cpp, compiled for Android ARM64.
https://github.com/ggerganov/whisper.cpp

## Sherpa-onnx

Text to speech provided by sherpa-onnx C-API with Piper voice models.
https://github.com/k2-fsa/sherpa-onnx

## Apache License 2.0

All third party components above are used under the Apache 2.0 License.
See LICENSE file for full license text.

---
Clarity Project — github.com/LuxLLC-ai
