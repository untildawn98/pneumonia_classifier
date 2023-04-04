# Pneumonia classifier from x-ray images
## Data
Data can be found in the kaggle contest https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/code
and can also be downloaded by running the following commands

``wget --no-check-certificate -O '/content/chest_xray_data.zip' 'https://data.mendeley.com/public-files/datasets/rscbjbr9sj/files/810b2ce2-11c3-4424-996e-3bef36600907/file_downloaded'``

``mkdir -p data``

``unzip -q -n path_to_downloaded_zip -d destination_folder``

## Evironment
Can be configured by installing the installations cell at the begining of the code or install the following libraries
tensorflow,keras,pandas,matplotlib, numpy,eaborn,sklearn, glob, cv2

for GPU processing you should make sure that cuda is configured. You can refer here for that 
https://developer.nvidia.com/cuda-downloads
