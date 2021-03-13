Title:
	Oceanic Advection Controls Mesoscale Mixed Layer Heat Budget and Air-sea Heat Exchange in the Southern Ocean

Authors: 
Yu Gao (ygao@rsmas.miami.edu, https://orcid.org/0000-0002-5123-2704) Rosenstiel School of Marine and Atmospheric Sciences (RSNAS), University of Miami, Miami, FL
Igor Kamenkovich (ikamenkovich@miami.edu), RSMAS, University of Miami, Miami, FL
Natalie Perlin (nperlin@rsmas.miami.edu), RSMAS and Cooperative Institute for Marine and Atmospheric Studies (CIMAS), University of Miami, Miami, FL
Benjamin Kirtman (bkirtman@rsmas.miami.edu), RSMAS and CIMAS, University of Miami, Miami, FL

Abstract: We analyze the role of mesoscale heat advection in the Southern Ocean mixed layer (ML) heat budget using a regional high-resolution coupled model, with realistic atmospheric forcing and an idealized ocean component. In order to test if the overall current speed affect our conclusion, the simulations are carried out in two distinct cases: one with overall strong current (SC case) and the other with overall weak current (WC case). Mesoscale currents are defined with two different spatial filters to explore the scale dependence of mesoscale air-sea coupling: the departure from 300-km running average represents small-mesoscale, while the departure from zonal-mean anomalies represents large-mesoscale. The data in this collection is based on numerical simulations in Regional Ocean–Atmosphere Model (ROAM, Perlin et al 2020, DOI: https://doi.org/10.1016/j.ocemod.2020.101660.) 

Key words: Southern Ocean; Ocean Mixed layer; heat budget; Mesoscale; air-sea interaction

Contents: 

1) Data output from atmospheric model simulations: 

"atmospheric_model_data/CO2_SE_SST_W10mN_TauX_TauY_U10m_V10m_daily.nc" and "atmospheric_model_data/CO2_WE_SST_W10mN_TauX_TauY_U10m_V10m_daily.nc"

Their content includes:

Dimensions:  (nlat_rho: 122, nlon_rho: 306, nlons_rho: 306, time: 735)
Dimensions without coordinates: nlat_rho, nlon_rho, nlons_rho, time
Data variables:
    Wstr2    (time, nlat_rho, nlons_rho) float32 ...
    SST2     (time, nlat_rho, nlons_rho) float32 274.6 275.2 ... 286.8 286.8
    U10m2    (time, nlat_rho, nlons_rho) float32 ...
    V10m2    (time, nlat_rho, nlons_rho) float32 ...
    W10mN2   (time, nlat_rho, nlons_rho) float32 12.22 12.29 ... 9.797 9.753
    TauX2    (time, nlat_rho, nlons_rho) float32 0.2507 0.254 ... 0.1394 0.1374
    TauY2    (time, nlat_rho, nlons_rho) float32 0.05018 0.04944 ... 0.04877
    lon2ocn  (nlat_rho, nlon_rho) float32 42.26 42.38 42.5 ... 77.57 77.68 77.8
    lat2ocn  (nlat_rho, nlon_rho) float32 -49.96 -49.96 -49.96 ... -40.03 -40.03

2) Binned statistics between multiple pair of variables:

"Strong_SSTA_eddy_adv_300km_filter_binned_statistics_2016.nc"
"Strong_shfluxa_SSTA_300km_binned_statistics_2016.nc"
"Strong_shfluxa_eddy_adv_300km_binned_statistics_2016.nc"
"Strong_temp1_rate_eddy_adv_300km_binned_statistics_2016.nc"
"Strong_temp1_rate_eddy_adv_zonal_filter_binned_statistics_2016.nc"
"Strong_temp1_rate_total_adv_300km_binned_statistics_2016.nc"
"Strong_temp_rate_eddy_adv_binned_statistics_2016.nc"
"Strong_temp_rate_eddy_adv_zonal_filter_binned_statistics_2016.nc"
"Strong_temp_rate_total_adv_binned_statistics_2016.nc"
"Weak_SSTA_eddy_adv_300km_filter_binned_statistics_2016.nc"
"Weak_shfluxa_SSTA_300km_binned_statistics_2016.nc"
"Weak_shfluxa_eddy_adv_ml_300km_binned_statistics_2016.nc"
"Weak_temp1_rate_eddy_adv_300km_binned_statistics_2016.nc"
"Weak_temp1_rate_eddy_adv_zonal_filter_binned_statistics_2016.nc"
"Weak_temp_rate_eddy_adv_binned_statistics_2016.nc"
"Weak_temp_rate_eddy_adv_zonal_filter_binned_statistics_2016.nc"
"Weak_temp_rate_total_adv_binned_statistics_2016.nc"

