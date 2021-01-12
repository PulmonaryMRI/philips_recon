# philips_recon

Scripts for reconstructing pulmonary UTE MRI acquired on Philips scanners

## Requirements 
* GPI lab, http://gpilab.com 
* SigPy, https://github.com/mikgroup/sigpy
* NumPy, https://numpy.org

## Files 
* 3DRadialSaveData.net, GPI Network, generating k-space data and trajectory NumPy files from Philips Raw/Lab/Sin files
* UTE_Koosh_recon_sigpy.ipynb, Jupyter Notebook script, reconstructing image with SigPy NuFFT, JSENSE, and PICS methods
