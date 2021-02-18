# 2020-first-order-mmrs
# Reference: Malhotra, R., Zhang, N., On the Divergence of First Order Resonance Widths at Low Eccentricities, MNRAS, 496(3):3152-3160 (2020); Preprint@ArXiv:2006:09452   

Data files [plain text]: mmr21L.txt, mmr21b.txt, mmr32.txt,mmr32b.txt, mmr43.txt, mmrs.txt;
Code [supermongo] for figures 3,4,6,7: fig.sm

Code [f90] for making surfaces of section (figures 2 and 5 in the MZ2020 paper) is in the zip file SurofSec.zip;

Notes on running the code to make surfaces of section
[See Malhotra & Zhang 2020, for background details]

- go to this folder: ./SurofSec/SurSec

- edit Initialize.f90, global.f90, global2.f90  to set needed ICs and parameters

- run makefile (command line > make)

- run sursec.x (command line > sursec.x)

- the output is written in this folder: ./SurofSec/data
  - in the files called SurSec[i].txt and ORBDATA.txt, ORBDATA1.txt
