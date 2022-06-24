![TheBlackPill](https://user-images.githubusercontent.com/9572668/168313587-e022f990-14ba-47ec-8a6c-7edece7d2238.png)


# TheBlackPill
The Black Pill hashrate enlarger Tool

This is a NVIDIA GPU LHR unlock software created for the 511.xx - 512.94 driver. (510.xx  on linux)
The program needs to be run with admin rights.

Should work on all LHR models with >=8GB memory

Usage (windows):

TheBlackPill.exe  (launch for all cuda devices in the rig                           
TheBlackPill.exe "0,1" (launch on device 0 and 1)                                   
TheBlackPill.exe "0,3" (launch on device 0 and 3)                                
TheBlackPill.exe "0,1,2,3,4" (launch on device 0-4)                         

Usage (linux):

sudo ./start.sh  (launch for all cuda devices in the rig)              
sudo ./start.sh "0"  (launch for device 0)                 
sudo ./start.sh "0,1,4"  (launch for device 0,1 and 4)                        
...

After the launch keep the window open and keep the program running.

Then launch your favorite mining software
