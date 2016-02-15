### usefull command   
ping -w 2 -c 1 -q %s' % gw   

ipmitool -I lanplus -H %s -U %s -P %s power status'   

find . -type f -name *.py  -exec grep -i mysql {}  +   

neutron security-group-rule-create --direction ingress --ethertype IPv4 --protocol tcp --port-range-min 22 --port-range-max 22 --remote-group-id global_http cluster  

### 
