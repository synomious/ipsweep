# ipsweep
Script to ping sweep a network and see which hosts are active and alive 

 ./ipsweep.sh $ip 

## Usage

1.) To print out the result to a txt file 

./ipsweep.sh $ip > ips.txt
 

2.) To automate Nmap using the script

for ip in $(cat ips.txt); do nmap $ip; done
