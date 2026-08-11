# DNS Blocklist Mirror

Public, automatically updated mirrors for AdGuard Home.

The lists are synchronized every six hours by GitHub Actions. Downloads are validated before existing files are replaced, and commits are created only when content changes.

## Included lists

- HaGeZi Pro++
- HaGeZi Threat Intelligence Feeds (TIF)
- HaGeZi Pop-Up Ads
- HaGeZi Referral Allowlist
- Dandelion Sprout Anti-Malware (AdGuard Home format)

HaGeZi lists prefer the official GitLab mirror and fall back to GitHub. Dandelion Sprout uses GitHub with GitLab and AdGuard's Hostlists Registry as fallbacks.

## AdGuard Home URLs

- `https://raw.githubusercontent.com/dirtballs/dns-blocklist-mirror/main/blocklists/hagezi-pro-plus.txt`
- `https://raw.githubusercontent.com/dirtballs/dns-blocklist-mirror/main/blocklists/hagezi-tif.txt`
- `https://raw.githubusercontent.com/dirtballs/dns-blocklist-mirror/main/blocklists/hagezi-popup-ads.txt`
- `https://raw.githubusercontent.com/dirtballs/dns-blocklist-mirror/main/blocklists/hagezi-referral-allowlist.txt`
- `https://raw.githubusercontent.com/dirtballs/dns-blocklist-mirror/main/blocklists/dandelion-anti-malware.txt`
