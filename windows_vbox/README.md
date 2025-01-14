# Docker Container Ports

**Container Web Ports**   
Webdav: 6999: http://10.17.0.10:6999/webdav   
Ledger: 7001 http://10.17.0.10:7001   
Boranga: 7002 http://10.17.0.10:7002   
Wildlife Legacy: 7005 http://10.17.0.10:7005   
Wildlife Compliance: 7006 http://10.17.0.10:7006   
Disturbance: 7007 http://10.17.0.10:7007  
Leases Licensing: 7008 http://10.17.0.10:7008   
Park Passes: 7009 http://10.17.0.10:7009   
Parkstay V2: 7010 http://10.17.0.10:7010   
Encryption GW: 7011 http://10.17.0.10:7011   
Commercial Operator: 7012 http://10.17.0.10:7012  
Moorings: 7013 http://10.17.0.10:7013  
Geoserver: 7014 http://10.17.0.10:7014  
Mooring Licensing: 7015 http://10.17.0.10:7015  
API Gateway: 7016 http://10.17.0.10:7016    

**Container Dev Ports**   
Postgres: 9011-9020 http://10.17.0.10:9011   
Ledger: 9021-9030 http://10.17.0.10:9021   
Boranga: 9000-9010 http://10.17.0.10:9001  
Wildlife Legacy: 9041-9050 http://10.17.0.10:9041  
Wildlife Compliance : 9051-9060 http://10.17.0.10:9051  
Disturbance: 9061-9070 http://10.17.0.10:9061  
Leases Licensing: 9071-9080 http://10.17.0.10:9071  
Park Passes: 9081-9090 http://10.17.0.10:9081  
Parkstay V2: 9091-9100 http://10.17.0.10:9091   
Encryption GW: 9101-9105 http://10.17.0.10:9101    
Commercial Operator: 9106-9110 http://10.17.0.10:9106   
Moorings: 9111-9115 http://10.17.0.10:9111   
Geoserver: 9116-9120 http://10.17.0.10:9116   
Mooring Licensing: 9121-9125 http://10.17.0.10:9121   
API Gateway: 9126-9130 http://10.17.0.10:9126    

**Container SSH Ports**   
Postgres: 2223    
Ledger: 2224   
Boranga: 2222   
Wildlife Legacy: 2225  
Wildlife Complance: 2226    
Disturbance: 2227   
Leases Licensing: 2228   
Park Passes: 2229   
Parkstay V2: 2230   
Encryption GW: 2231   
Commercial Operator: 2232   
Moorings : 2233      
Geoserver : 2234  
Mooring Licensing: 2235   
API Gateway : 2236

# Installation Instructions
https://github.com/dbca-wa/docker-scripts-dev/tree/main/windows_vbox/installation

# Update .bashrc to allow scripts to be executed anywhere.  

Add the two export lines to the end of the .bashrc   
   
```
vi ~/.bashrc   
export PATH=~/docker-scripts-dev/windows_vbox:$PATH   
export PATH=~/docker-scripts-dev/tools:$PATH   
```
