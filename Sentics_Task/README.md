# Task 

## Data Generation:
1. Generated a synthetic dataset with the following assumptions:
   - 5 sensors (cameras) labeled A, B, C, D, and E.
   - Random X and Y coordinates within the range [0, 100].
   - Three unique IDs: 0, 126, and 348 representing Unknown Object 1, Object 2, and Object Unknown.

2. The generated data is saved in a CSV file named `created_data.csv`.

## Task Execution Steps:

1. **Data Loading:**
   - Load the generated dataset into a Pandas DataFrame.

2. **Data Preprocessing:**

3. **Clustering:**
   - Use DBSCAN algorithm for clustering based on `x_position` and `y_position`.
   - Adjust `eps` parameter to control the maximum distance for points to be considered part of the same cluster.

4. **Save Results:**
   - Save the result DataFrame to a new CSV file named `result.csv`.


