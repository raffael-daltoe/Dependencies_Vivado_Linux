# Dependencies of Vivado Linux

Libraries what you need to install before of instalation of Vivado in Linux.

## Instalation

To install you need:

1. Give permissions to the file `install.sh`:

    ```bash
    chmod +x install.sh
    ```

2. Execute the script `install.sh` with privilegies sudo:

    ```bash
    sudo ./install.sh
    ```
    
## Use

If you need, you can uncomment the lines to install the drivers:
  
      
      sudo /tools/Xilinx/Vivado/2023.2/data/xicom/cable_drivers/lin64/install_script/install_drivers/install_drivers
      sudo /tools/Xilinx/Vivado/2023.2/data/xicom/cable_drivers/lin64/install_script/install_drivers/setup_pcusb
      

And if you have more other error, you need to uncomment this line also:
      
      cp 52-xilinx-*.* /etc/udev/rules.d
    
    



