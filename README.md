# OmniNodes-ComfyUI (TensorVizion)

A collection of **ComfyUI custom nodes** for audio processing and model utilities.

## Nodes Included

### Audio Nodes
- **Audio Beat Detect** (`audio_beat_detect_node.py`)
- **Audio Normalize** (`audio_normalize_node.py`)
- **Audio Spectrogram** (`audio_spectrogram_node.py`)
- **Audio Waveform** (`audio_waveform_node.py`)

### Model Utilities
- **CLIP Text Compare** (`clip_text_compare_node.py`)
- **CLIP Text Weight** (`clip_text_weight_node.py`)
- **LoRA Info** (`lora_info_node.py`)
- **LoRA Stack** (`lora_stack_node.py`)
- **Model Block Freeze** (`model_block_freeze_node.py`)
- **Weighted Model Merge** (`model_merge_weighted_node.py`)

## Installation (ComfyUI)

1. Locate your ComfyUI install folder.
2. Copy this repo into:
   - `ComfyUI/custom_nodes/`
3. Restart ComfyUI.

After restart, the nodes should appear in the ComfyUI UI under the categories defined by each node.

## Configuration Files
This repo also includes JSON configuration files under:
- `tensorvizion_node_configs/tensorvizion_configs/`
