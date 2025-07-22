## Notes on the shared dataset

1. **Scope**  
   Each file here contains the numerical data points shown in *arXiv:2501.03419*.  
   The filename indicates the corresponding figure in the manuscript (e.g. `Fig3a_pp.txt`).

2. **Raw pp data**  
   Generated with the public **PYTHIA** model; users can reproduce it by running PYTHIA with the settings described in the paper.

3. **Raw Pb+Pb data**  
   Produced with our proprietary **CoLBT-hydro** model.  
   Full raw files (~50 GB) are **not openly hosted** due to size and project constraints, but can be obtained from the authors (contact **Zhong Yang** or **Xin-Nian Wang**) upon reasonable request.

4. **Figure-specific notes**  
   - *Fig. 1* is illustrative only – no underlying numerical data.  
   - *Fig. 2* is a 2-D distribution. The file lists `x` and `y` bin centers; construct the 2-D matrix with these coordinates to reproduce the plot.  
   - *Fig. 3 & Fig. 4* files contain four columns:  
     ```
     # x  y  xErr  yErr
     ```  
     The filled band in the figures corresponds to `y ± yErr`.

