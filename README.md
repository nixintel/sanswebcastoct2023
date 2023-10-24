# SANS Webcast October 2023
Resources mentioned during the Oct 2023 webcast "Investigating Suspicious Websites" 


## About Me

Web: https://www.nixintel.info   
Twitter: https://twitter.com/nixintel   
LinkedIn: https://www.linkedin.com/in/steven-harris-nixintel   
SEC497 Course: https://www.sans.org/sec497   
Protection Group International: https://pgitl.com   

# Talk Resources

## Resources

FCA list of suspicious websites: https://www.fca.org.uk/consumers/warning-list-unauthorised-firms  

## Example Scam Websites (may not be up for much longer...)

Gain Market: https://gainmarketcrypinv.com/ 
Michael Rayh FX: https://www.michaelrayhfx.com/ 

## Example Sitemap

SANS: https://www.sans.org/sitemap.xml 
BG14: https://bg14.ru/sitemap.xml

## Historic Websites

Wayback Machine: https://archive.org/ 
  
## Carbon-14

Important: requires Python 3.8 or earlier.
Github: https://github.com/Lazza/Carbon14 
Tutorial: https://nixintel.info/osint-tools/carbon-14-verifying-the-age-of-a-website/

## Urlscan & Censys

Urlscan (requires login to use search filters): https://urlscan.io/

Example filter: `domain:royalmail.com AND NOT page.domain:royalmail.com` 

Censys: https://censys.io 
Censys GPT: https://gpt.censys.io 

Example query: `services.http.response.body: "download.anydesk.com" AND crypto|forex` 

## Additional Resources From Q&A

Certstream for certificate monitoring: https://github.com/CaliDog/certstream-server 
Watcher for automated DNSTwist/Certstream monitoring: https://github.com/thalesgroup-cert/Watcher 
DNSTwist (Python): https://github.com/elceef/dnstwist 
DNSTwister (web version): https://dnstwister.report/ 





















