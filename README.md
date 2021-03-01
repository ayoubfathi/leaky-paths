# About
A collection of **special** paths linked to major web CVEs, known juicy APIs, misconfigurations.. etc. These could be used for web-content discovery as a way to find quick-wins.


## Goal
I started this repository to make it open for everyone to contribute, with a simple goal of making high-quality wordlists for the community. It could be very helpful whether Pentesters use it for their assessments, security engineers as a part of their DAST solution, or bug bounty hunters to scan a huge number of subdomains/hosts looking for quick wins using high-quality wordlists.



## Usage

* **cve-paths.txt** - this is a curated list of paths linked to previous CVEs, you can use this to scan passively for endpoints related to CVEs. (please feel free to add paths of any newly found CVEs).

* **leaky-misconfigs.txt** - Those are primarily paths associated with known misconfigurations, endpoints that leaks some sensitive data or grant access to some special parts of the app .. etc. This is your go-to for quick hits on any target.

* **juicy-paths.txt** - are special paths that usually expose API endpoints or server information. It's simply an initial gateway to find more interesting stuff while performing a passive scan; you would go for this, especially when looking for more APIs, interesting and verbose endpoints.

* **all-files.txt** - as the name suggests, it has all the files listed in this repository sorted uniquely so that you can simply rely on that if you want to scan everything rather than using each file separately. 


##### In Progress:

* **Adding CVE mapping to each endpoint on cve-paths.txt**, so if you stumble across a valid endpoint from that list, you would be able to map it to a specific CVE and then proceed with exploitation steps. (You can use [Nuclei](https://github.com/projectdiscovery/nuclei) for exploitation)

## Contribution
Feel free to open a new Pull-request if you have a new CVE endpoint to add or simply any special paths that usually return juicy information. 

Please note that the wordlists' use-case is made to be short with a focus on high-quality endpoints only, so they are intentionally not vast enough to rely on it completely for active scanning.

For extended and large wordlists, please refer to [Assetnote](https://wordlists.assetnote.io/) and [SecLists](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content)


## Credits

- A special thanks to [project-discovery](https://github.com/projectdiscovery/), a large part of the CVE endpoints were extracted from their projects.

- Many endpoints were also curated from this tweet by [NahamSec](https://twitter.com/NahamSec/status/1177672652011343873)
 
- Others were shared by various individuals, from tweets, Hackerone reports, personal wordlists. 
