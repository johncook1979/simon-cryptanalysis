# VISTA-CRYPT 
VISTA-CRYPT is a lightweight cryptanalysis method for Internet of Things (IoT) encryption algorithms SIMON and SIMECK. VISTA-CRYPT utilises quota sampling to reduce variance within the differentials and improve overall search efficiency using a Nested Monte Carlo Search (NMCS) method. VISTA-CRYPT optimises NMCS to identify the best differential path. [This article published in IEEE Access](https://ieeexplore.ieee.org/abstract/document/10703066/) is related to this repository

## Directory structure
This repo has the following structure

_readme.md_

[__one_way_analysis__](https://github.com/johncook1979/simon-cryptanalysis/tree/main/one_way_analysis)

*   _SIMON_32_timings_stratified_sampling.ipynb_
  
*  _SIMECK_32_stratified_sampling.ipynb_
  
__two_way_analysis__

*  _SIMON32-rev-stratified-sampling.ipynb_
  
*  _SIMECK32-rev-stratified-sampling.ipynb_
  
__pddt__

*  _alph.txt_
  
*  _bet.txt_
  
* _gam.txt_
  
*  _pro.txt_

## Prerequisites
Either Visual Studio Code or Jupyter Notebook to execute Python code. 
Familiarity with Python is a benefit.

## Executing code
When executing the code, ensure you are using either Jupyter Notebook or Visual Studio with Python. The 4 text files should be in the same directory as the executed files, or modify the code to reference their correct location.

## Reference
If you intend on using this repository we request you reference using the following:

## APA 7
Cook, J., Rehman, S. ur, & Arif Khan, M. (2024). Lightweight Cryptanalysis of IoT Encryption Algorithms: Is Quota Sampling the Answer? IEEE Access, 1–1. https://doi.org/10.1109/access.2024.3472014

## Harvard
Cook, J., Rehman, S. ur and Arif Khan, M. (2024). Lightweight Cryptanalysis of IoT Encryption Algorithms: Is Quota Sampling the Answer? IEEE Access, pp.1–1. doi:https://doi.org/10.1109/access.2024.3472014.

## IEEE
J. Cook, S. ur Rehman, and M. Arif Khan, “Lightweight Cryptanalysis of IoT Encryption Algorithms: Is Quota Sampling the Answer?,” IEEE Access, pp. 1–1, 2024, doi: https://doi.org/10.1109/access.2024.3472014.

## BibTex
@ARTICLE{10703066,  
  author={Cook, Jonathan and Rehman, Sabih ur and Arif Khan, M.},  
  journal={IEEE Access},   
  title={Lightweight Cryptanalysis of IoT Encryption Algorithms: Is Quota Sampling the Answer?},   
  year={2024},  
  volume={},  
  number={},  
  pages={1-1},  
  keywords={Ciphers;Internet of Things;Encryption;Monte Carlo methods;Hamming weight;Symbols;Object recognition;Mathematics;Heuristic algorithms;Australia;Differential cryptanalysis;Internet of Things (IoT);Lightweight Encryption;SIMON;SIMECK;Quota sampling},  
  doi={10.1109/ACCESS.2024.3472014}  
}

