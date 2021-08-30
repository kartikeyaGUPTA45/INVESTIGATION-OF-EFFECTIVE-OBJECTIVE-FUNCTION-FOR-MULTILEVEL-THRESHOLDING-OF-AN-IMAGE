# INVESTIGATION-OF-EFFECTIVE-OBJECTIVE-FUNCTION-FOR-MULTILEVEL-THRESHOLDING-OF-AN-IMAGE

In this project, we are trying to study the performance of different objective functions like Kapur’s entropy, Renyi entropy, Otsu method, and many more, on a nature-inspired algorithm like ant lion optimizer, grey wolf optimizer, whale optimization algorithm and so on. Particularly we research Kapur’s entropy, Minimum cross-entropy, Otsu class variance method, and Masi entropy as our objective function and Grey wolf optimizer as our nature-inspired algorithm.

# BASIC TERMINOLOGY
# 1. IMAGE SEGMENTATION:
Image Segmentation is the most important preprocessing step. It partitions an image into a suitable number of homogeneous regions or traces the object boundaries. The goal of segmentation is to change the representation of an image and convert it into that is more meaningful and easier to analyze based on gray level, color, texture, shape, size, or position of an image. Image Segmentation is used in image analysis, objective recognition, and computer vision
                                           
# 2.THRESHOLDING:
Depending on the number of thresholds used to segment an image, thresholding techniques are divided into two types: Bi-level thresholding and Multilevel thresholding.
## Bi-level thresholding:
In this technique, there is one single global threshold is used to partition an image into two classes: the object and background.
## Multilevel thresholding:
In this technique, there is more than one threshold is used to partition an image into different segments which correspond for one background and several objects

# DATASET:
The dataset we are using is  Berkeley Segmentation Data Set and Benchmarks 300 (BSD300)
It is a large dataset of natural images that have been manually segmented. The human annotations serve as ground truth for learning grouping cues as well as a benchmark for comparing different segmentation and boundary detection algorithms.

# GREY WOLF OPTIMIZER
The Grey Wolf Optimizer(GWO) is a nature-inspired algorithm, which imitates the behavior and hunting mechanism of grey wolves in nature.
Grey Wolf Optimizer AlgorithmThere are three types of grey wolfs employed for simulating the leadership hierarchy viz. Alpha(α), Beta(β), and Delta(δ). The rest of the wolfs are called Omega(ω). The process of optimization happens in three steps as searching for prey, encircling prey, and attacking prey.
This Optimizer is used to maximize or minimize an objective function automatically to segment an image.

# Peak Signal-to-Noise Ratio(PSNR) :
It is used to compare image compression quality. It is defined as the ratio between the maximum possible power of an image and the power of corrupting noise.

# Structural SiMilarity (SSIM) index:
It is a method for measuring the similarity between two images. The SSIM index can be viewed as a quality measure of one of the images being compared, provided the other image is regarded as of perfect quality.

# OBJECTIVE FUNCTIONS:
## 1.KAPUR'S ENTROPY:
Kapur's method selects the optimum thresholds by maximizing the entropy of the segmented classes. It uses Shannon's entropy concept of entropy. Shannon's function says that the information content of an event is inversely proportional to its probability of occurrence.
Kapur defines the entropy of an image assuming that an image is entirely represented by its grey level histogram.

## OTSU METHOD:
Otsu's method is also known as the between-class variance technique as this segmentation technique maximizes the inter-class variance and minimizes the within-class variance between the pixels in each class.

## MASI ENTROPY:
Masi entropy is a generalized entropy introduced by Masi. This entropic measure is first applied to bi-level thresholding, it is then later extended for multilevel thresholding. The optimum set of thresholds for the image segmentation is found by maximizing the Masi entropy function. Multilevel thresholding is a technique which uses two or more threshold values to perform image segmentation

## MINIMUM CROSS ENTROPY:
Minimum cross-entropy is proposed by Kullback in 1978 under the name divergence. The minimum cross entropy thresholding algorithm is originally developed for bi-level thresholding, it is later extended to multilevel thresholding.



# BLOG LINK
https://medium.com/@kartikeyagupta1409/investigation-of-effective-objective-function-for-multilevel-thresholding-of-an-image-7b0b5b1d4ea


# VIDEO LINK
https://youtu.be/OtCCsMGKw0I
