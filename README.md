# dataset
## Dataset Availability

The dataset is available at the following link:

Baidu Netdisk:
https://pan.baidu.com/s/1syPaa8NSXol0_-WyYBR-5g

Extraction code:
7029

Please cite this dataset if you use it in your research.

The folder xuzhou_5 indicates that there are 5 UAV sampling points in the Xuzhou scenario, corresponding to a sampling rate of 0.01%. The same naming convention applies to the other folders.

Each sample folder contains the relevant files for radio maps, including the following text files: uav_sparse.txt, which represents the UAV sparse sampling; uav_mask.txt, which represents the UAV sampling mask; uav_height, which records the UAV height information; gt_ground.txt, which contains the ground-truth radio map; metadata.txt, which stores the parameter settings; and uav_points.txt, which provides summary information of the UAV sampling points.

The building height and building mask information are stored in NumPy array format (.npy), with the corresponding files named height.npy and mask.npy, respectively.

The dataset split files train.txt, val.txt, and test.txt specify the samples assigned to the training, validation, and testing sets, respectively.

In addition, the tx folder contains fpp files that can be loaded in winprop for visualization analysis.
