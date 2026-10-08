# Hard-wall half-line continuous-time quantum walk

Figure-generation code for:

Kangqiao Liu and Deyou Chen, *Maximal-velocity deficit under a finite-support constraint in a hard-wall half-line continuous-time quantum walk*, **Physical Review A 114**, 032434 (2026). [Paper](https://doi.org/10.1103/dyyr-z1k8).

The notebook `regen_figures_hardwall_ctqw_pra.ipynb` computes finite-support spectral optima and the continuum scaling function, and generates:

- `fig_opt_state.png` and `fig_opt_bias.png`
- `fig_lambda_u.png`
- `fig_vmax_scaling.png`
- `fig_coherent_incoherent.png`

**Requirements:** Python, NumPy, SciPy, Matplotlib, SciencePlots, tqdm, Jupyter, and a LaTeX installation for figure text.

Run the notebook cells in order. PNG files are saved in the working directory. The largest dense diagonalization (`M=10000`) can require substantial memory and computation time.
