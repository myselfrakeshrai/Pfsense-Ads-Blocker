# Pfsense-Ads-Blocker
pfsense advertisement blocker

https://raw.githubusercontent.com/rakeshrai10046/Pfsense-Ads-Blocker/main/ads-blocker
#Get this from https://firebog.net/
##The Big Blocklist Collection
The Internet is full of unsavoury content: advertisers wanting to sell you stuff you don't need, trackers extracting and selling your data as if it were oil, and malicious content vying to hijack your favourite device. This collection hopes to help you minimise these issues, and to maintain a more enjoyable online presence, using the wonderful, free and open source utility known as Pi-hole.

On arrival, like a growing number of websites, Forbes asked readers to turn off ad blockers in order to view the article. After doing so, visitors were immediately served with pop-under malware, primed to infect their computers, and likely silently steal passwords, personal data and banking information. Or, as is popular worldwide with these malware "exploit kits," lock up their hard drives in exchange for Bitcoin ransom.
'Forbes Site, After Begging You To Turn Off Adblocker, Serves Up A Steaming Pile Of Malware 'Ads'' - Techdirt, 2016
Before starting, here are some reading points:
Lists in green and bulleted with a tick are least likely to interfere with browsing
Lists that have a strike through them are not recommended for use (E.G: Many false postives, deprecated, biased)
A tool to help keep your blocklists in sync is found here
If you wish to automate the update of your blocklist sources, URL-only and CSV versions are found here
Using lists hosted at v.firebog.net allows me to view very basic ongoing aggregated statistics via CloudFlare
These lists are painstakingly worked on by their respective maintainers. Please contact them first if you find false positives
Avoid using mirrored consolidated lists, if possible; it deprives the original list maintainer of visits (meaning they may be less inclined to keep it up to date!)
Suspicious Lists
https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
https://v.firebog.net/hosts/static/w3kbl.txt
https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
https://someonewhocares.org/hosts/zero/hosts
https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts
https://winhelp2002.mvps.org/hosts.txt
https://v.firebog.net/hosts/neohostsbasic.txt
https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt
https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt
https://hostsfile.mine.nu/hosts0.txt
https://v.firebog.net/hosts/BillStearns.txt
https://hostsfile.org/Downloads/hosts.txt
https://www.joewein.net/dl/bl/dom-bl-base.txt
https://v.firebog.net/hosts/Kowabit.txt
https://adblock.mahakala.is
Advertising Lists
https://adaway.org/hosts.txt
https://v.firebog.net/hosts/AdguardDNS.txt
https://v.firebog.net/hosts/Admiral.txt
https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt
https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
https://v.firebog.net/hosts/Easylist.txt
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts
https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts
Tracking & Telemetry Lists
https://v.firebog.net/hosts/Easyprivacy.txt
https://v.firebog.net/hosts/Prigent-Ads.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts
https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt
https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt
https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
https://v.firebog.net/hosts/Airelle-trc.txt
https://raw.githubusercontent.com/Kees1958/W3C_annual_most_used_survey_blocklist/6b8c2411f22dda68b0b41757aeda10e50717a802/TOP_EU_US_Ads_Trackers_HOST
Malicious Lists
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt
https://v.firebog.net/hosts/Prigent-Crypto.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt
https://phishing.army/download/phishing_army_blocklist_extended.txt
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt
https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt
https://raw.githubusercontent.com/Te-k/stalkerware-indicators/master/generated/hosts
https://urlhaus.abuse.ch/downloads/hostfile/
https://v.firebog.net/hosts/Prigent-Malware.txt
https://v.firebog.net/hosts/Shalla-mal.txt
https://v.firebog.net/hosts/Airelle-hrsk.txt
https://raw.githubusercontent.com/tg12/pihole-phishtank-list/master/list/phish_domains.txt
https://raw.githubusercontent.com/HorusTeknoloji/TR-PhishingList/master/url-lists.txt
Other Lists
https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser
https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_top1m.list
https://v.firebog.net/hosts/Prigent-Adult.txt
https://raw.githubusercontent.com/anudeepND/blacklist/master/facebook.txt
Whitelisting Suggestions
The more blocklists you add, the more likely you'll come across a false positive. First, you'll want to check out Commonly Whitelisted Domains over at the Pi-hole forum, followed up by anudeepND's curated whitelist, and then you can see if anything below is relevant to your interests.
