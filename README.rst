Small Load Carrier Dataset
===========================

This repository contains four image datasets used in the paper:

**Analyzing Feature Relevance Under Occlusion in Small Load Carrier Detection**

with the github: https://github.com/TrescherDe/Visualizing-and-Interpreting-Neural-Network-Features/tree/main

Datasets
--------

Each dataset contains 500 images and is split into `train/` and `val/` subsets.

- **Real**: A real-world image dataset containing the small load carrier and a visually similar storage box. The objects share similar material properties, making them visually challenging to distinguish.

- **Storage Box**: A synthetic baseline dataset generated using Blender and 3D object meshes. It includes the small load carrier and a similar storage box rendered with simple lighting and backgrounds.

- **SD-V1**: A Stable Diffusion-augmented version of the Storage Box dataset. It enhances variability by generating synthetic variations with general style prompts.

- **SD-V2**: A photorealism-focused version of the SD-V1 dataset. The synthetic images are generated using Stable Diffusion with prompts optimized for photorealistic textures and lighting.



Citation
--------

If you use these datasets, please cite this repository:

::

    @misc{small-load-carrier-dataset,
      title        = {small-load-carrier-dataset},
      author       = {Denis Trescher and Waldemar Haag},
      year         = {2025},
      note         = {Available at https://github.com/TrescherDe/small-load-carrier-dataset}
    }

License
-------

This dataset is available under the `Creative Commons Attribution 4.0 International (CC BY 4.0) License <https://creativecommons.org/licenses/by/4.0/>`_.

You are free to share and adapt the material for any purpose, even commercially, as long as you provide proper attribution.
