# Internet-Drone
Control your drone via internet

## Windows

### Python packages

Install these python packages

- pip install pymavlink

- pip install dronekit

- pip install pyserial -- this is important NOT serial

### Connection with APM

- Connect to APM telemetry port using a FTDI
  - Remember to connect RX of APM to TX of FTDI and TX of APM to RX of FTDI
- Connect FTDI to your desktop/laptop using USB to mini usb connector
  - I am using this one here

![drone_ftdi](https://user-images.githubusercontent.com/2953096/43541607-6ed72c2a-95e8-11e8-9d4b-8f8d0156c62b.jpg)
  
- Check that baud rate mentioned in your Standard params is same as mentioned inside the demo.py  
  
![baud rate](https://user-images.githubusercontent.com/2953096/43541649-8eef68b0-95e8-11e8-9607-fa26910c4896.png)


### FTDI

- You probably need to install a USB to UART driver I used this one 
   - https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
- Finally after connection it should show up in your device manager as one of your COM ports

### Running the python script

python demo.py --connect=<COM_Port>
