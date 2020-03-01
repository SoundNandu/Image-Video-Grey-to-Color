# Image-Video-Grey-to-Color
# Introduction
In image colorization, goal is to produce a colored image given a grayscale input image. This
problem is challenging because it is multimodal -- a single grayscale image may correspond to
many plausible colored images. As a result, traditional models often relied on significant user
input alongside a grayscale image.
Recently, deep neural networks have shown remarkable success in automatic image colorization
going from grayscale to color with no additional human input. This success may in part be due to
their ability to capture and use semantic information (i.e. what the image actually is) in
colorization, although we are not yet sure what exactly makes these types of models perform so
well.

<img width="741" alt="Screen Shot 2020-03-01 at 12 54 20 AM" src="https://user-images.githubusercontent.com/41890348/75622625-5f74e480-5b57-11ea-90fc-75171697ffe5.png">
<img width="705" alt="Screen Shot 2020-03-01 at 12 54 31 AM" src="https://user-images.githubusercontent.com/41890348/75622626-600d7b00-5b57-11ea-9d45-efa57e8a4da4.png">

For the dataset, we are using publicly available series of 1000 photos from 
open dataset and deep
learning net website. The link is shown as below: https://skymind.ai/wiki/open-datasets and http://deeplearning.net/datasets/.We are planning to split 70% in the training set and 30%
 in thethe test set. Since we have not much of dataset, we might need to give up on validate set for now.
These photos are each 256*256 pixels and includes faces, photography, pa
inting, animals andobjects.To help with generalization, we also performed various transformations including zooms,
flips and shears to prevent overfitting.

# References
1. S. Ioffe and C. Szegedy. Batch normalization: Accelerating deep network training by reducing
internal covariate shift.arXiv preprint arXiv:1502.03167, 2015.
2 .D. Kingma and J. Ba. Adam: A method for stochastic optimization. arXiv preprint
arXiv:1412.6980, 2014.
3. A. Krizhevsky, I. Sutskever, and G. E. Hinton. Imagenet classification with deep
convolutional neural networks. In Advances in neural information processing systems, pages
1097–1105, 2012.
4. A.OlivaandA.Torralba.Modeling the shape of the scene:Aholistic representation of the spatial
envelope. International journal of computer vision, 42(3):145–175, 2001.
5. A. Olmos et al. A biologically inspired algorithm for the recovery of shading and reflectance
images. Perception,33(12):1463–1473, 2004.
6. O. Russakovsky, J. Deng, H. Su, J. Krause, S. Satheesh,S. Ma, Z. Hua
ng, A. Ka
rpathy, A.
Khosla, M. Bernstein, et al. Imagenet large scale visual recognition challenge. International
Journal of Computer Vision, 115(3):211–252, 2015.
