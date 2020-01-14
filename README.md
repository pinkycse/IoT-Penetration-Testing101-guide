# Null-Bangalore-IoT-Security-101-workshop
null bangalore workshop - how to step into IoT penetration testing  

 ## Software tools and hardware requirements:
 
|__IoT Penetration testing Framework__  |
| --------------------------------------|
| 1.IoTSecFuzz			        |
| 2.Exploit Framework                   |


| __Firmware Reverse engineering:__     |
| --------------------------------------|
| 1. binwalk                            |
| 2. firmwalker                         |
| 3. FACT-core                          |
| 4. radare2                            |
| 5. capstone                           |
| 6. angr                               |
| 7. flawfinder                         |
| 8. firmware modkit                    |
| 9. r2ghidra-dec                       |
 

| __Firmware emulating:__	|
| ------------------------------|
| 1. FAT tool                   |
| 2. Qemu             		|	
| 3. Qiling         		|
| 4. Firmadyne        		|



| __BluetoothTool__ | __Hardware Requirements__ | 
| -------------------|---------------------------|
| Gattacker         | CSR 4.0                   | 
| Bluez             | CSR 4.0                   | 
| bettercap         | CSR 4.0                   |
| btlejuice         | CSR 4.0                   |
| nrfconnect        | NRF52840                  |
| sniffle           | TI CC1352R                |


	
|__Hardware:__	    |
| ------------------|
| 1.flashrom        |
| 2.openocd         |
	
|__Apk Analyzers:__ |
| ------------------|
| 1.MobSF           |
| 2.QARK            |

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
  
  - ___Runnig Gattacker___
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/gattacker/gattacker1.JPG =100x20)
    
  - ___Runnig Gattacker___
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/gattacker/gattacker2.JPG =100x20)
    
   - ___btlejuice___
    
        - Running btlejuice
        - btlejuice-proxy (in vm)
        - btlejuice -u (ip address) -w (host linux)
        - localhost:8080 (in any webb browser)
    ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/btlejuice/BTLE-JUICE.png =100x20)
    
   - ___bettercap___
        - #bettercap
        - ble.recon on (recon the devices)
        - ble.recon off (stopr the recon)
        - ble.show (to see all scanned devices surrounded by us)
        - ble enum (bd addr)
        ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/bettercap/bettercap.png)
           
        
   - ___sudo bettercap -caplet https-ui (for web ui)___
   <img src="https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/bettercap/Selection_003.png" width="100" height="100" />
     ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/bettercap/Selection_003.png)
  
  
### Firmware Revere engineering
    
   - ___FACT Tool (Firmware analysis comparison toolkti)___
     ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/firmware/Selection_003.png)
     
   - ___FACT UI (after running script ui will load at https://127.0.0.1:5000)___
     ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/firmware/FACT-UI.png)
         
      
### Hardware Exploitation


### Exploit Frameworks 
	
   ___expliot framework___
   ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/exploit%20framework/expliot.JPG)
   
   ___IoTSecFuzz___
   ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/exploit%20framework/iotsecfuzz.JPG)
   
   ___Routersploit___
   ![](https://github.com/V33RU/Null-Bangalore-IoT-Security-101-workshop/blob/master/null/exploit%20framework/routersploit.JPG =100x20)
