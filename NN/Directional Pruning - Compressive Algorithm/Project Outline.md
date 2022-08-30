# Deep Neural Networks Project: Compressive Algorithm 

## SGDcomp and SAMcomp 
SGDcomp is an optimizer that can learn a small sub-network during training, if one starts from an overparameterized dense network. Follow the same idea, apply the compressive algorithm to Sharpness-Aware Minimization (SAM https://arxiv.org/pdf/2010.01412.pdf) optimizer. Algorithm performence becomes even better.

<p align="center">
<img src="https://user-images.githubusercontent.com/32427262/187322768-b04b988a-96be-4fa5-bcde-59293434008c.png" width=46%/> <img src="https://user-images.githubusercontent.com/32427262/187322783-49da7f69-f821-42a1-9056-f18be6b13dfa.png" width=46.2%/>
<br>
<em> Figure: Left: training curve and sparsity based on Cifar 10 using VGG16. Right: training curve and sparsity based on Cifar 100 using WRN28x10. </em>
</p>
