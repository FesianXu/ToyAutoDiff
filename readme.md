<div align='center'>
    Toy Automatic Differentiation on computation graph
</div>



The `Automatic Differentiation` (`AutoDiff`) is the fundamental technic in the deep learning framework like `TensorFlow` and `Theano`.  Since there is no many tutorial about the `AutoDiff` in Chinese, I plan to  show some code as examples to illustrate the basic idea of `AutoDiff` used in `TensorFlow` and simultaneously with Chinese blogs published in CSDN. My code is mainly based on [1]. I don't know whether I can explain it well so I will later just write the most of the tutorial using Chinese, but if it's helpful, maybe I can translate the blogs to English.:)

As a summary of this toy project, we will introduce some module in our code:

1. `Node`,  the basic unit used in computation graph, they represent a computation operation or a placeholder, which do not use to calculate in the graph-building process.
2. `Op`, operation node, is one type of the node.
3.  `Executor`,  like `TensorFlow`, we just build the computation graph and there won't be any numeric calculation if you do no feed the numbers. So we need the executor to manage the calculation flow when we feed the numbers.



if this project is helpful, please give me some stars, thanks~

**No Warranty**: This project is just used for tutorial and does not provide any warranty for the code.

# Reference

[1]. https://github.com/dlsys-course/assignment1