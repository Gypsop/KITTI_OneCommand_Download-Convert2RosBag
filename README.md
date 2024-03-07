### KITTI Dataset Batch Processing Tool
##### This repository provides a convenient batch script to automate the process of downloading the KITTI dataset and converting it to ROS bag file format.

#### Prerequisites
- Ubuntu 20.04
- ROS Noetic

#### How to use
1. Download the **download_kitti_and_convert_to_bag.sh** file to the folder you want to store KITTI dataset in.
2. Open terminal in that folder. Change the permission of the file to make sure you can run it.
```bash
sudo chmod +x ./download_kitti_and_convert_to_bag.sh
```
3. Just run it.
```bash
sudo ./download_kitti_and_convert_to_bag.sh
```

That's it! Please make sure you have enough available space on the disk (about 300GB for all the KITTI raw data and the bag files) before you run it. :)

#### Thanks to
- [KITTI](https://www.cvlibs.net/datasets/kitti)
- Omid Hosseini for his [raw dataset download script](https://s3.eu-central-1.amazonaws.com/avg-kitti/raw_data_downloader.zip)
- Tomas Krejci for his [kitti2bag tool](https://github.com/tomas789/kitti2bag)
