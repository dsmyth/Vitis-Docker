Docker Image for Xilinx Vitis Unified Software Platform Installation
========

The development environment for Vitis and Vivado can be created on Docker as well. My set of files is above. I haven't written the procedure yet, but like PetaLinux, create it as follows. I would like to write the procedure again.

    Build the base Docker image with build / build.sh
    Start Docker container with run_base / run_base.sh
    Install Vitis in batch mode by referring to install / install
    Install XRT and third party bdf with install_xrt_bdf / build.sh
    docker commit
    Start Docker container with run / run.sh

## References

* [UG1393 - Vitis Unified Software Platform Documentation (v2020.2)](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2020_2/ug1393-vitis-application-acceleration.pdf)
* [UG1393 - Vitis 統合ソフトウェア プラットフォームの資料 (v2020.2)](https://japan.xilinx.com/support/documentation/sw_manuals_j/xilinx2020_2/ug1393-vitis-application-acceleration.pdf)


## License

* MIT

