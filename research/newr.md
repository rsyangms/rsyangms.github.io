# Newly published #
## Integrating Sentinel-1 ETAD into Standard PSI Processing: A Cost-Effective Approach to Phase,Deformation and Localization Accuracy ## 
### Abstract ###
Abstract—Persistent Scatterer Interferometry (PSI) is widely
used for surface deformation monitoring, but its accuracy is
often limited by atmospheric path delays, orbit errors, and
timing inconsistencies. To address these issues, the European
Space Agency (ESA) released the Sentinel-1 Extended Timing
Annotation Dataset (ETAD), providing refined timing correc
tions that account for instrument, atmospheric, geophysical,
and Doppler-related effects. This study introduces PSI+ETAD:
a sensor-native PSI processing framework that fully exploits
ETAD’s range- and azimuth-direction timing annotations to
jointly enhance interferometric phase quality, deformation time
series accuracy, and PS 3D localization precision — thereby
delivering simultaneous, cost-effective improvements across all
three pillars of operational PSI. Experimental results show
that ETAD integration substantially improves phase quality,
with reductions of 60.77% in the Sum of Phase Differences
(SPD) and 40.3% in the Phase Standard Deviation (PSD). In
deformation velocity estimation, PSI+ETAD achieves a standard
deviation of 5.26 mm/year, compared with 18.64 mm/year for
PSI (uncorrected), 2.82 mm/year for PSI+STF (PSI with spatio
temporal filtering), and 6.34 mm/year for PSI+GACOS (PSI with
GACOS-based tropospheric delay correction), providing a better
balance between noise suppression and signal preservation. In
time-series analysis, ETAD corrections lower the Standard Devi
ation of Displacements (SDD) to 3.65 and the Spatio-Temporal
Consistency (STC) to 2.23. Validation against GNSS confirms
that PSI+ETAD yields the closest agreement with ground-truth
deformation, with the lowest errors (MAE of 3.18 mm and RMSE
of 3.91 mm). For geolocation, mean offsets of 5.566 m in range,
1.736 m in azimuth, and 0.974 m in cross-range are corrected,
with improvements validated against airborne LiDAR data. These
f
indings demonstrate that integrating ETAD into standard PSI
workflows provides a cost-effective and operationally feasible
correction strategy, significantly enhancing phase stability, defor
mation accuracy, and geolocation precision for large-scale InSAR
monitoring in urban and tectonically active regions.
![](fig\6.png)
<br><hr>

## SE-CAE: A Self-Evolving CAE Framework for Noise-Free InSAR ##
### Abstract ###
Abstract—Interferometric synthetic aperture radar (InSAR) is
a pivotal geodetic tool for deformation monitoring, yet mul
tisource noise coupling in time-series data remains a critical
challenge. This study proposes a self-evolving convolutional
autoencoder (SE-CAE) framework to achieve noise-free deforma
tion reconstruction. Validated using Sentinel-1 time-series data
over Kunming, China, SE-CAE outperformed uncorrected data,
spatiotemporal filtering, and GACOS-based methods through
multimetric analysis. Quantitative evaluations demonstrated its
superiority: an 82.01% reduction in standard deviation (STD), a
92.5% reduction in STD of displacements (SDD), and 88.66%
improvement in spatiotemporal consistency (STC), alongside
an 84.31% enhancement in local STC, confirming robustness
across regional and localized scales. Spectral analysis verified
its capacity to eliminate high-frequency noise while preserv
ing deformation signals. Principal component analysis (PCA)
revealed that SE-CAE addresses atmospheric delays (68.10%
explained variance ratio, EVR), orbital errors (22.74% EVR),
and topographic artifacts (2.80% EVR), accounting for 93.64%
of corrected errors. Cross-validation with GNSS measurements
further substantiated its reliability. By integrating deep learn
ing with mechanistic interpretability, SE-CAE advances InSAR
processing with balanced noise suppression, signal fidelity, and
physically meaningful error correction, offering a transformative
solution for high-precision deformation monitoring.
![](fig\5.png)
<br><hr>

## InSAR-based deformation monitoring of high-fill engineered landslides: a case study at Panzhihua Airport,Southwest China ##
### Abstract ###
High-fill engineered landslides challenge infrastructure safety in mountainous regions, characterized by the progressive deformation of the fill body under its own weight and external triggers. Utilizing 163 ascending and 134 descending Sentinel-1 images spanning from 2018 to 2023, this study investigated a landslide at Panzhihua Airport, Southwest China, within a multi-orbit Time-Series InSAR framework. This methodology innovatively combines multi-orbit LOS (Line of Sight) deformation retrieval through InSAR processing, 2D deformation vector decomposition (vertical + slope-parallel directions), and spatiotemporal correlation analysis with geological structure and rainfall patterns. Results show: (i) The average LOS deformation rates in the airport area are 3.58 mm/year for the runway and − 1.37 mm/year for surrounding buildings, indicating stability; while, in the landslide area, the deformation rates decrease to − 37.07 mm/year and − 12.75 mm/year, suggesting active sliding.(ii) Deformation in the landslide area was spatially heterogeneous, characterized by vertical settlement at the rear (max. 45.3 mm/year) and horizontal displacement at the front (max. 53.61 mm/year) of the fill body. (iii) The displacement time series reveals a clear correlation between vertical deformation and rainfall. Across the four declining phases, landslide movement demonstrates strong rainfall coupling, with Spearman's correlation coefficients exceeding 0.5 in most monitored areas. These findings provide valuable insights for managing secondary deformation risks in large-scale fill slopes and contribute to early warning system development in similar geo-engineering contexts.
![](fig\4.png)
<br><hr>

