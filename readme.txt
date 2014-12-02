


supported devices 

Supported and tested:
 FT232R
 CDC/ACM serial services
 CP2102

(All Arduino devices we know of use one of these two drivers, and are supported.)

Possibly supported (untested):
 FT232H 
 FT2232D 
 FT2432H


some used pid/vid 

    <!-- 0x0403 / 0x6001: FTDI FT232R UART -->
     <usb-device vendor-id="1027" product-id="24577" /> 

    <!-- 0x2341 / Arduino -->
    <usb-device vendor-id="9025" />

    <!-- 0x16C0 / 0x0483: Teensyduino  -->
    <usb-device vendor-id="5824" product-id="1155" />

    <!-- 0x10C4 / 0xEA60: CP210x UART Bridge -->
    <usb-device vendor-id="4292" product-id="60000" />
    
     <!-- 0x1B4F / 0x9204 Sparkfun pro micro -->
    <usb-device vendor-id="6991" product-id="37380" />


To add new device see the required steps at : https://groups.google.com/forum/#!searchin/usb-serial-for-android/cdc/usb-serial-for-android/5Uz736xIAuY/6-ByLFlLI5MJ


