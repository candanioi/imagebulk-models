# ImageBulk models

On-device AI models used by the ImageBulk Android app, kept here as release assets so the
app always downloads from this repository.

| Release | File | Used for | Licence |
|---|---|---|---|
| `isnet-v1` | `isnet-general-use.onnx` | HD background removal (IS-Net) | Apache-2.0 |
| `migan-v2` | `migan_pipeline_v2.onnx` | Magic eraser (MI-GAN, Picsart) | MIT |
| `esrgan-v1` | `realesr-general-x4v3.onnx` | AI enlarge (Real-ESRGAN) | BSD-3-Clause |

The **Mirror models** workflow downloads each file from its public source and publishes it
here. It skips files that are already published. Release notes record each file's SHA-256.
