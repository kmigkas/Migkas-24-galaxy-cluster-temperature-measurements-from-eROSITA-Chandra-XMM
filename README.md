# Migkas-24-galaxy-cluster-temperature-measurements-from-eROSITA-Chandra-XMM
The "Data.fits" file contains all the galaxy cluster data and information used in the Migkas et al. (2024) paper titled "SRG/eROSITA cross-calibration with Chandra and XMM-Newton using galaxy cluster gas temperatures"

The column name description is given below:

1) "Cluster": Name of the galaxy cluster
2) "Region": Region of the cluster (Annulus or Core) which we study and within which we measure the temperatures. Annulus refers to 0.2-0.5 R500 and Core to <0.2 R500.
3) "T_eRO_full": eROSITA temperature in the 0.7-7 keV (full) band
4) "T_eRO_full_low": Lower 1σ uncertainty of T_eRO_full
5) "T_eRO_full_high": Upper 1σ uncertainty of T_eRO_full
6) "T_CXO_XMM_full": Chandra or XMM-Newton temperature (depends on the used instrument, see last column) in the 0.7-7 keV band
7) "T_CXO_XMM_full_low": Lower 1σ uncertainty of T_CXO_XMM_full
8) "T_CXO_XMM_full_high": Upper 1σ uncertainty of T_CXO_XMM_full
9) "T_eRO_soft": eROSITA temperature in the 0.5-4 keV (soft) band
10) "T_eRO_soft_low": Lower 1σ uncertainty of T_eRO_soft
11) "T_eRO_soft_high": Upper 1σ uncertainty of T_eRO_soft
12) "T_CXO_XMM_soft": Chandra or XMM-Newton temperature in the 0.5-4 keV band
13) "T_CXO_XMM_soft_low": Lower 1σ uncertainty of T_CXO_XMM_soft
14) "T_CXO_XMM_soft_high": Upper 1σ uncertainty of T_CXO_XMM_soft
15) "T_eRO_hard": eROSITA temperature in the 1.5-7 keV (hard) band
16) "T_eRO_hard_low": Lower 1σ uncertainty of T_eRO_hard
17) "T_eRO_hard_high": Upper 1σ uncertainty of T_eRO_hard
18) "T_CXO_XMM_hard": Chandra or XMM-Newton temperature in the 1.5-7 keV band
19) "T_CXO_XMM_hard_low": Lower 1σ uncertainty of T_CXO_XMM_hard
20) "T_CXO_XMM_hard_high": Upper 1σ uncertainty of T_CXO_XMM_hard
21) "Z_full": Best-fit metal abundance used in determination of T_eRO_full (fixed Z_full) and was constrained simultaneously with T_CXO_XMM_full, where Z_full was free to vary
22) "Z_soft": Same as Z_full but for T_eRO_soft and T_CXO_XMM_soft
23) "Z_hard": Same as Z_full but for T_eRO_hard and T_CXO_XMM_hard
24) "z": Redshift of cluster
25) "R500": Apparent R500 cluster radius (arcminutes)
26) "NHtot": Total hydrogen column density in 1/cm^2 as given in Willingale et al. (2013)
27) "Glon": Galactic longitude (degrees)
28) "Glat": Galactic latitude (degrees)
29) "CXO_XMM_telescope": Telescope used for measuring T_CXO_XMM values
