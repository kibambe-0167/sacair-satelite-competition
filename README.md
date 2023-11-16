# sacair-satelite-competition
SACAIR 2023 Satellite Image Classification Competition

Scikit-image: Offers various functions for image processing and feature extraction.
Rasterio: Handling geospatial raster data.
OpenCV: Provides a wide range of image processing functions.
Scikit-learn: Contains modules for feature extraction, dimensionality reduction, and classification.



1. **Spectral Bands:**
   - Satellite images typically consist of multiple spectral bands (e.g., Red, Green, Blue, Near Infrared, etc.). Statistical measures (mean, standard deviation, minimum, maximum) or spectral indices (NDVI - Normalized Difference Vegetation Index, NDWI - Normalized Difference Water Index) computed from these bands can be powerful features.

2. **Texture Features:**
   - Haralick texture features, Gabor filters, or local binary patterns (LBP) can capture textural information within an image, useful for distinguishing between various land cover types (e.g., forest, urban, water bodies).

3. **Shape and Structure:**
   - Features like object size, shape descriptors (e.g., circularity, elongation), and structural elements (e.g., building footprints, roads) extracted using segmentation techniques or object detection algorithms can be valuable.

4. **Spatial Features:**
   - Spatial relationships among pixels or regions can be crucial. Features like spatial autocorrelation, Moran's I, or Geary's C capture the spatial dependency among neighboring pixels.

5. **Principal Component Analysis (PCA) or Dimensionality Reduction:**
   - Reduce the dimensionality of multi-band data while retaining essential information. PCA can be used to transform the spectral bands into a smaller set of uncorrelated variables.

6. **Convolutional Neural Network (CNN) Features:**
   - Utilize pre-trained CNN models (like VGG, ResNet, etc.) and extract features from intermediate layers. Transfer learning can capture hierarchical features learned from large datasets.

7. **DCT or Fourier Transform Coefficients:**
   - Extract frequency-based features using DCT or Fourier Transform, which could capture specific patterns in different frequency domains.

8. **Land Use/Land Cover (LULC) Indices:**
   - Indices like Land Use/Land Cover classifications, which categorize land into classes (e.g., agriculture, forest, urban) can serve as features.