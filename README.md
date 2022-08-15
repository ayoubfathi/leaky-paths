# About
A collection of **special** paths linked to major web CVEs, known juicy APIs, misconfigurations.. etc. These could be used for web-content discovery as a way to find quick wins.

**Update:** I have removed all the other sub-list files and kept everything consolidated on "all-files". This would be much better to remove confusion and keep it all-in-one.


## Goal
I started this repository to make it open for everyone to contribute, with the simple goal of making high-quality wordlists for the community. It could be very helpful whether Pentesters use it for their assessments, security engineers as a part of their DAST solution, or bug bounty hunters to scan a massive number of subdomains/hosts looking for quick wins using high-quality wordlists; this should be your go-to for quick hits on any targets. It includes:

* A curated list of PATHs linked to previous CVEs; you can use it to scan passively for endpoints related to CVEs.

* PATHs associated with known misconfigurations, endpoints that leak sensitive data, grant access to some special parts of the app .. etc.

* Special paths that usually expose API endpoints or server information. Perfectly suitable for discovering more "hidden" APIs, interesting and verbose endpoints.


## Contribution
Feel free to open a new Pull-request if you have a new CVE endpoint to add or simply any special paths that usually return juicy information. 

Please note that the wordlist is intentionally short to focus only on high-quality endpoints, so it is not vast enough to rely entirely on it for active scanning.

For extended and large wordlists, please refer to [Assetnote](https://wordlists.assetnote.io/) and [SecLists](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content)


## Credits

- A special thanks to [project-discovery](https://github.com/projectdiscovery/), a large part of the CVE endpoints were extracted from their projects.

- Many endpoints were also curated from this tweet by [NahamSec](https://twitter.com/NahamSec/status/1177672652011343873)
 
- Others were shared by various individuals, from tweets, Hackerone reports, personal wordlists. 

## Samo's addons
I added some paths from google hacking database and also created wildcards worth searching for.
