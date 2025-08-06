
# Large Interferometer For Exoplanets (LIFE): VIII. Where is the phosphine? Observing exoplanetary PH3 with a space based MIR nulling interferometer
  

Spectra with and without phosphine for various planetary cases used in the LIFE VIII paper (Angerhausen D., Ottiger M., Dannert F., Miguel Y., Sousa-Silva C., Kammerer J., Menti F., et al., 2023, AsBio, 23, 183. doi:10.1089/ast.2022.0010)

Link to paper: 	https://www.liebertpub.com/doi/10.1089/ast.2022.0010

  
  

  

## Description of the different subdirectories:  


  

- `Jupiterlike/`  

	Contains the spectra with and without phosphine (labeled 'noPH3') for the warm Jupiter modeled in the publication (Figure 5).  Units: Wavelength (microns) vs  Flux (W/m2/m) at the top of the atmosphere. Source: Yamila Miguel

	> **Note:** The Jupyter notebook  [conversion.ipynb](conversion.ipynb) allows you to scale and convert to LIFEsim-friendly units to reproduce the Figure in the paper. 
	

  

- `SuperEarths/` 

	Contains the spectra with (labeled 'with_PH3') and without phosphine (labeled 'wo_PH3') for the Super Earths modeled in the publication. Both the H2-rich case (labeled 'H2', corresponding to Figure 3) and CO2-rich case (labeled 'CO2', corresponding to Figure 4). Units: Wavenumber (cm^-1) vs Contrast. See Figures 6/7 from Sousa-Silva et al. 2019.
  
	> **Note:** You will need to multiply the contrast by a stellar flux to get the planet flux. 

- `Venuslike/` 

	Contains the spectra with (labeled 'ph3') and without phosphine (labeled 'no_ph3') for the warm Jupiter modeled in the publication (Figure 2).  Units: Wavelength (microns, 1st column) vs  contrast.

	> **Note:** You will need to multiply the contrast by a stellar flux to get the planet flux. 
