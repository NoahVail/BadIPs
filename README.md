GmailSendingIPs: For my limited-use email server. It receives no legit gmail.com emails, only spam. However, I need to receive DMARC reports from Google. I can't block gmail's entire IP space. 

GoogleDMARCSendingIPs: Every IP I have found sending DMARC reports on behalf of Google. 

ShadowServer 24: Eight CIDR that contain every IP ShadowServer IPv4 address. I found this by looking up every possible domain name that fits SS's naming patterns. Last run in April 2024. 

ShadoowServer IPv6: IPv6 addresses found during aformentioned SS scan.

Stretchoid IPv4: The entirety of AS8075 gets scanned every 6 hours for Stretchoid IPs.

Stretchoid backstory: I kept getting Stretchoid scans, even tho I had stretchoid blocklits in place.
Searching for these newfound stretched IPs revealed that none of the blocklist providers had these IP, often not days later.
From what I tell, Stretchoid is continually adding to/deleting from it's IP group. That would seem to be why other list providers are lacking.

Of note: I reviewed a few stretchoid blocklists and couldn't find one that was more that 50% current. Most were in the single digits.
