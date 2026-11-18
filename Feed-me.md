## x) Why use a feed reader?
A feed reader makes it easier to follow several websites in one place. 
Instead of visiting each website separately, new posts from different sources appear automatically in the reader. 
RSS and Atom feeds are useful in cyber security because new vulnerabilities, attacks and security news are published frequently.
The downside is that following many feeds can produce a lot of information, and not every article is relevant.


## y) KKO 2003:36
 The case concerned port scanning against the computer systems of Osuuspankkikeskus. 
 The important point for this exercise is that port scanning other people's systems can have legal consequences.
 Therefore, port scanning should only be performed against systems where you have permission.

 #### a-b) Feed reader

I installed Thunderbird on my Debian virtual machine and I added the Krebs on Security feed: https://krebsonsecurity.com/feed/

<img width="1202" height="538" alt="image" src="https://github.com/user-attachments/assets/f0ec09dd-270a-40ad-bca6-bfa8cdebbe6f" />

## c)Schneier

<img width="782" height="356" alt="image" src="https://github.com/user-attachments/assets/36edbf76-d13e-4316-83b3-82ffb295c86a" />

## d)CISA: 
https://www.cisa.gov/cybersecurity-advisories/all.xml
SANS: https://isc.sans.edu/rssfeed_full.xml

<img width="644" height="334" alt="image" src="https://github.com/user-attachments/assets/4cc5820e-b580-4c37-87ef-5954e8303152" />

## e)
<img width="724" height="293" alt="image" src="https://github.com/user-attachments/assets/8033f8ef-9172-4a9f-b8c1-d7656c375698" />

## f)Scan

I disconnected the virtual machine from the Internet and confirmed this by pinging 8.8.8.8.
I then scanned my own computer using sudo nmap -A -v localhost.
After the first scan, I installed and started Apache.
I disconnected the Internet again and repeated the scan against localhost. 
The second scan detected TCP port 80 as open. This shows that installing and running a network service changes the ports visible to a port scanner.
The scan was performed only against localhost (127.0.0.1), which refers to the local computer.

<img width="560" height="362" alt="image" src="https://github.com/user-attachments/assets/d61593bf-5828-45e3-90ea-7d71d89a7c81" />

<img width="552" height="361" alt="image" src="https://github.com/user-attachments/assets/0e76d56e-7078-4aab-a8c9-21ab43b8f59d" />
<img width="680" height="356" alt="image" src="https://github.com/user-attachments/assets/b14ccdd8-f658-4be8-8bab-5d0456f79752" />

## Sources

Karvinen, T. Cyber Security – h4 Feed me.
 https://terokarvinen.com/cyber-security/

Finlex. KKO:2003:36. Korkeimman oikeuden ennakkopäätös.
 https://www.finlex.fi/fi/oikeuskaytanto/korkein-oikeus/ennakkopaatokset/2003/36

Krebs on Security. RSS Feed.
 https://krebsonsecurity.com/feed/

Schneier on Security. RSS Feed.
 https://www.schneier.com/feed/

SANS Internet Storm Center. RSS Feeds.
 https://isc.sans.edu/xml.html

Cybersecurity and Infrastructure Security Agency (CISA). Cybersecurity Advisories.
 https://www.cisa.gov/news-events/cybersecurity-advisories

Use of AI

Microsoft Copilot was used to help find relevant sources, explain RSS feeds and port scanning concepts, and assist with language and structure. The practical exercises, commands, screenshots and observations were completed by the author.


