# CEE 292 PINNs Project
## November 6, 2026
### Arba Shkreli

`PINNS_Project.ipynb`: encapsulated original PINNs formulation and implemented different optimization strategies to compare against

`compare_runs.ipynb`: read contents of `/runs` folder for visual side-by-side comparison of all the runs

`\runs`: graphs and saved networks for each run performed.

Note that 
- `original_strategy` is the original mode of obtaining the PINN, like on the class website. Some of the original code has been organized
differently to make iterating through different strategies easier, but algorithmically it is the same.
- `original_strategy_plane_stress` is the original algorithm on a different form of the Lamé first parameter that allows for z-axis strain,
according to my understanding more closely aligned with the 2D cantilever setting.
