# Advanced Google searches
Advanced Google search allows you to filter your search and thus obtain much more targeted and relevant results for your target.

## Additional Informations
All these commands can be added together using the prefix “OR” between each one.


## Commands
- ``targeted_keyword site:targeted-site.com`` ― return search results related to the targeted keyword from the targeted site

- ``targeted_keyword filetype:targeted_type`` ― return search results related to the targeted keyword into your targeted file type

# Advanced Google searches
Advanced Google search allows you to filter your search and thus obtain much more targeted and relevant results for OSINT investigations, reconnaissance, and information gathering.

## Additional Informations
All these commands can be added together using the prefix “OR” between each one.  
They can also be combined with quotes `" "` for exact matches and exclusions using `-keyword`.

## Commands

- ``targeted_keyword site:targeted-site.com``  
  ― return search results related to the targeted keyword from the targeted site  
  Example: ``admin panel site:example.com``

- ``targeted_keyword filetype:targeted_type`` ― return search results related to the targeted keyword in a specific file type  
  Example: ``confidential filetype:pdf``

- ``targeted_keyword intitle:keyword`` ― return pages that contain the keyword in the page title (useful to find login pages, dashboards, panels)  
  Example: ``intitle:login``

- ``targeted_keyword inurl:keyword`` ― return pages that contain the keyword in the URL (useful for exposed paths)  
  Example: ``inurl:admin``

- ``site:targeted-site.com filetype:txt`` ― find text files on a specific website (often logs, notes, configs)  
  Example: ``site:example.com filetype:txt``

- ``site:targeted-site.com intitle:index of`` ― find open directories (directory listing enabled)  
  Example: ``site:example.com intitle:"index of"``

- ``filetype:env OR filetype:yaml OR filetype:json`` ― search for configuration files that may contain sensitive information  
  Example: ``database filetype:env``

- ``"targeted phrase"`` ― return only results containing the exact phrase  
  Example: ``"internal use only"``

- ``targeted_keyword -excluded_keyword`` ― exclude unwanted results from your search  
  Example: ``admin panel -wordpress``

- ``site:github.com targeted_keyword`` ― search for exposed code, API keys, or credentials on GitHub  
  Example: ``site:github.com api_key``

- ``site:pastebin.com OR site:paste.ee targeted_keyword`` ― search paste websites for leaked information  
  Example: ``site:pastebin.com password``

- ``site:linkedin.com/in targeted_keyword`` ― gather information about employees or roles (useful for recon & social engineering context)  
  Example: ``site:linkedin.com/in cybersecurity Belgium``

- ``cache:targeted-site.com`` ― view Google’s cached version of a page (useful if content was deleted)  
  Example: ``cache:example.com``

- ``related:targeted-site.com`` ― find websites related to a given domain  
  Example: ``related:example.com``

## Notes
These operators are commonly used during:
- OSINT investigations
- Reconnaissance phases
- Bug bounty research
- Red team preparation
- Digital footprint analysis

Use them responsibly and only in legal and ethical contexts.
```
