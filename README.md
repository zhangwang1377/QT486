# QT486
Cross Compile QT4.8.6 For IMX6UL

1. install crosstoolchain in /opt/fsl-imx-x11/3.14.52-1.1.1/
2. cp 0001-Cross-Compile-Qt4.8.6-For-Chipsee-IMX6UL.patch <qt4.8.6 opensource directory>
3. git apply 0001-Cross-Compile-Qt4.8.6-For-Chipsee-IMX6UL.patch
4. ./config.sh

When you meet error. just copy need header file and library file from
/home/chipsee/chipsee-release-bsp/build-x11-6ul/tmp/sysroots to 
/opt/fsl-imx-x11/3.14.52-1.1.1/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi/
