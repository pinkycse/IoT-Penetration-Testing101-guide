# Null-Bangalore-IoT-Security-101-workshop
null bangalore workshop - how to step into IoT penetration testing  



## Setup the Lab -- Download the OVA file from the below link 

- username : nullblr
- password : iot
- <https://drive.google.com/open?id=1NHf8Yr17ZZX8gd-gGeytWVddVAh0OVVZ>

## write the approach to pentest device 

- Network pentesting on devices

- Embedded application

- Bluetooth pentesting
    - gattacker
  
      Runnig Gattacker
    ![Start Gattacker](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/gattacker/gattacker1.JPG)
    
      Runnig Gattacker
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/gattacker/gattacker2.JPG)
    
    - btlejuice 
    
        - Running btlejuice
        - btlejuice-proxy (in vm)
        - btlejuice -u (ip address) -w (host linux)
        - localhost:8080 (in any webb browser)
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/btlejuice/BTLE-JUICE.png)
    
    - bettercap 
        - #bettercap
        - ble.recon on (recon the devices)
        - ble.recon off (stopr the recon)
        - ble.show (to see all scanned devices surrounded by us)
        - ble enum (bd addr)
        ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/bettercap/bettercap.png)
           
        
        - sudo bettercap -caplet https-ui (for web ui)
        ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/bettercap/Selection_003.png)
    - 
  
- Firmware Revere engineering

- Hardware Exploitation
