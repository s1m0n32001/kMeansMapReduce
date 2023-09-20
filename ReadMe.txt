kmeans_presentation.ipynb = presentation file
kmeans_2D.ipynb = same code, implemented on a simple 2D dataset we made up to check the effectiveness of our code
benchmark.ipynb = notebook in which we visualize the results of the benchmark. 

The benchmark files are in the three 'benchmark_*' folders. 
The format of these files is

k
G
number of records
number of partitions
loading dataset time
kmeans|| time
weight calculation time
kmeans++ time
kmeans time

list with the logarithm of the cost function during kmeans||
list with the cost function of each iteration of kmeans
