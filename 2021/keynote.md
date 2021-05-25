# Surprises in Deep Learning Training: Symmetry, Efficiency, and Scale 

## Abstract
We make a few interesting observations regarding Deep Neural Networks (DNNS) training:
* DNNs are typically initialized with (a) random weights in order to (b) break symmetry and (c) promote feature diversity.  We demonstrate a,b, and c are not necessary at initialization, in order to obtain high accuracy at the end of the training. (ICML2020)  
* Quantization of full precision trained DNNs while retaining high accuracy typically requires "fine-tuning" the model on a large dataset. We generate synthetic data from the DNN Batch-Norm statistics; we then use it "fine-tune" the DNN to good performance, thus eliminating the need for real data (CVPR2020).
* Asynchronous training causes a degradation in generalization, even after training has converged to a steady-state. We close this gap by adjusting hyper-parameters according to a theoretical framework aiming to maintain minima stability. (ICLR2020)

## Speaker
Daniel is an assistant professor and in the Electrical Engineering Department at the Technion, working in the areas of machine learning and neural networks.  His recent works focus on resource efficiency and implicit bias in neural networks. He did his post-doc working with Prof. Liam Paninski in the Department of Statistics and the Center for Theoretical Neuroscience at Columbia University, and his Ph.D. in the Electrical Engineering Department at the Technion. He is the recipient of the Gruss Lipper Fellowship, the Taub Fellowship, the Goldberg Award, and Intel's Rising Star Faculty Award.

