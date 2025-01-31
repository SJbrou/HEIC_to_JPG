# HEIC_to_JPG
 Using python to convert HEIC images to JPG with correct "created" date for apple photo's

The pillow, pillow-heif and piexif packages are required.
You can install them using:

```
pip install pillow pillow-heif piexif
```

# Usage
All HEIC photo's from a specified input directory will be converted to JPG photo's in a specified output directory. Set the directory paths in:

```python
# Input and output directories
from_directory = "from"
to_directory = "to"
```