## 2024 COVID-19-CT-Classification
The competition includes two types of frameworks for the scripts. Except for the difference in network framework, all data preprocessing is the same for both.

### Pre-processing

The following script assumes that the data and paths are correct. Please make sure that the data and paths are correct before running the script.
***
Run the ```00-group5fold-df.ipynb``` script which treats all train and validation sets as cross-validation. Use it as needed.
***
Run the ```01-preprocess.py``` script to perform cropping on each slice.
***
Run the ```02-get_slice_range_ke.ipynb``` script to obtain the range for each CT scan and sample from the estimated kernel-density distribution.
***
Run the ```03-1-slice_filter_code.ipynb``` script to handle exceptional images, such as excluding misaligned axis data, modifying paths, and constructing convenient CSV files for training or testing.
***

### E2D-Net
Run the ```04_training_kds``` script to obtain basic results.

### Inference

Run all files in ```/inference``` according to index, thereby yielding final prediction results.

### Contact

If you have any question, please don't hesitate to contact us.

email: zuw408421476@gmail.com, cchsu@gs.ncku.edu.tw