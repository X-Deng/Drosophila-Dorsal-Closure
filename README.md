# Drosophila Dorsal Closure: Optical Flow & Protein Dynamics Analysis  

## Overview  
This project analyzes the process of **Drosophila dorsal closure** using **optical flow techniques** and **intensity quantification** to study protein dynamics over time. It employs image processing and statistical analysis to track and measure the behavior of proteins **Cadherin (Ch0)** and **ILK-GFP (Ch1)** across multiple time points.

## Dataset  
**2D + Time + Channels**
- Image dimensions: **444 × 1556 pixels**  
- **20 time points**  
- **2 channels**:  
  - Channel 0 (Cadherin - Protein A): Used for image registration.  
  - Channel 1 (ILK-GFP - Protein B): Observe its dynamics relative to Cadherin.  

## Objective  
Analyzing protein dynamics over time.

## Approach  
1. **Registration**: Use Optical Flow (TV-L1) on Channel 0 for accurate alignment.  
2. **Intensity Extraction**: Quantify pixel intensities in areas of interest for both channels.  
3. **Statistical Analysis**: Analyze kymographs to identify temporal and spatial relationships.

## Registration Result

**Unregistered time series**:

![Unregistered](MAXz8z11_t07t27_Ecadtom.gif)

**Registered time series**:

![Registered](Area1_warped_Ecadtom.gif)








