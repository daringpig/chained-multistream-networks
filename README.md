#### Code and Models for "Chained Multi-stream Networks Exploiting Pose, Motion, and Appearance for Action Classification and Detection" in ICCV 2017 

###### By Mohammadreza Zolfaghari, Gabriel L. Oliveira, Nima Sedaghat, Thomas Brox


### Update
- **2018.4.30**: Scripts for creating body-part mask to train body-part segmentation network.
- **2018.2.26**: The pretrained models and scripts for creating human pose maps are released.

### Contents
0. [Citation](#citation)
0. [Requirements](#requirements)
0. [Installation](#installation)
0. [Usage](#usage)
0. [Models](#models)
0. [Results](#results)
0. [Project page](#Project page)



### Citation

If you find **ChainedNet** useful in your research, please consider to cite:

        @InProceedings{ZOSB17a,
        author       = "Mohammadreza Zolfaghari and
                    Gabriel L. Oliveira and
                    Nima Sedaghat and
                    Thomas Brox",
        title        = "Chained Multi-stream Networks Exploiting Pose, Motion, and Appearance for Action Classification and Detection",
        booktitle    = "IEEE International Conference on Computer Vision (ICCV)",
        month        = " ",
        year         = "2017",
        url          = "http://lmb.informatik.uni-freiburg.de/Publications/2017/ZOSB17a"
        }



### Requirements
1. Requirements for `Python`
2. Requirements for `Matlab`
3. Requirements for `Caffe` and `pycaffe` (see: [Caffe installation instructions](http://caffe.berkeleyvision.org/installation.html))

### Installation
1. git clone ... TODO.
2. Build Caffe and pycaffe

    ```Shell
    cd $caffe_FAST_ROOT/
    # Now follow the Caffe installation instructions here:
    # http://caffe.berkeleyvision.org/installation.html
    make all -j8 && make pycaffe && make matcaffe
    ```

### Usage

*After successfully completing the [installation](#installation)*, you are ready to run all the following experiments.


#### Part 1: Body Part Segmentation
 Please follow steps explained in [Body Part Segmentation](https://github.com/mzolfaghari/chained-multistream-networks/tree/master/body_part_segmentation)

Image+mask             |  BodyPart mask
:-------------------------:|:-------------------------:
![](files/GIFMaker3.gif)  |  ![](files/GIFMaker4.gif)


#### Part 2: Chained Multi-stream network
**Note:** TODO


### Models (TODO)


### Results (TODO)


### Project page
https://lmb.informatik.uni-freiburg.de/projects/action_chain/


### Contact

  [Mohammadreza Zolfaghari](https://github.com/mzolfaghari/chained-multistream-networks)

  Questions can also be left as issues in the repository. We will be happy to answer them.
