# Implementations of DBSCAN on PySpark
## About the project
In this report, we implement and compare DBSCAN in four different methods. These methods include naive, K-D Tree, Matrix and Triangle. The triangle method use the triangle inequality to divide the partitions. It use MapReduce and GraphFrame in spark to parallel compute the results. So it has the best performance in the large dataset and clusters. 

## About the code
- dbscan_naive.ipynb: The naive DBSCAN
- dbscan_kdtree.ipynb: The DBSCAN optimized by the kdtree
- dbscan_matrix.ipynb: The DBSCAN optimized by the matrix
- dbscan_triangle.ipynb: The DBSCAN optimized by the triangle inequality

## the environment
use the remote environment in Azure: [Environment configuration details](https://github.com/wuhao050698/use-pyspark-in-the-remote-serve)

## Contribution
Wu hao

Chen zhizhen

Ji minghao

Huang yitian

