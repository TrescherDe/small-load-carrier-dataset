Small Load Carrier Dataset
===========================

This repository contains four image datasets used in the paper:

**Analyzing Feature Relevance Under Occlusion in Small Load Carrier Detection**

with the github: https://github.com/TrescherDe/Visualizing-and-Interpreting-Neural-Network-Features/tree/main

Datasets
--------

Each dataset contains 500 images and is split into `train/` and `val/` subsets.

- **Real**: A dataset containing real images of small load carriers and a small storage box with material properties similar to the small load carrier.

- **Storage Box**: The baseline synthetic dataset containing images generated using Blender and 3D meshes of small load carriers and a small storage box with similar material properties.

- **SD-V1**: A baseline-extended dataset augmenting the baseline using Stable Diffusion.

- **SD-V2**: A baseline-extended dataset augmenting the baseline using Stable Diffusion, focusing on photorealism.

- **Test video**: A dataset containing real images of the small load carrier, a small storage box with similar material properties, and other distracting objects in a possible use case scenario.


Citation
--------

If you use these datasets, please cite this repository:

::

    @misc{small-load-carrier-dataset,
      title        = {small-load-carrier-dataset},
      author       = {Trescher, Denis and Haag, Waldemar},
      year         = {2025},
      note         = {Available at https://github.com/TrescherDe/small-load-carrier-dataset}
    }

License
-------

This dataset is available under the `Creative Commons Attribution 4.0 International (CC BY 4.0) License <https://creativecommons.org/licenses/by/4.0/>`_.

You are free to share and adapt the material for any purpose, even commercially, as long as you provide proper attribution.
