# comfycli-sample-recipes
Sample environment recipes for [comfycli](https://github.com/richinsley/comfycli)

## Installation
```bash
comfycli env pull recipes https://github.com/richinsley/comfycli-sample-recipes.git
```

## Usage

```bash
# Create a ComfyUI environment with ControlNet for SDXL and name it 
comfycli env create --recipe comfycli-sample-recipes/controlnet_SDXL --name SDXLControlNet

# Run ComfyUI in the SDXLControlNet environment
comfycli env runcomfy SDXLControlNet
```