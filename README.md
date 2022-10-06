![Unlock_516](https://user-images.githubusercontent.com/9572668/186130000-0e612cae-48d0-40cb-88fa-e0b306fb4f1b.png)


# TheBlackPill
The Black Pill hashrate enlarger Tool

This is a NVIDIA GPU LHR unlock software created for the 511.xx driver or later.
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

hiveos installation guide

https://www.reddit.com/r/acidpool/comments/xhjasb/mine_vtc_at_full_hashrate_on_hiveos_using_lhr/


After the launch keep the window open and keep the program running.

Then launch your favorite mining software
