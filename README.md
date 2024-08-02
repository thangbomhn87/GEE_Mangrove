# GEE_Mangrove Traits and Uncertainty Mapping 

Author: Nguyen An Binh, Leon T. Hauser, Matías Salinero-Delgado, Pham Viet Hoa, Giang Thi Phuong Thao, Jochem Verrelst

This is a guideline for running a GPR model for mapping mangrove traits through Google Earth Engine (GEE) Python API

For more information, please refer to the article entitled: Monitoring mangrove traits through optical Earth observation: Towards spatio-temporal scalability using cloud-based Sentinel-2 continuous time series (https://doi.org/10.1016/j.isprsjprs.2024.06.007)

Please email nabinh@hcmig.vast.vn for any further information.

* Folder **GPR_Parameters**: Contains GPR retrieval models for Leaf area index (LAI), Leaf chlorophyll content (Cab), Leaf water content (Cw), and Leaf Dry Matter Content (Cm). These models will be used in the Colab Notebook for mapping specific mangrove traits (LAI, Cab, Cw, Cm) simultaneously with uncertainties per pixel.
  
* Folder **GPR_Python**: Contains Python script (also can run in Google Colab) for mapping mangrove traits and pixel-wise uncertainty.
