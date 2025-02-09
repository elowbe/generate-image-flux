# generate-image-flux.neu

## Overview
A specialized image generation template utilizing FLUX technology for producing high-quality images. This workflow incorporates FLUX's unique sampling and guidance methods for enhanced image generation.

### Module Inputs
- **prompt**: Text input defining what image to generate.
- **flux-checkpoint**: Selection of FLUX model checkpoint to use (default: pixelwave_flux1Dev03.gguf).
- **flux-lora**: Selection of FLUX-specific LoRA to apply (default: Hyper-FLUX.1-dev-16steps-lora.safetensors).
- **resolution**: Preset dimension options for output image (e.g., "1024x1024", "1152x896", etc.).

### Module Outputs
- **image**: The generated image output.

### Notes
- Utilizes FLUX guidance and sampling methods for improved image quality
- Supports various resolution presets for flexible output dimensions
- Integrates LoRA models for enhanced generation capabilities
- Default configuration optimized for balanced quality and speed
