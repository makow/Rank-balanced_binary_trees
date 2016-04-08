# Rank-balanced_binary_trees

Herein are implementations of trees described by the rank-balanced framework (Haeupler, B., Sen, S., and Tarjan, R. E. (2015). Rank-Balanced Trees. ACM Transactions on Algorithms, 11(4):1–26), specifically, AVL, WAVL, 2-3 and 2-3-4 trees.

Please refer to the README in the 'docs' directory for how to use the program and see the CODE_COMMENTS file for balancing cases which apply (these have not been rigorously checked). The algorithms have not been rigorously tested, testing is a TODO item.

There are four different balancing frameworks that work with the same core binary tree algorithm where one of the balancing algorithms is user-defined at run-time. As a result of constructing an interchangeable set of balancing algorithms for the same binary tree algorithm, the performance of the balancing aspect can be isolated from the other binary tree mainenance operations. In doing so a more direct comparison between the performance/output on the same input data becomes possible.

However, the balancing functions may carry sufficient variation to invalidate a direct comparison as a consequence of my interpretation of the primary literature.

There are other balancing algorithms to add to the four already present. A further use case would be allowing a user to run a sample input data set(s) across the different balancing options and compare the output to find the best performing option.
