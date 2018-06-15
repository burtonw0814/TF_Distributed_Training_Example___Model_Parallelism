# TF_Distributed_Training_Example___Model_Parallelism
A CNN example that demonstrates the workflow for using distributed TensorFlow to split the graph between multiple machines.

Workflow: 
1. Run the Helper_Server.ipynb on all but the first machine as defined in your cluster specification.
2. Run the Chief_Worker to create and run the TF graph.

Check out corresponding blog post:
https://medium.com/@willburton_48961/how-to-use-distributed-tensorflow-to-split-your-tensorflow-graph-between-multiple-machines-f48ffca2810c
