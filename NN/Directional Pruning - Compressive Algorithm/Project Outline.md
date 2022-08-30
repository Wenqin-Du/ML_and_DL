# Deep Neural Networks Project: Compressive Algorithm 

## SGDcomp and SAMcomp 
SGDcomp is an optimizer that can learn a small sub-network during training, if one starts from an overparameterized dense network. Follow the same idea, apply the compressive algorithm to Sharpness-Aware Minimization (SAM) optimizer. Algorithm performence becomes even better.

<p align="center">
<img src = 'https://github.com/donlan2710/gRDA-Optimizer/blob/master/pics/intro_cifar100_conn_thumb.png' width=46%/>
<br>
<em> Figure: The DP is the asymptotic directional pruning solution computed with gRDA, which lies in the same minimum valley as the SGD on the training loss landscape. DP has a sparsity 90.3% and a test accuracy 76.81%, while the SGD solution has no zero elements and has a test accuracy 76.6%. This example uses wide ResNet28x10 on CIFAR-100. See the paper for more detail. </em>
</p>



<img src="https://user-images.githubusercontent.com/32427262/187322768-b04b988a-96be-4fa5-bcde-59293434008c.png" width=46%/> <img src="https://user-images.githubusercontent.com/32427262/187322783-49da7f69-f821-42a1-9056-f18be6b13dfa.png" width=46%/>
<br>
<em> Figure: training curve and sparsity based on the simple 6-layer CNN provided in the Keras tutorial https://keras.io/examples/cifar10_cnn/. The experiments are done using lr = 0.005 for SGD, SGD momentum and gRDAs. c = 0.005 for gRDA. lr = 0.005 and 0.001 for Adagrad and Adam, respectively. </em>
