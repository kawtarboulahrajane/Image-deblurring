# Image-deblurring

data available at https://zenodo.org/records/4772280

The Helsinki Deblur Challenge is a competition presented by the Finnish Inverse Problems Society (FIPS) and 
addressed to research groups to test their deconvolution algorithms on real world data. In particular, the task 
consists in reconstructing sharp images starting from blurred and defocused images. Convolutional neural 
networks have shown potential in image processing, but often in contexts where a priori knowledge of the noise 
was available. Moreover, many papers consider small input sizes images, where the training set can be large and 
easily extended exploiting data augmentation techniques, without making the training too computationally 
expensive. In this paper we experiment supervised deep learning networks for blind deconvolution of large images 
given limited RAM memory. It resulted that the most effective algorithms are the ones with encode-decoder 
structure and higher number of filters and layers even if trained on a smaller training set. 
