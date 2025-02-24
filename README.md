# Tree++ Graph Kernels

Wei Ye, Zhen Wang, Rachel Redberg, Ambuj Singh, Tree++: Truncated Tree Based Graph Kernels, IEEE Transactions on Knowledge and Data Engineering (TKDE), 2019.

The directory includes two subfolders "code" and "datasets". The "code" folder contains the code of our Tree++ graph kernel and a breadth-first search script used in Tree++. It also contains a folder called "evaluation" that includes all the codes for the evaluations of the results of graph kernels on real-world datasets. The main script is “runsvm.m”.

Required libraries to run our Tree++ are numpy, networkx, scipy, re, sympy, and gensim. For gensim, please see https://radimrehurek.com/gensim. For networkx, please see https://networkx.github.io/. In order to run our method, please run the following command in the Linux terminal. We take the KKI dataset for example:

$ python tree++.py "KKI"

where the input parameter "KKI" is the name of the dataset.

The original datasets can be found at: https://ls11-www.cs.tu-dortmund.de/staff/morris/graphkerneldatasets

If you have any questions, please contact me via weiye@cs.ucsb.edu.
