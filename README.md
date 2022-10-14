## SVP 2022 Workshop 


[Download link for sample data:](https://seattlechildrens1.box.com/v/SVP2022Dataset)
This share contains three files:
1. **Hypertrag_UW13933Slices.zip:** Original image stack courtesy of Anne Kort. This is the original data format provided by the imaging center. This is a massive dataset (uncompressed 32GB) and when unzipped has 3754 TIFF files. The image spacing is 0.0346mm (or 34.6 micron). If you wanto import this dataset at its original resolution, you will need a computer with minimum of 48GB (64GB is better) RAM. We will show you how you use [`ImageStacks`](https://github.com/SlicerMorph/Tutorials/blob/main/ImageStacks/README.md) module of SlicerMorph to effectively import this data into 3D Slicer. 
2. **preview.nrrd:** This is the same dataset above imported at preview resolution of original dataset (each axis is reduced by 4, so resolution is now 0.1384mm) and saved in NRRD format. This dataset can be directly loaded into Slicer. If you have a computer that has 8GB RAM (or less), please only use this dataset.
3. **half_resolution.nrrd:** This is the same dataset above imported at half resolution of original dataset (each axis is reduced by 2, so resolution is now 0.0692mm) and saved in NRRD format. This dataset can be directly loaded into Slicer. If you have a computer that has 16GB RAM (or more), you can use this dataset.
