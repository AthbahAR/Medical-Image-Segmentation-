# Medical_Image_Segmentation

Lesion Detection in Medical Images using Convolutional Neural Network (U-Net).

This is the capstone project of MISK Data Science Immersive course.
After the artificial intelligence revolution, CNN’s models can detect lesions with superior performance which helps doctors with diagnosis. U-Net is one of the deep learning networks with an encoder-decoder architecture and is used in medical image segmentation.

Polyps are precursors to colorectal cancer, and are found in nearly half of the individuals at age 50 having a screening colonoscopy, and are increasing with age. Colonoscopy is the gold standard for detecting and assessing these polyps with subsequent biopsy and removal of the polyps. Early disease detection has a huge impact on survival from colorectal cancer, and polyp detection is therefore important.

### Dependencies
* Tensorflow
* Keras

### Dataset
Kvasir-seg is an open-access dataset for gastrointestinal polyp images and corresponding segmentation ground truth, manually labeled and verified by an experienced gastroenterologist.
The Kvasir-SEG dataset contains 1000 polyp images and their corresponding ground truth.
The resolution of the images contained in Kvasir-SEG varies from 332x487 to 1920x1072 pixels.
The images and its corresponding masks are stored in two separate folders with the same filename.
The image files are encoded using JPEG compression.

You can find the dataset:
* @inproceedings{jha2020kvasir, title={Kvasir-seg: A segmented polyp dataset}, author={Jha, Debesh and Smedsrud, Pia H and Riegler, Michael A and Halvorsen, P{\aa}l and de Lange, Thomas and Johansen, Dag and Johansen, H{\aa}vard D}, booktitle={International Conference on Multimedia Modeling}, pages={451--462}, year={2020}, organization={Springer} .

### Methodology
The methodology has six steps:
* Reading and preprocessing dataset (Image and ground truth). 
** Resizing the height and width of images into 128X128 pixels.
* Normalizing the images to [0, 1].
* Splitting dataset into training, validating, and testing sets.
* Applying data augmentation to the training set. 
# Horizontal flipping.
# Vertical flipping.
# Mirroring.
* Building the U-Net model.
* Training the model using training and validating sets.
* Testing the model with accuracy and Dice Coefficient measurements.
