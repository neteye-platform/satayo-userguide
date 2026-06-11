.. _changelog:

**********
Changelog
**********

This page shows the changelog for the SATAYO Threat Intelligence Platform (TIP).

4.15
~~~~~
released on 2025-07-14

+ :command:`added` The new Favicon item is now managed within the platform. The process built around this object allows you to detect the favicons used by your web services and pivot this information, identifying any other third-party services using the same favicons and which could be associated with brand exploitation attempts or malicious campaigns. Within the Favicon item, there is a configuration page that allows you to specify the preferred favicons that will then be included in the pivoting process.

4.14
~~~~~
released on 2025-05-27

+ :command:`added` The new page All Domains is available. This page displays the list of domains associated with your organization that you may want to monitor. In the "Monitored" column you can see if the domain is already monitored. If the domain is not currently monitored but you want to monitor it, you can open a ticket specifying the domain and our analysts will take care of the request.
+ :command:`added` The Technologies section of the ip/hostnames objects now displays any favicons present.
+ :command:`added` In the Status Managed section, you can now filter your search by ticket creation date and update date periods.

4.13
~~~~~
released on 2025-01-07

+ :command:`added` email flags (Disabled, VIP User) in the *Breached Accounts* item for improved account status visibility

4.12
~~~~~
released on 2024-10-23

+ :command:`added` The insert_time field to API responses to indicate the data discovery timestamp
+ :command:`added` A new API endpoint to export the ticket list. The feature is available in the global APIs
+ :command:`added` The ability to organize domains into groups and grant users restricted access to the platform
+ :command:`added` Now the indication of the number of assets, used to manage the service quotation, can be viewed on the License page. In addition, a graph has been added to the Report section, showing the trend over time of the number of assets for each individual domain of your organization

4.11
~~~~~
released on 2024-08-14

+ :command:`added` IP enrichment with NAT configuration and additional information. This information is useful to enrich the context at the customer infrastructure level and consequently provide more precise remediation indications on tickets
+ :command:`added` Hudson Rock Cavalier Platform Integration. This integration significantly improves SATAYO's coverage of infostealer logs
+ :command:`added` Combo List Integration. When combo lists are detected on different types of sources, they are indexed and displayed in the *Breached Account* item or in the *Market* item, depending on the type of combo list
+ :command:`added` Check the presence of detected vulnerabilities within the KEV (Known Exploited Vulnerabilities) catalog

4.10
~~~~~
released on 2024-05-07

+ :command:`added` related tickets for users in the *Mail* item
+ :command:`added` username visibility in market evidence
+ :command:`added` list of usernames for market resources

4.9
~~~~
released on 2024-03-25

+ :command:`fixed` bug fixed and performance improvements
+ :command:`security` multiple security improvements

4.8
~~~~
released on 2024-02-05

+ :command:`added` new filters for vulnerabilities in *Vulnerability* item
+ :command:`added` new page *License*
+ :command:`changed` improved tables for *Vulnerability* item
+ :command:`fixed` Bug during CSV export of Mail evidence

4.7
~~~~
released on 2024-01-05

+ :command:`added` VIP Password Global Overview
+ :command:`added` Breached VIP Accounts Global Overview
+ :command:`added` Global Overview for Domain tld, Domain similar, Domain suspicious, Domain correlated and Domain phishing Global Overview
+ :command:`added` new tabs *Statistics*, *Search* and *Evidence*
+ :command:`added` the possibility to set email accounts as disabled to stop receiving tickets related to them

4.6
~~~~
released on 2023-10-03

+ :command:`added` Blacklist indicators & indicators page
+ :command:`added` new page *Ransomware Monitor*
+ :command:`added` alert for changing vip email
+ :command:`added` Context Data of various data breaches (Federprivacy)
+ :command:`added` EPSS score in CVE page
+ :command:`changed` split the market into two tabs: *Evidence* and *Risk Accepted*

4.5
~~~~
released on 2023-07-05

+ :command:`added` access to the managed status page for partners
+ :command:`added` checks if an email is attached to an account on miro.com
+ :command:`added` Mail VIP Global Overview
+ :command:`added` difference between old and new evidence in the search box
+ :command:`added` links for the different domains in global cve page
+ :command:`added` set up your organization's VIP mail accounts
+ :command:`fixed` bug in count Filtered Tickets and Total Tickets

4.4
~~~~
released on 2023-05-03

