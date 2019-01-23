# geoWrench: A mesh processing toolbox for geometrical acoustics

Mesh manipulation includes the following three operations: 

- Segmentation:

Region growing point cloud segmentation decomposes the model to several segments with a set of features.

- Disassembler:

One can load the segment's features and identify each segment based on them. Knowing which segments should be simplified, current folder contains required simplification codes and result will be accessible in mesh format. 

Acoustic properties can be assigned easily here too for each segment.

- Assembler:

One can choose which segments either simplified or not should be in the final model. The final model can have information about the acoustic properties for mesh vertices.
