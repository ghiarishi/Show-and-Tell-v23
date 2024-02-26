In this project we aimed to implement a Multimodal Show and Tell model to caption images
using the MSCOCO dataset. Our image captioning system was run using a combination
of a CNN model to encode the images and an
RNN model to produce the captions. This was
then extended to include attention on the side
of the image encoding and attention to produce
the caption. The images were also augmented
to improve the robustness of the the model. The
results were then evaluated using the Corpus
BLEU-4 score to test the accuracy of the produced captions. We observed that augmenting the images as well as training on multiple
captions showed a significant increase in the
Corpus BLEU score.

The overall dataset (approximately 165k images) is about 25GB in size. The data was pre-split, and links to the same can be found below: 

Train Data (118k images): http://images.cocodataset.org/zips/train2017.zip

Val Data (5k images):     http://images.cocodataset.org/zips/val2017.zip

Test Data (41k images):   http://images.cocodataset.org/zips/val2017.zip

Through this link (https://drive.google.com/drive/folders/1OTaVLAAHYE0SFX1EcoS8YGmmxk2LurTj?usp=sharing) we have shared a few samples of the data. It is primarily structured as an image along with 5 sample human-generated captions. There also exists the option to access image segmentation data/labels.
