# KNOCKSPY

Knockpy is a python tool designed to enumerate subdomains on   
a target domain through a wordlist.  
It is designed to scan for DNS zone transfer and to   
try to bypass the wildcard DNS record automatically  
if it is enabled. Now knockpy supports queries to VirusTotal subdomains,  

Installation :  
* $ apt update && apt upgrade  
* $ apt install git   
* $ apt install python2  
* $ apt install python 
* $ pip2 install dnspython   
* $ git clone https://github.com/guelfoweb/knock.git  
* $ cd knock 
* $ python2 setup.py install  

usage :  
* $ knockpy -h  
it shows how you can use this tool  
* $ knockpy domain.com
