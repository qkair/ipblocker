# ipblocker
A web tool for blocking ip via BGP protocol
### Usage:
 **Step1**: Get gobgp release binary file at https://github.com/osrg/gobgp/releases  
 **Step2**: Run gobgp with: `nohup ./gobgpd -f gobgpd.conf`  
 **Step3**: Run this project with: `nohup python main.py`  
 **Step4**: You can access the web via http://ip:5000/