## A PSI targets characterization approach to interpreting surface displacement signals: A case study of the Shanghai metro tunnels ##
### Abstract ###

Persistent Scatterer Interferometry (PSI) is a multi-epoch InSAR method for measuring displacements of Earth's surface over time by exploring the interferometric phase of constantly coherent points, named Persistent Scatterer (PS). PSI has shown its superior capability to monitor linear features with long-distance and large-span characteristics. Nevertheless, the interpretation of estimated displacements over PS is a challenge to overcome. Here, we propose a target characterization approach for multi-epoch InSAR post-processing to efficiently correlate the target's possible deformation types and corresponding deformation characteristics. The PS targets were categorized into elevated (ELV) and ground (GRD) groups. The deformation signals are assigned into four types: Defo-Type I stable, Defo-Type II shallow, Defo-Type III structural, and Defo-Type IV mixed deformation based on the ELV versus GRD differential motion estimation. Our approach is demonstrated over the metro network of Shanghai city, China using High-resolution TerraSAR-X data. The seven-year displacements map along Shanghai metro lines estimated by PSI shows that 85% of the points are relatively stable, while only 0.07% exhibits a significant deformation trend. We performed the stability evaluation along the subway by incorporating velocity, cumulative and relative deformation. It was found that the lines that have been operated for a long time are relatively stable, and obvious deformations were observed on the newly built lines and the extension sections of existing lines. By interpreting deformation types, We inferred that the displacements along metro lines mainly corresponded to Defo-Type II, and the areas with obvious deformation involve the superposition of multiple deformation types.

![](fig\1.png)

<br><hr>

## Investigating deformation along metro lines in coastal cities considering different structures with InSAR and SBM analyses ##
### Abstract ###
The metro system solves traffic congestion in urban transportation while bringing potential deformation risks, especially in tunnels built in typical soft deposits in coastal cities. Time-series Synthetic Aperture Radar Interferometry (TS-InSAR) is an effective tool for monitoring land subsidence in urban areas. However, the different structures of metro lines, such as elevated tracks, ground lines, and tunnels, were often neglected in previous studies. Here, we introduced a Station Based Monitoring (SBM) method combined with InSAR analyses for metro safety monitoring. TS-InSAR provided the measurements along the elevated rails and ground lines. For tunnels, the TS-InSAR and SBM were jointly performed to deduct partial deformation under tunnels caused by land subsidence. The proposed metro system monitoring strategy was demonstrated and validated over the Shanghai Metro and Tianjin Rail Transit in the coastal cities of China. The results show that most deformed sections are located on the metro network's periphery, with velocities around −5 mm/year in Shanghai and −25 mm/year in Tianjin. The spatial distribution and temporal evolution of deformation characteristics along the two cases were then explored and compared. The proposed hazard matrix combining geological conditions and passenger density provided a more comprehensive assessment of potential hazards. The study highlights that InSAR and SBM analyses could be potentially applied to monitoring metro systems considering different structures.
![](fig\2.png)

<br><hr>

## Decomposing and mapping different scales of land subsidence over Shanghai with X- and C-Band SAR data stacks ##

### Abstract ###
Land subsidence can be observed with time-series of Interferometric Synthetic Aperture Radar (InSAR) data. However, existing approaches only reveal subsidence signals that are multi-scale mixed, which is not conducive to the systematic analysis of subsidence of different mechanisms. A deformation signal decomposition (DSD) method based on spectral analysis is used to decompose the deformation extracted by time-series InSAR into three classes of deformation signals. They refer to large-scale deformation related to geological settings, medium-scale deformation caused more by group excavation, and small-scale deformation along linear infrastructures. TerraSAR-X datasets for Shanghai spanning April 2013 to September 2020, and Sentinel-1A datasets spanning January 2016 to September 2020 are used in this study. The results were cross-verified between the TerraSAR-X and Sentinel-1A datasets, and validated against levelling measurements. Subsidence signals caused by different mechanisms were automatically decomposed, which facilitates a systematic analysis for targeted diagnosis of land subsidence signals. A detailed analysis was conducted jointly at three scales of surface displacement, geological conditions, major construction activities, and subsidence mechanisms. It indicated that construction activities were the leading cause of land subsidence, and suggests that local authorities that wish to mitigate surface subsidence may benefit from primarily considering this process.
![](fig\3.png)

<br><hr><br><br>