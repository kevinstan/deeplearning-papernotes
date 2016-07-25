## [Adaptive Computation Time for Recurrent Neural Networks](http://arxiv.org/abs/1603.08983)

TLDR; The paper presents Adaptive Computation Time (ACT), an algorithm that allows RNNs to adaptively decide how much computation to expend per time step, also called "pondering". To prevent the network from computng indefinitely an extra term that encourages shorter computation is added to the cost. The architecture is fully differentiable and applicable to any type of RNN (e.g. LSTMs). The authors evaluate ACT on tasks of Parity, Logic, Addition, Sorting and character prediction. An interesting observation is that the numbet of pondering steps seems to predict "boundaries" in the data.