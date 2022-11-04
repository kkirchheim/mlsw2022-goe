
<div align="center">

# On Outlier Exposure with Generative Models 

<a href="https://pytorch.org/get-started/locally/">
    <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white">
</a>
<a href="https://gitlab.com/kkirchheim/pytorch-ood">
    <img alt="Template" src="https://img.shields.io/badge/-PyTorch--OOD-017F2F?style=flat&logo=gitlab&labelColor=gray">
</a>

</div>

This is the code for the workshop paper *On Outlier Exposure with Generative Models* as published 
on the NeurIPS 2022 Machine Learning Safety Workshop. 

In the paper, we take a first step into exploring the idea of using generative models to sample from low density regions of the data 
distriubtion.
Such samples can be used as synthetic outliers for outlier exposure, and we show that they tend to make the model more robust to Out-of-Distribution data 
compared to models exposed to uniform noise. 


<div align="center">

![samples](img/cover-samples.png)



![results](img/results-base.png)

</div>







## Dependencies

* pytorch 
* torchvision
* torchtext
* pytorch-ood 



