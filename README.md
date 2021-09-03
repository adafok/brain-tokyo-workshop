<h1>Weight Agnostic Neural Networks under Network Constraints</h1>

This repository contains the source code for my bachelor thesis titled "Weight Agnostic Neural Networks under Network Constraints". It is based on [Weight Agnostic Neural Networks](https://github.com/google/brain-tokyo-workshop/tree/master/WANNRelease). 

Our goal was to search for the the optimal solutions where the performance is maximized while minimizing the network's complexity. The major contribution is the implementation of two additional complexity constraints: 1) the number of internal nodes and 2) entropy.

<h3>Setup</h3>

Basically, you can follow the instructions in [WANN](https://github.com/google/brain-tokyo-workshop/tree/master/WANNRelease/WANN/). If you want to adjust the probabilities of choosing a specific objective, you can change the hyperparameters which begin with <code>alg_probMoo</code> in <code>/WANN/p/default_wan.json</code>. Moreover, the combination of different objectives can be changed in <code>probMoo</code> in <code>/WANN/wann_src/wann.py</code>.

Please note that the experiments have only done on the cart-pole swing-up task.
