### UART-for-Fysetc-Cheetah-v3
This repository has a finality the configuration of connection serial UART the Cheetah V3 on a Pi BTT 1.2. 


Aiming to solve the USB connection problem of the cheetah V3 with the klipper, installed on a Pi BTT. The following tutorial was developed to help the community.

- STEP 1 - CONFIGURATION OF THE KLIPPER
  
In Klipper, access via SSH and configure:
```
make menuconfig
```

#image 1

After configuration of menuconfig, Build and flash the firmware. For flash of, was used the kiauh and usb connection. 
```
make
``` 

- STEP 2 - KIAUH 
Using the `Kiauh` this is possible build and flash firmware.
```
./kiauh/kiauh.sh
```

