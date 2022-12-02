# About
A collection of **special** paths linked to major web CVEs, known juicy APIs, misconfigurations.. etc. These could be used for web-content discovery as a way to find quick wins.


## Goal
With the goal of providing the community with high-quality wordlists, I opened up this repository for contributions from anyone. This should be your go-to for quick hits on any targets, whether you're a Pentester using it for assessments, a security engineer using it as part of your DAST solution, or a bug bounty hunter scanning a large number of subdomains/hosts for quick wins using high-quality wordlists. It contains:

* PATHS associated with known misconfigurations, endpoints leaking sensitive data, granting access to some special parts of the app, etc.

* A curated list of PATHs associated with previous CVEs; you can use it to passively scan for endpoints associated with CVEs.

* Paths that typically expose API endpoints or server data. Perfect for finding more "hidden" APIs, interesting and verbose endpoints.


## Contribution
You are welcome to create a new pull request if you have a new endpoint to include or simply any unique paths that typically return juicy information.

Please keep in mind that the wordlist is intentionally kept short in order to focus only on high-quality endpoints, so it is not comprehensive enough for active scanning.

Please see [Assetnote](https://wordlists.assetnote.io/) and [SecLists](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content) for extended and large wordlists


## Credits

- A special thanks to [project-discovery](https://github.com/projectdiscovery/), a large part of the CVE endpoints were extracted from their projects. 
- Others were shared by various individuals on Twitter, Hackerone reports, own personal wordlists. 
