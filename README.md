# Migkas-24-galaxy-cluster-temperature-measurements-from-eROSITA-Chandra-XMM
The "Data.fits" file contains all the galaxy cluster data and information used in the Migkas et al. (2024) paper titled "SRG/eROSITA cross-calibration with Chandra and XMM-Newton using galaxy cluster gas temperatures"

The column name description is given below:

1) "Cluster": Name of the galaxy cluster
2) "Region": Region of the cluster (Annulus or Core) which we study and within which we measure the temperatures. Annulus refers to 0.2-0.5 R500 and Core to <0.2 R500.
3) "T_eRO_full": eROSITA temperature in the 0.7-7 keV (full) band (units: keV)
4) "T_eRO_full_low": Lower 1σ uncertainty of T_eRO_full (units: keV)
5) "T_eRO_full_high": Upper 1σ uncertainty of T_eRO_full (units: keV)
6) "T_CXO_XMM_full": Chandra or XMM-Newton temperature (depends on the used instrument, see last column) in the 0.7-7 keV band (units: keV)
7) "T_CXO_XMM_full_low": Lower 1σ uncertainty of T_CXO_XMM_full (units: keV)
8) "T_CXO_XMM_full_high": Upper 1σ uncertainty of T_CXO_XMM_full (units: keV)
9) "T_eRO_soft": eROSITA temperature in the 0.5-4 keV (soft) band (units: keV)
10) "T_eRO_soft_low": Lower 1σ uncertainty of T_eRO_soft (units: keV)
11) "T_eRO_soft_high": Upper 1σ uncertainty of T_eRO_soft (units: keV)
12) "T_CXO_XMM_soft": Chandra or XMM-Newton temperature in the 0.5-4 keV band (units: keV)
13) "T_CXO_XMM_soft_low": Lower 1σ uncertainty of T_CXO_XMM_soft (units: keV)
14) "T_CXO_XMM_soft_high": Upper 1σ uncertainty of T_CXO_XMM_soft (units: keV)
15) "T_eRO_hard": eROSITA temperature in the 1.5-7 keV (hard) band (units: keV)
16) "T_eRO_hard_low": Lower 1σ uncertainty of T_eRO_hard (units: keV)
17) "T_eRO_hard_high": Upper 1σ uncertainty of T_eRO_hard (units: keV)
18) "T_CXO_XMM_hard": Chandra or XMM-Newton temperature in the 1.5-7 keV band (units: keV)
19) "T_CXO_XMM_hard_low": Lower 1σ uncertainty of T_CXO_XMM_hard (units: keV)
20) "T_CXO_XMM_hard_high": Upper 1σ uncertainty of T_CXO_XMM_hard (units: keV)
21) "Z_full": Best-fit metal abundance used in determination of T_eRO_full (fixed Z_full) and was constrained simultaneously with T_CXO_XMM_full, where Z_full was free to vary (units: solar abundance Z_solar)
22) "Z_soft": Same as Z_full but for T_eRO_soft and T_CXO_XMM_soft (units: solar abundance Z_solar)
23) "Z_hard": Same as Z_full but for T_eRO_hard and T_CXO_XMM_hard (units: solar abundance Z_solar)
24) "z": Redshift of cluster
25) "R500": Apparent R500 cluster radius (units: arcminutes)
26) "NHtot": Total hydrogen column density as given in Willingale et al. (2013) (units: 1/cm^2)
27) "Glon": Galactic longitude (units: degrees)
28) "Glat": Galactic latitude (units: degrees)
29) "CXO_XMM_telescope": Telescope used for measuring T_CXO_XMM values

#Note: Some cluster regions appear twice, due to the temperature having been measured with both Chandra and XMM-Newton. In such cases, the eROSITA temperature might differ for the same cluster region, since different masks were used and different fraction of the region is covered by Chandra and XMM-Newton, with the former sometimes not covering the full 0.2-0.5 R500 annulus.    
