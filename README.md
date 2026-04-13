# Nu Selection Project

This project is based on CAFAna for neutrino event selection studies.

It is structured to keep source code, configuration, execution environment, and outputs cleanly separated.

The goal of this project is to implement a clean, reproducible **event selection workflow**, where all dataset choices and parameters are externalized in configuration files and the C++ code is kept fully generic.

# Acknowledgements
This work uses and extends analysis code originally developed by
rtriozzi (GitHub: [https://github.com/rtriozzi/<repo-name>](https://github.com/rtriozzi/numine)).

---

# Project Structure
```
analysis/
├── src/            # Main CAFAna macros and analysis code
├── include/        # Helper headers (cuts, selections, utilities)
├── config/         # Configuration files (datasets, options, parameters)
├── run/            # Execution directory (cafe is run here)
├── output/
│   ├── root/       # ROOT output files (histograms, spectra, efficiencies)
│   └── pdf/        # Plots and figures
├── scripts/        # Utility scripts (run automation, cleanup, etc.)
```
