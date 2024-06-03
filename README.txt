All paramaters is changed in the Faster R-CNN.upynb file which is a jupyter nootebook file. 

Hyperparamaters:

Batch_size_train determines the batch size used when training the model.

Batch_size_test_valid determines the batch size used when testing and validation the model. This also determines how many images is to be saved when save_imgs is set to True, as the images saved is the first image in the batch.

num_epochs determine how many epochs the model is to be trained on.

lr is the learning rate given to the Adam optimizer.

image_size is the image size the transform resizes the images to.

wandb_on is a boolean that determines if wandb should be used to save data or not.

save_imgs is a boolean that determines in the images the model draws bounding boxes on should be saved or not.

device_cuda determines if the model should use the GPU or CPU to trian the model.

transform_mode determines if the model should transform the images or not

num_workers determines how many parrallel processes should be used.

dataset_path is the name of the folder containing the dataset to be trained, tested and validated on. The folder containing the dataset should be in the same place as the Faster R-CNN.ipynb file.


To run the file, first set the hyper paramaters to be used, set wandb_on to True of False, set save_imgs to True or False, set device_cude to GPU or CPU, set transform_mode to full or none. Set the dataset_path to what the folder is called for the dataset. Now that all the changeble paramaters have been set, press the "Run All" button at the top of the file, 


