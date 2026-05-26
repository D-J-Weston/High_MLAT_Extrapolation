# Extrapolating Medium Energy Electron Fluxes At High Magnetic Latitudes For A Low-MEO Orbit

Codes and data for Weston et al. 2026 (DOI to be issued), where using a Von Mises fit on the Arase spacecraft data for electrons with energies between ~60 keV and ~1.2 MeV, We extrapolate the 75th percentile flux values to a higher MLAT whilst maintaining a fixed altitude of ~8000km.

We take a functional form of the Von Mises distribution (see below) with $\lambda$ as MLAT and 4 fitting parameters: K, A, $\omega$, $\Phi$.  

$$
f(\lambda)=K\cdot e^{A\cos(\omega\lambda+\Phi)}
$$

For further details please see Weston et al. 2026 (DOI to be issued)
