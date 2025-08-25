# Geo-referencing of historical images.

This repo contains the code of the publication [Polar perspectives: a deep dive into geo-referencing historical Antarctic photos]{https://doi.org/10.1080/17538947.2024.2406384}, to geo-reference historical images of the TMA archive. The folder "src" contains own code for geo-referencing, the folder external contains the algorithms used for tie-point extraction/matching (Superglue and Lightglue).
The "georef"-function in the src folder can be used as a startin point for the geo-referencing with the three main methods "georef_sat", "georef_img" & "georef_calc".

Please note that this repo is currently created specifically for the TMA archive & some adapations are required to have it work with another data. For possible questions please open an issue. 
However, the code will be regularly updated to add more functions, generalize it more and add some data! 