3) Figures included in Gao et al. (2021)


Fig01_diagram_ML_heat_balance.pdf
Fig02_SSTA_STREAMPLOT_Aug.png
Fig03_SSTA_power_spectra.png
Fig04_MLD_time_series.pdf
Fig05_SC_zonal_mean_budget.pdf
Fig06_WC_zonal_mean_budget.pdf
Fig07_hp_budget_SC.png
Fig08_hp_budget_WC.png
Fig09_gao_number_hp.pdf
Fig10_ml_heating_cooling.pdf
Fig11_EDDY_SSTA_SHFLUXA_AUG.png
Fig12_EDDY_SSTA_SHFLUX.png
Fig13_Ekman_geostrophic_Sept.png
Fig14_Ekman_geostrophic_Feb.png


4) High-passed filtered monthly mixed layer heat budget files:

"high_pass_heat_balance_Strong/high_pass_monthly_ml_heat_balance_2016-*_StrongEddies.nc"
"high_pass_heat_balance_Weak/high_pass_monthly_ml_heat_balance_2016-*_WeakEddies.nc" 

5) Monthly mixed layer heat budget files at small-mesoscale:

"monthly_ml_heat_budget_data_small_mesoscale/Strong/monthly_ml_heat_balance_2016-*_StrongEddies.nc"

"monthly_ml_heat_budget_data_small_mesoscale/Weak/monthly_ml_heat_balance_2016-*_WeakEddies.nc"

6) Monthly mixed layer heat budget files at large-mesoscale:
"monthly_ml_heat_budget_large_mesoscale/Strong/monthly_ml_heat_balance_2016-*_StrongEddies.nc"
"monthly_ml_heat_budget_large_mesoscale/Weak/monthly_ml_heat_balance_2016-*_WeakEddies.nc"

7) SST and surface current data in Strong Current case:

"SST_UV_DATA/SST_2016-08_StrongEddies.nc"
"SST_UV_DATA/Surface_U_2016-08_StrongEddies.nc"
"SST_UV_DATA/Surface_V_2016-08_StrongEddies.nc"

8) Python notebook to re-create the figures:

"python_code/Fig02_SSTA_STREAMPLOT.ipynb"
"python_code/Fig03_SSTA_spectrum_300km_monthly_mean_final.ipynb"
"python_code/Fig04_monthly_mld.ipynb"
"python_code/Fig05_Strong_mon_zonal_mean_heat_balance.ipynb"
"python_code/Fig06_Weak_mon_zonal_mean_heat_balance.ipynb"
"python_code/Fig07_hp_monthly_mean_2D_SC.ipynb"
"python_code/Fig08_hp_monthly_mean_2D_WC.ipynb"
"python_code/Fig09_Gao_number_hp.ipynb"
"python_code/Fig10_plot_coupling_coef.ipynb"
"python_code/Fig10a_ml_heating_cooling_binned_stats_300km.ipynb"
"python_code/Fig10b_temp1_rate_binned_stats.ipynb"
"python_code/Fig10c_meso_ml_heating_cooling_binned_stats.ipynb"
"python_code/Fig11_SHFLUX_eddy_adv_300km.ipynb"
"python_code/Fig12_plot_MS_SSTA_SHFLUXA_300km_filter.ipynb"
"python_code/Fig12a_eddy_adv_ml_binned_stats.ipynb"
"python_code/Fig12b_shfluxa_eddy_adv_Strong.ipynb"
"python_code/Fig13_14_Ekman_Geostrophic.ipynb"



