# A Survey for Occluded Person Re-Identification


A paper list of Occluded Person Re-Identification.

*Last updated: 2023/08/17

#### Update log

*2023/August* - update all of recent papers and make some diagram about history of Occluded Person Re-Identification.


##


## Table of Contents

- [Datasets](https://github.com/changshuowang/A-Survey-for-Occluded-Person-Re-Identification/blob/master/README.md#Datasets)
- [Metrics](https://github.com/changshuowang/A-Survey-for-Occluded-Person-Re-Identification/blob/master/README.md#Metrics)
- [Performance tables](https://github.com/changshuowang/A-Survey-for-Occluded-Person-Re-Identification/blob/master/README.md#Performance-tables)
- [Paper list](https://github.com/changshuowang/A-Survey-for-Occluded-Person-Re-Identification/blob/master/README.md#paper-list)


##


## Datasets

The papers related to datasets used mainly about Occluded Person Re-Identification are as follows.

- **[`[Occluded-DukeMTMC]`](https://github.com/lightas/ICCV19_Pose_Guided_Occluded_Person_ReID)** Occluded-DukeMTMC was collected from DukeMTMC-reID, containing 15,618 training images of 708 pedestrians, 2,210 query images of 519 pedestrians, and 17,661 gallery images of 1,110 pedestrians for testing. Of these images, 9% of the training set, 100% of the query set, and 10% of the gallery are occluded images. Obstacles include cars, bicycles, trees, and other pedestrians, adding complexity to the dataset.
- **[`[Occluded-REID]`]()**  
- **[`[Occluded-DukeMTMC-VideoReID]`]()** 
- **[`[P-ETHZ]`]()** 
- **[`[P-DukeMTMC-reID]`]()** 
- **[`[P-CUHK03]`]()**
- **[`[Partial-ReID]`]()** 
- **[`[Partial-iLIDS]`]()** 
- **[`[Partial-CAVIAR]`]()**

We also list two holistic Person Re-Identification as follows.

- **[`[Market-1501]`]()**
- **[`[DukeMTMC-reID]`]()**



##

## Metrics

The papers related to metrics used mainly in RGBD semantic segmentation are as follows.

- **[CMC()Cumulative Matching Characteristic]**  CMC curves are based on the principle of ranking the similarity between the query image and the image library, and the higher the top image, the higher the similarity with the query image.
- **[mAP(mean Average Precision)]**  mAP better reflects the degree to which all correct target pictures are at the top of the sorted list.



##

## Performance tables

Speed is related to the hardware spec (e.g. CPU, GPU, RAM, etc), so it is hard to make an equal comparison. We select two indexes namely CMC and mAP to make comparison. The closer the re-identification result is to the ground truth, the higher the above two indexes are.

Here, we list the results of four occluded Occluded PersonRe-Idenfication datasets and two holistic Person Re-Identification datasets usually used as follows.

### 

|           Method           |   Rank-1    |    mAP    |   Rank-1    |    mAP    |   Rank-1    |    mAP    |   Rank-1    |    mAP    |   Rank-1    |    mAP    |   Rank-1    |    mAP    |    Ref. from    |  Published  |   Year  |
| :------------------------: | :---------: | :-------: | :---------: | :-------: | :---------: | :-------: | :---------: | :-------: | :---------: | :-------: | :---- ----: | :-------: | :-------------: | :---------: | :-----: |
|          **CBDB-Net**      |    50.09    |    38.9   |      -      |     -     |    66.7     |    78.3   |    68.4     |    81.5   |    94.4     |     85    |    87.7     |    74.3   |                 |    TCSVT    |   2021  |
|        **OCNet**           |             |           |             |           |             |           |             |           |             |           |             |           |                 |             |         |
|        **AACN**            |             |           |             |           |             |           |             |           |             |           |             |           |                 |             |         |


###





## Paper list


###2023



###2022
- **[DPM]** L. Tan, et al. (2022). Dynamic Prototype Mask for Occluded Person Re-Identification. in: Proceedings of the 30th ACM International Conference on Multimedia, 2022, pp. 531–540. [[Paper]](https://github.com/stone96123/DPM) [Code]


###2021
- **[CBDB-Net]** H. Tan, et al. (2021). Incomplete Descriptor Mining with Elastic Loss for Person Re-Identification. EEE Transactions on Circuits and Systems for Video Technology 32 (1) (2021) 160–171. [[Paper]]







## Citing
If you find this repository useful in your research, please consider citing:
```
@ARTICLE{OPRDL2023,  
  author={E. {Ning} and C. {Wang} and  H. {Zhang} and X. {Ning} and P. {Tiwari}},  
  booktitle={Arxiv},   
  title={Occluded Person Re-Identification with Deep Learning: A Survey and Perspectives},   
  year={2023}，  
  pages={1-35}
  }
```

## Contact & Feedback

If you have any suggestions about this project, feel free to contact me.

- [e-mail: wangchangshuo1[at]gmail.com]


