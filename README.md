# commands 

`ls -lsaht`
`searchsploit apache`
`export IP="172.16.80.1" &&
echo $IP`
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``



# tools

`nmap -p80,20-23 -sV --script=http-enum,http-wordpress-enum,http-methods,http-ls,http-robots.txt,http-cookie-flags,http-cors $IP`
`gobuster dir -u http://offsecwp:80/ -w /usr/share/wordlists/dirb/common.txt -t 5 -b 301`
`gobuster dns -d megacorpone.com -w /usr/share/seclists/Discovery/DNS/subdomains-top1million-110000.txt -t 30`
`wfuzz -c -z file,/usr/share/seclists/Discovery/Web-Content/raft-medium-files.txt --hc 301,404,403 "http://offsecwp:80/FUZZ/"`
`echo "https://www.megacorpone.com/" |hakrawler `
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
