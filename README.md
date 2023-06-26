# KITTI-Dataset-Supplements

## KITTI-Dataset-Supplements: Additional Files for Testing  OpenPCDet

### File Description

**ImageSets** - Describes the segmentation of the raw dataset. Put in the root directory of your KITTY dataset.

**planes.tar.gz** - Contains the ground data. Unzip and put in the training directory of your KITTY dataset.

**pointpillar_7728.pth** - A checkpoint for testing.

**test.bin** - A point cloud sample file for testing.

### Directory Structure

After patching, the directory structure should be like:

```
KITTI
├── ImageSets
│   ├── test.txt
│   ├── train.txt
│   ├── trainval.txt
│   └── val.txt
├── testing
│   ├── calib
│   ├── image_2
│   └── velodyne
└── training
    ├── calib
    ├── image_2
    ├── label_2
    ├── planes
    └── velodyne
```



