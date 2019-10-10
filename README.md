# MicroNet-CIFAR
<p>My submission for the <a href="https://micronet-challenge.github.io/">MicroNet Challenge</a>, on the CIFAR-100 classification task. I used PyTorch for my implementation, and did most of the training on Kaggle and Google Colab.</p>

<p>My model is a sparse, weight pruned Googlenet, trained and iteratively pruned over 200 epochs. The details of the training settings are specified in both the notebook and the submission writeup.</p>

<p>The submitted checkpoint(sparsegnetv5_200ep.pth) has a top-1 accuracy of 80.18%, and has 1.845M params and 1.627B mult-adds, which results in a score of 0.2057 (Compared against 36.5M params and 10.49B mult-adds).</p>


