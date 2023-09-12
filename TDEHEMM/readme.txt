Data files of neutrino and gamma-ray spectra [CITATION: Murase, Kimura, Zhang, Oikonomou & Petropoulou Astrophys.J. 902 (2020) 108]

1. Energy: E [eV]  
2. IGNORE (dN_gamma/dE [eV^-1 s^-1 cm^-2] with EBL)
3. dN_gamma/dE [eV^-1 s^-1 cm^-2] w.o. EBL
4. IGNORE
5. IGNORE 
6. IGNORE
7. dN_gamma/dE [eV^-1 s^-1 cm^-2] generated gammas
8. dN_neutrino/dE [eV^-1 s^-1 cm^-2] generated neutrinos (all flavors)
9. IGNORE
10. IGNORE
11. dN_gamma/dE [eV^-1 s^-1 cm^-2] low-energy photons
12. IGNORE (reference CTA sensitivity)
13. IGNORE (reference Fermi sensitivity)


# All fluxes are evaluated at 1 Mpc 
# $1*$1*$3*1.2*1e50 gives the differential gamma-ray luminosity
# $1*$1*$8*1.2*1e50 gives the differential neutrino luminosity
# EBL/CMB attenuation needs to be included for photons
# For corona/RIAF models, attenuation inside TDE debris (that can be relevant for photons especially above 100 GeV) is not included
# Cosmic-ray normalization can be rescaled
  - CoronaM1e7: CR pressure ratio=0.464 
  - CoronaM3e7: CR pressure ratio=0.306
  - RIAFM1e7: CR pressure ratio=0.638
  - RIAFM3e7: CR pressure ratio=0.566
  - shock: CR luminosity ratio=1
 
