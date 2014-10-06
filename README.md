## What is vegan3d?

**vegan3d** is an R package of 3D plotting routines split apart from
**vegan**. It can be used for dynamic plots based on **rgl** package,
and for static 3D plots based on **scatterplot3d** package.

The package contains the following functions:

 * `ordirgl` with its support functions `orglpoints`, `orglsegments`,
   `orglpoints`, `orglsegments`, `orglspider` and `orgltext`.  These
   require **rgl** package and provide dynamic ordination graphics.

 * **rgl** based support functions `rgl.isomap` to display `isomap`
     results, and `rgl.renyiaccum` to display `renyiaccum` results.

 * `ordiplot3d` for static 3D ordination diagrams. This requires
   **scatterplot3d** package.

Special plotting functions based on **lattice** and **tcltk** packages
are still in **vegan**.

The **rgl** functions are based on the release 0.65-0. They work with
more modern **rgl** but do not use its full capabilities.
