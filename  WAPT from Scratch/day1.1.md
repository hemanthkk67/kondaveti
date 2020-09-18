## websites to start recon

1)shodan.io
 
 SHODAN is designed to help the user find specific nodes (desktops, servers, routers, switches, etc.) with specific content

##### I have login and found api key and  used shodan for finding information about uber.com using google dorks 
eg. apache hostname:.uber.com
       apache 2.2.1

   2)censys.io
 i have used censys.io to found the protocols and ipv4 hosts ,website backend servers information for indeed.com 

3)crt.sh
used crt.sh for indeed.com to find the regestered domains certifications validation information ,issuer names, etc

4)archive.org
i found the 2010 year snapshots for the flickr.com and website view, its behaviour using waybackmachine 

5)mxtoolbox.com

founded ip address, hostname using mxtoolbox also information observered like spf, dmarc records,whois etc.


6)kitterman
  checked spf records where exist for flickr.com 

7)greynoise.io

GreyNoise is a system that collects and analyzes data on Internet-wide scanners. GreyNoise collects data on benign scanners such as Shodan.io, as well as malicious actors like SSH and telnet worms.

The data is collected by a network of sensors deployed around the Internet in various datacenters, cloud providers, and regions.


8)hunter.io

I observed this is an email finder and email verifier tool which allows to perform domain search for email addresses.

9)recon.dev

10)spiderfoot.net(OSINT)

## Tools
1)dig

used dig tool to finding dns record types, dns paths,nameservers ..etc

dig flickr.com.com txt (Query TXT record)
dig flickr.com cname (Query CNAME record)
dig flickr.com ns (Query NS record)
dig flickr.com A (Query A record)

2)nmap
  finded target open ports, os detection, vuln script cve  details 

3)amass
 ~./myconfigfile.ini
 ~ amass enum -src -ip -d flickr.com
 


4)aquatone
   finding the subdomains scanning, information,takeover possiblities for flickr.com

5)sublist3r

finding subdomains 

6)gobuster(dir bruteforce)

used to find the possible hidden directories for bruteforcing