+ :command:`added` Market Global Overview
+ :command:`added` Sandboxes Global Overview
+ :command:`added` Severity overview of the market resources
+ :command:`added` New dashboards have been created on the Status Managed page
+ :command:`added` the value of the remaining credit to the market pages
+ :command:`added` subdomain search with VirusTotal and Shodan
+ :command:`added` view filtered tickets on the dashboard
+ :command:`added` Unsubscribed column for *Social & Services* in the *Mail* item
+ :command:`changed` Overview for ticket in the managed service

4.3
~~~~
released on 2023-03-19

+ :command:`added` Traffic Light Protocol (TLP) system for classifying sensitive information
+ :command:`added` fixed vulnerabilities are now highlighted with a green tick
+ :command:`added` advanced profile search within Instagram
+ :command:`added` IntelX platform content integration
+ :command:`fixed` phone evidence
+ :command:`fixed` notification when a new research is available

4.2
~~~~
released on 2023-01-11

+ :command:`added` Information regarding the tactics and techniques of the MITRE ATT&CK®
+ :command:`added` Context Data of various data breaches (azazie, virustotal(multiple combolists), amway, brazilcatho, twitter200M, deezer, gemini, radioitalia, whitepages, ticketcounter, flexbooker, guntrader, onlinerspambot, imesh, netlog)
+ :command:`added` registrant information for domain link
+ :command:`added` VIP account - VIP accounts can now be monitored. VIP accounts are those relating to senior figures with a domain outside the monitored ones (e.g. gmail). VIP accounts must be reported by opening a ticket.
+ :command:`fixed` bug fix
+ :command:`fixed` domain similar notification
+ :command:`fixed` 2easy market scraper

4.1
~~~~
released on 2022-11-04

+ :command:`added` new item sandboxes
+ :command:`added` SATAYO user guide (link in menu)
+ :command:`added` link from JIRA to SATAYO (managed service)
+ :command:`added` The "Global Overview" provides a cross-domain view of the evidence found
+ :command:`changed` graph icon
+ :command:`fixed` Russian market scraper
+ :command:`fixed` CVE order by CVSS score v3
+ :command:`security` low vulnerability patch

4.0
~~~~
released on 2022-10-10

+ :command:`added` description field to CVE export
+ :command:`added` Context Data of various data breaches (Exactis Netprospex StockX Start.ru (new Breach) Stripchat Tapa Airport)
+ :command:`fixed` order column cvss for CVE evidence

3.7
~~~~
released on 2022-07-13

+ :command:`added` Continuous monitoring of the evidence published in the Genesis and Russian marketplaces
+ :command:`added` in the *Port* and *Vulnerability* item, evidence is given if the resource resides on IPs directly managed by the organization
+ :command:`added` Context Data of various data breaches (Disk Union, Coin Pay Ex)
+ :command:`added` severity field for the ticket in the managed service
+ :command:`changed` ticket overview in the managed service page

3.6
~~~~
released on 2022-06-13

+ :command:`added` Parsing DMARC and SPF with verification of warnings or errors
+ :command:`fixed` domain evidence in report

3.5
~~~~
released on 2022-05-19

+ :command:`added` Correlation of the identified CVEs with the TTPs (Tactics, Techniques, Procedures) used by threat actors
+ :command:`added` Description of the identified CVEs
+ :command:`added` focus on CVEs when they concern IPs present within IP blocks directly managed by the customer
+ :command:`added` Management of related domains item: ability to manually add directly managed domains (black suitcase icon); automatic correlation through WHOIS record analysis of domains residing on networks not directly managed (black suitcase icon); automatic correlation through WHOIS record analysis of domains residing on networks not directly managed (blue suitcase icon)
+ :command:`added` Context Data of various data breaches (adapt, riaru ,readnovel, mgm)

3.4
~~~~
released on 2022-03-06

+ :command:`added` Interactive Network Visualisation (beta)
+ :command:`added` evidence of the paste value
+ :command:`added` domains defined as suspicious since they contain the company's domain
+ :command:`added` Context Data of various data breaches (500px, animaljam, bb, animoto, annual, bitly, crackingforum, dave, eatstreet, indiamart, xhamster, youku, zomato, adityaBirla, yahoo, abandonia, aimjunkies, autohotkey, bitcointalk, bitshacking, bleachanime, couponmom2014, cfire, cheapassgamer, chinaeko, comicbookresources, crackingitaly, digitalgangster, openraid, combo, neteller)

3.3
~~~~
released on 2021-11-26

+ :command:`added` SATAYO now searches for Google and Amazon Buckets as well as Azure Containers related to the company domain
+ :command:`added` "Last modified" column in file evidence
+ :command:`added` Possibility to mark as verified the emails that are reported within the various data breaches. The date and the user who carried out the verification are associated. In the event of new emails present in the future in the same data breach, a new verification by the organization is required
+ :command:`added` hashes of files found by SATAYO
+ :command:`changed` improved file search by SATAYO
+ :command:`fixed` VirusTotal Evidence
+ :command:`security` Addition of the CSRF token to all user-interactable forms

