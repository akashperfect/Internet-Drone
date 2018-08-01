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
  
![baud rate](https://user-images.githubusercontent.com/2953096/43541649-8eef68b0-95e8-11e8-9607-fa26910c4896.png)
