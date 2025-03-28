# blend2stl

Simple library to export blender files (`.blend`) to STL format (`.stl`) with scale. 

## Usage:

In CLI

```bash
python -m blend2stl --input folder-with-blend --output folder-with-stl --scale 500
```

In python code

```python
from blend2stl import blend2stl

# Define input/output paths and scale
input_folder = "/path/to/blend/files"
output_folder = "/path/to/output/stls"
scale = 1000  # Optional, default is 1000

# Run export
blend2stl(input_folder, output_folder, scale)
```

