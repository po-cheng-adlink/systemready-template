## For yocto eMMC image with u-boot that is compliant with ArmSystemReady IR

Follow instructions from: https://github.com/ADLINK/meta-adlink-nxp/wiki/01-1.-Build-Yocto-Image_imx8mp
to build yocto hardknott.

#### But instead do following repo

$ repo init -u https://github.com/ADLINK/adlink-manifest -b lec-imx-yocto-hardknott -m adlink-lec-imx8mp-yocto-hardknott_1v3.xml

#### Also instead of building imx-image-multimedia, build adlink-image-acs

$ bitbake adlink-image-acs

## ArmSystemReady IR compliant u-boot Repository

$ git clone https://github.com/ADLINK/u-boot-adlink.git -b lf_v2021.04-adlink u-boot-adlink

