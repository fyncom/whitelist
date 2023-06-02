# The FynCom Whitelist

Since FynCom's anti-spam technology has moved into emails, the JSON file at [domains.json](domains.json) will serve as a public record of which web domains 
FynCom is actively whitelisting. 

This will be a living document, with rules that are expected to change over time as we explore the effects of 
FynCom technology on the internet.

## Guidelines
- An individual's personal blacklist takes precedence over this global whitelist
- Subdomains of the main url are not automatically whitelisted
  - Only the subdomains included in the domains list, if available, are also whitelisted with the parent domain. 
- The "emails" JSON is more selective, only allowing for certain addresses from a domain to be whitelisted, instead of emails from the entire domain
- Reasons for each URL are provided in the JSON file
  - in some cases, the reasons are obvious, and thus not filled in. 

## Add your url
If you would like to add your url to the whitelist, please submit a pull request or email us at support@fyncom.com
