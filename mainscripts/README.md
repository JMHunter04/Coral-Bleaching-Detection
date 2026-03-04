In this folder are the scripts to fully run this project, they should be ran in order. File paths must be changed for your system.

1) Main - this code is taken directly from the CoralSCOP GITHUB: https://github.com/zhengziqiang/CoralSCOP. It takes your dataset as an input and outputs masks as JSON files into a new folder.

2) coralmask - this code extracts the masks from the JSON files created by main and applies them to the dataset in a new folder.

3) datasetsplitter - this code splits the masked images into three folders for training, validation and testing.

The dataset used is Healthy and Bleached Corals Image Classification: https://www.kaggle.com/datasets/vencerlanz09/healthy-and-bleached-corals-image-classification/data
This dataset included 485 images of bleached corals and 438 images of healthy corals.

@inproceedings{ziqiang2024coralscop,
    title={Coral{SCOP}: Segment any {CO}ral Image on this Planet},
    author={Ziqiang Zheng and Haixin Liang and Binh-Son Hua and Yue Him Wong and Put ANG Jr and Apple Pui Yi CHUI and Sai-Kit Yeung},
    booktitle={IEEE/CVF conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2024},
}