3.2
~~~~
released on 2021-10-19

+ :command:`added` API (Application Programming Interface): on the export page, accessible from the home page, it is now possible to enable your token to use the API and integrate the evidence collected by SATAYO into other platforms
+ :command:`added` Subdomain Takeover Checker. This evidence allows an attacker to set up a page on the service that was being used and point their page to that sub-domain
+ :command:`added` The related domains are now shown only in case of resources of those domains present on IP blocks managed directly by your organization. The reference IP of that particular domain is also indicated

3.1
~~~~
released on 2021-10-13

+ :command:`added` MFA (Multi Factor Authentication): now, through the user menu, it is possible to configure the second authentication factor to make access to SATAYO more secure. Currently, the Google Authenticator app can be used as a second authentication factor
+ :command:`fixed` date format in all the *Domain* items

3.0
~~~~
released on 2021-09-24

+ :command:`added` internal search engine. Through this feature it is possible to search for IP addresses, hostnames, email accounts, CVEs, data breaches in all the evidence discovered by SATAYO for the organization's domains
+ :command:`added` continuous, real-time scraping of Pastebin, with verification of evidence relating to the organization, using the configured keywords
+ :command:`added` the evidence of IP addresses managed directly by the company
+ :command:`added` SATAYO now searches for similar domains used in phishing campaigns

2.5
~~~~
released on 2021-08-16

+ :command:`added` target information for *Domain correlated* item. Host and IP address is shown
+ :command:`added` new context data of various data breaches (Badoo, Boxee, Lumin, Cafepress, Evite, Edmodo, BitLy, Pixlr, EyeEm, Liker, Houzz...)
+ :command:`added` from the *Password* item it is possible to have evidence of the data breaches within which that password is present
+ :command:`added` a threat actor has leaked a list of Fortinet VPN login names and passwords that were allegedly scraped from exploitable (see CVE-2018-13379) devices in 2020 summer. SATAYO checks if the IPs of your organization are within this list
+ :command:`added` a threat actor has leaked a list of Ivanti Pulse Connect Secure potentially vulnerable (see CVE-2021-22893 and CVE-2019-11510). SATAYO checks if the IPs of your organization are within this list
+ :command:`changed` alignment of information enrichment (registrar, country) relating to the types of domains managed (TLD, similar, related)
+ :command:`fixed` export Hostnames/IPs

2.4
~~~~
released on 2021-07-07

+ :command:`added` new notification for the *Open Bug Bounty* item
+ :command:`added` information in the *Open Bug Bounty* item
+ :command:`changed` score calculation for *Open Bug Bounty* item. Now the status and date of release are considered
+ :command:`fixed` country flag

2.3
~~~~
released on 2021-03-18

+ :command:`added` verification of the existence of MX records for domain similar and subsequent verification of the presence of the same in the blacklist
+ :command:`added` check if the domains (correlated, similar and TLD) are managed by the organization in SATAYO
+ :command:`added` check the content of robots.txt file. If there are paths in the file related to administrative areas, an alert is displayed
+ :command:`added` navigation menu on the research and statistics page
+ :command:`added` in the *Phone number* item, in the "Source" column, the web resource in which the telephone number has been identified
+ :command:`added` registrar information for all the *Domain* items
+ :command:`added` improvement in hostnames research
+ :command:`added` new graph with a comparison between the different historical researches
+ :command:`added` evidence of similar or tld domain that are owned by the organization
+ :command:`fixed` email validation
+ :command:`removed` domain similar of organization in CSV files

2.2
~~~~
released on 2021-03-01

+ :command:`added` the “Global Executive Summary”, a printable report that aims to provide a quick observation point on issues that require a high degree of priority in mitigation / remediation
+ :command:`added` the Exposure Assessment Index Value (EAIV), visible both in the web report and in the docx format, which shows the degree of exposure of the 3 macro areas (Infrastructure - Data, Files & People - Deep & Dark Web)
+ :command:`added` possibility to export data, from home page and in csv / plain text format, of different types (Mail, Domain Similar [last 60 days], Vulnerability High, Hostnames/IPs, SSL problems, Registry, Password)
+ :command:`added` possibility to change the display order of the accounts present in the data breach. Now they can be sorted based on the date of release of the data breach or the date of discovery by SATAYO
+ :command:`added` notification for new deployments
+ :command:`added` possibility to export data, from home page and in csv / plain text format, of different items (Domain Similar ALL, CVE ALL, etc.)
+ :command:`added` new data breach and context data
+ :command:`added` check on the correct configuration of the records related to the IP blocks used
+ :command:`added` descriptive field on the methods used to retrieve evidence in the *Hostname* item
+ :command:`fixed` improvement in searching IPs not linked to hostnames
+ :command:`fixed` field arrangement in *SSL/TLS* item

