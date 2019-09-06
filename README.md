# Deepdrive
Visual Saliency based target detection in self driving cars
Target Detection is a classic area of research in computer vision. By the improvements
hap- pened with machine learning, target detection evolved as Automatic Target De-
tection and it is used in Self Driving Cars. Target detection can be done in several
ways. In this case, Target Detection is implemented by using Visual Saliency. Visual
saliency is a technique/mechanism of an image which makes some objects stand out from
the other objects and immediately grab our attention . It is unique in every case, so
saliency is hard to detect. Inorder to avoid the complication of the Saliency Detection,
Semantic Segmentation is introduced. It will produce pixel-wise segmentation map for
each classes in different colors. By using Convolutional Neural Network(CNN) architec-
ture,the model is trained. CNN is mainly used for feature extraction, classification and
prediction. The Semantic Segmentation output map is given to the VGGNet-16 network
for feature extraction and classification. Further Keras Visualization(Keras-Vis) tool is
used inorder to get Saliency Map of the given image. Finally a saliency map is generated
with important regions.

# Dataset

CamVid Dataset ---> http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamSeq01/

# Steps

1) Go to VGGNet.py to train a VGGNet-16 model for semantic segmentation.

2) Save the ouput images of Semantic Segmentation and give it as input to visual saliency detection.

3)
