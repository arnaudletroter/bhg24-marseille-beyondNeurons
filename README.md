# bhg24-marseille-beyondNeurons

Goals for the BrainHack:
To characterize the spatiotemporal dynamics of calcium signaling in these two glial cell types within the lumbar spinal cord.

WP1: Segmentation of calcium imaging data to identify radial glia and astrocytes
WP2: Analysis of the area under the curve (AUC) of calcium transients under three conditions:
C1: Baseline (ACSF)
C2: TTX treatment to block neuronal activity
C3: TTX combined with a locomotor cocktail
WP3: Mapping the spatial distribution (xy positions) of active astrocytes relative to the central canal

Repository for sharing  resources on timeseries image processing and analysis in calcium imaging

- conversion from ome.tiff to nii.gz format 
  
- image downsampling on 2D (factor x4) + t (factor x 50) dimensions  

- ROI conversion Fiji (Ellipse freehand segmented) -> binary mask of segmentation 

- Affine registration between 2 timeseries
