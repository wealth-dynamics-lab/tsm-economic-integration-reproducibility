# Appendix D　Results Reproduction: Code and Algorithms (Chapters 7 and 8)

To ensure full independent reproducibility of the computational methods in Chapter 7 and the empirical results in Chapter 8, this appendix provides complete reproduction guidelines.

All runnable code and author-derived summary data are open-sourced in this repository:  
https://github.com/wealth-dynamics-lab/tsm-economic-integration-reproducibility

Restricted raw data (WIOD .xlsb, full WID .csv, Edelman PDFs, OECD TiVA raw files, Zenodo .zip, etc.) are not included per license terms. See Appendix E for details.

## D.1 Reproduction Environment
- Python 3.10+
- Packages: pandas, numpy, matplotlib, seaborn, scipy, openpyxl, networkx
- Install: pip install -r requirements.txt

## D.2 Chapter 7 Core Algorithm
File: code/algorithm_constraint_variation.py

# See full code in repository
def constraint_variational_integration(G, rho=0.6, cutoff_ratio=0.3):
    """Constrained variational optimization for economic integration degree."""
    # Full implementation available in the repository
    pass

## D.3 Chapter 8 Six Core Figures
- code/fig8_1.py → Figure 8.1: CRJ Distribution and 12.0 Threshold Validation
- code/fig8_2.py → Figure 8.2: Wealth Differentiation Trends (2007–2019)
- code/fig8_3.py → Figure 8.3: WIOD 2014 Meso-Level Validation
- code/fig8_4.py → Figure 8.4: Three-Layer Synchronization Timeline
- code/fig8_5.py → Figure 8.5: ρ Proxy Construction and τ Relationship
- code/fig8_6.py → Figure 8.6: ρ–CRJ–τ Three-Variable Phase Transition Law

Run example: python code/fig8_1.py  
Figures are saved to output/ at 300 dpi.

## D.4 Reproduction Steps
1. Clone or download the repository.
2. Place author-derived data in data/.
3. Place restricted raw data in data/raw/ (see Appendix E).
4. Run the scripts.

License: MIT License  
Data usage: Strictly follows Appendix E.

