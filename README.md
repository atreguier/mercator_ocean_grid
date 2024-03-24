# mercator_ocean_grid
python notebooks to create ocean grids

create_quasi_mercator_1deg_grid.ipynb : The standard 1° lon-lat grid is not isotropic in the polar regions. This is especially true in the Arctic ocean. Ocean modellers have used for a long time “quasi-mercator” grids, that is, lon-lat grids with the size of the cells in latitude decreasing poleward as the cosine of latitude. Here is an example for a 360 x 290 points grid, where delta_y is refined up to 1/3°.
