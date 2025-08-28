# Vectra Assignment Overview

The notebook demonstrates solutions for three distinct assignments, covering data analysis, geometric calculations, and a tiling/bin packing problem.

## Assignment 1a: Student Data Analysis

This section focuses on loading student data from a Google Sheet, performing calculations for academic performance (total score, average, and grades), identifying top students in various categories, visualizing results with a bar chart, and exporting the processed data and visualization back to Google Sheets.

## Assignment 1b: Geometric Calculations with Shapely

This part of the notebook explores basic geometric operations using the `shapely` library. It includes examples of creating points and polygons, calculating distances between points, determining polygon area using both the shoelace formula and `shapely`, calculating edge vectors and their magnitudes, analyzing interior angles for convexity, and finding the centroid of a polygon. The polygon is then visualized with its vertices, angles, and calculated centroid.

## Assignment 2: Room Tiling with Spiral Pattern

This assignment implements a greedy algorithm to tile a rectangular room with different sized square tiles (4x4, 3x3, 2x2, and 1x1) in a spiral pattern from the center outwards. The code includes functions to generate spiral positions, check if a tile can be placed, place tiles on a grid, and visualize the resulting tiling pattern along with a summary of tile counts.

## Assignment 3: Bin Packing (Row-wise Placement)

This section tackles a 2D bin packing problem using a simple row-wise placement strategy. It takes a container of a given width and height and a list of bins with their dimensions. The algorithm attempts to place the bins into the container row by row. The results, including placed and unplaced bins, are printed and visualized.

## Usage

To use this notebook:

1.  **Clone the repository:** Clone this GitHub repository to your local machine.
2.  **Open in Google Colab:** Upload and open the `.ipynb` file in Google Colab.
3.  **Run cells sequentially:** Execute the code cells in order from top to bottom.
    *   For Assignment 1a, ensure you have authenticated with Google Drive and have access to the specified Google Sheet.
    *   For Assignment 2, you will be prompted to enter the room dimensions.
    *   For Assignment 3, you can use the default bin and container sizes or modify the `main()` function or call the `custom_bin_packing()` function for custom input.

This notebook requires the following libraries: `pandas`, `numpy`, `matplotlib`, `gspread`, `google.auth`, `google.colab`, `pydrive`, `shapely`, and `googleapiclient`. These are installed in the first code cell of Assignment 1a.
