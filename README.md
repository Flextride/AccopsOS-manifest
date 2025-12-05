AccopsOS-Manifest

AccopsOS Manifest directory contains mainfest for pulling all the code repositories required to generate AccopsOS.

Usage:
repo init -u https://github.com/Flextride/AccopsOS-manifest.git  -m default.xml -b <branch/tag>
repo sync -j8

After repo sync you will have all required repositories and you may proceed with building AccopsOS using Yocto commands (Refer to release documentation)
