# Medical_Image_Segmentation

Lesion Detection in Medical Images using Convolutional Neural Network (U-Net).

This is the capstone project of MISK Data Science program.
After the artificial intelligence revolution, CNN’s models can detect lesions with superior performance which helps doctors with diagnosis. 

Polyps are precursors to colorectal cancer, and are found in nearly half of the individuals at age 50 having a screening colonoscopy, and are increasing with age. Colonoscopy is the gold standard for detecting and assessing these polyps with subsequent biopsy and removal of the polyps. Early disease detection has a huge impact on survival from colorectal cancer, and polyp detection is therefore important.

For this purpose, this project aim to detect the polyps using U-Net model. The U-Net is one of the deep learning networks that used in medical image segmentation. It is a U-shaped encoder-decoder network architecture, which consists of four encoder blocks and four decoder blocks that are connected via a bridge. 

### Dependencies
* Tensorflow
* Keras

### Dataset
Kvasir-seg is an open-access dataset for gastrointestinal polyp images and corresponding segmentation ground truth, manually labeled and verified by an experienced gastroenterologist.
* The Kvasir-SEG dataset contains 1000 polyp images and their corresponding ground truth.
* The resolution of the images contained in Kvasir-SEG varies from 332x487 to 1920x1072 pixels.
* The images and its corresponding masks are stored in two separate folders with the same filename.
* The image files are encoded using JPEG compression.

You can find the dataset:
* @inproceedings{jha2020kvasir, title={Kvasir-seg: A segmented polyp dataset}, author={Jha, Debesh and Smedsrud, Pia H and Riegler, Michael A and Halvorsen, P{\aa}l and de Lange, Thomas and Johansen, Dag and Johansen, H{\aa}vard D}, booktitle={International Conference on Multimedia Modeling}, pages={451--462}, year={2020}, organization={Springer} .


### Resources
* Ronneberger, O., Fischer, P. and Brox, T., 2015, October. U-net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.
* Yang, R., & Yu, Y. (2021). Artificial Convolutional Neural Network in Object Detection and Semantic Segmentation for Medical Imaging Analysis. Frontiers in Oncology, 11. https://doi.org/10.3389/fonc.2021.638182
* https://github.com/bnsreenu/python_for_microscopists/blob/master/204-207simple_unet_model.py
* Jha, D., Smedsrud, P.H., Riegler, M.A., Halvorsen, P., Lange, T.D., Johansen, D. and Johansen, H.D., 2020, January. Kvasir-seg: A segmented polyp dataset. In International Conference on Multimedia Modeling (pp. 451-462). Springer, Cham.
![image](https://user-images.githubusercontent.com/79464137/207325542-16976f35-f7b2-46b7-8159-da01c68979a7.png