2.1
~~~~
released on 2020-12-28

+ :command:`added` new item *General Social*
+ :command:`added` in the *Vulnerability* item the presence of exploits for each CVE (when available)
+ :command:`added` new page that allows you to view the contact channels to receive technical support
+ :command:`fixed` downloadable report
+ :command:`fixed` inserted time with years and months
+ :command:`fixed` more CVE entity
+ :command:`fixed` network graphs

2.0
~~~~
released on 2020-12-01

+ :command:`added` new filter in *Breached Accounts* item to order databreaches for last update date for the domain or breach date
+ :command:`added` item's last evidence
+ :command:`added` data breach - PDL
+ :command:`added` link to the malicious scan report for IPs
+ :command:`added` favorite option in *Registry* item
+ :command:`added` mobileapps in report
+ :command:`added` technologies graph in report
+ :command:`added` downloadable report in docx format, containing all the evidence found
+ :command:`changed` the presence of every single email account is checked within about 120 different web services
+ :command:`fixed` bug in Databreach keywords
+ :command:`fixed` items date in homepage

1.9
~~~~
released on 2020-11-03

+ :command:`added` IPs export in CSV (beta)
+ :command:`added` Home - Report print button
+ :command:`added` new page *Export*
+ :command:`added` API documentation
+ :command:`added` visibility of keywords used for collecting records
+ :command:`added` new page *Security News*
+ :command:`added` new item *SSL/TLS*
+ :command:`added` data breach - Cit0day
+ :command:`added` data breach - 2,844 Troy Hunt collection
+ :command:`removed` IPs export in CSV (beta)

1.8
~~~~
released on 2020-09-28

+ :command:`added` LinkedIn email enumeration

1.7
~~~~
released on 2020-09-11

+ :command:`added` Ips country
+ :command:`added` scan creation date in SATAYO homepage
+ :command:`added` blacklist scan for IP addresses
+ :command:`added` new item *Vulnerability*
+ :command:`added` new item *Port*
+ :command:`added` link to *Password* item in the *Mail* item
+ :command:`changed` single mail view in *Breached Accounts* item
+ :command:`fixed` country image in all the *Domain* items

1.6
~~~~
released on 2020-08-27

+ :command:`added` keywords in *Deep & Dark Web*
+ :command:`added` insert time in *Breached Accounts* item
+ :command:`added` insert time in *Paste* item
+ :command:`added` *Deep & Dark Web* - Conti News
+ :command:`added` *Deep & Dark Web* - exploit.in
+ :command:`added` country flag in all the *Domain* items
+ :command:`changed` sorting option in *Mail* item
+ :command:`changed` sorting option in all the *Domain* items
+ :command:`fixed` clear table sort
+ :command:`fixed` SSL certificate number
+ :command:`fixed` option to sort users

1.5
~~~~
released on 2020-08-19

+ :command:`added` *Deep & Dark Web*
+ :command:`added` column permission in partner org page
+ :command:`added` notification for new *Deep & Dark Web* items
+ :command:`added` notification for new *IP* items in blacklist
+ :command:`added` notification for new *Hostname* items in blacklist
+ :command:`added` *Deep & Dark Web* - Maze
+ :command:`added` *Deep & Dark Web* - Raidforun
+ :command:`added` *Deep & Dark Web* - Twitter
+ :command:`added` *Deep & Dark Web* - Telegram
+ :command:`added` *Deep & Dark Web* - darksearch
+ :command:`fixed` CSS table

1.4
~~~~
released on 2020-08-13

+ :command:`added` partner
+ :command:`changed` user page

1.3
~~~~
released on 2020-08-10

+ :command:`added` option to sort tables
+ :command:`added` tool: pagine gialle
+ :command:`added` last update date for items
+ :command:`added` recover password option
+ :command:`fixed` Microsoft vulnerabilities

1.2
~~~~
released on 2020-07-01

+ :command:`added` changelog
+ :command:`added` insert time in *Mail* item
+ :command:`added` insert time in all the *Domain* items
+ :command:`added` ticket
+ :command:`changed` UI color table
+ :command:`fixed` item *Phone number*
+ :command:`fixed` item *Mail*
