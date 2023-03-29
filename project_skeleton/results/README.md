# Results README

Include intermediate results in this folder. For example, the output of your segmentation algorithm.
Your notebook code should be able to reproduce the results in this folder.

## `how_many_cells` Goal I: How many cells?

`how_many_cells_database.csv`:
- image_fname: name of the image in the database folder
- nb_cells: number of cells in the image
- centroids_fname: name of the csv file with the centroid of each cell

`results_per_image/cell_centroids-image_name.csv`: these columns respect the napari I/O for the point layer. You can drag and drop this file in napari to create a point layer.
- index: index of the cell
- axis-0: x axis of the centroid
- axis-1: y axis of the centroid

## `how_are_cells_connected` Goal II: Junction Analysis

... to be completed
