# Null-Bangalore-IoT-Security-101-workshop
null bangalore workshop - how to step into IoT penetration testing  

 ## Software tools and hardware requirements:
 
|IoT Penetration testing Framework 
| ----------------------------------|
| 1.IoTSecFuzz			               |
| 2.Exploit Framework               |

| Firmware Reverse engineering:     |
| --------------- | --------------- |
| binwalk         | Not Required    |
| firmwalker      | Not Required    |
| FACT-core       | Not Required    |
| radare2         | Not Required    |
| capstone        | Not Required    |
| angr            | Not Required    |
| flawfinder      | Not Required    |
| firmware modkit | Not Required    |
| r2ghidra-dec    | Not Required    |
 

| Firmware emulating:		|
| ------------- | ------------- |
| FAT tool      | Not Required  |
| Qemu          | Not Require   |
| qiling        | Not Required  |
| Firmadyne     | Not Required  |

| Bluetooth:	         	|
| --------------| --------------|
| Gattacker     | CSR 4.0       |
| Bluez         | CSR 4.0       |
| bettercap     | CSR 4.0       |
| btlejuice     | CSR 4.0       |
| nrfconnect    | NRF52840      |
| sniffle       | TI CC1352R    |
	
|Hardware:
| -----------------------------------|
| 1.flashrom                         |
| 2.openocd                          |
	
|Apk Analyzers:
| -----------------------------------|
| 1.MobSF                            |
| 2.QARK                             |

## Setup the Lab -- Download the OVA file from the below link 

- username : nullblr
- password : iot
- <https://drive.google.com/open?id=1NHf8Yr17ZZX8gd-gGeytWVddVAh0OVVZ>

## write your own way approach to pentest device 

### Network pentesting on devices

### Embedded application
   
   <https://www.owasp.org/index.php/OWASP_Embedded_Application_Security>
    
### Bluetooth pentesting
   
  - Gattacker
  
  - Runnig Gattacker
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/gattacker/gattacker1.JPG)
    
  - Runnig Gattacker
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
  
  
### Firmware Revere engineering
    
   - FACT Tool (Firmware analysis comparison toolkti)
     ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/firmware/Selection_003.png)
     
   - FACT UI (after running script ui will load at https://127.0.0.1:5000)
     ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/firmware/FACT-UI.png)
         
      
### Hardware Exploitation
