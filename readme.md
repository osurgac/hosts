# Unified hosts file with base extensions

This repository consolidates several reputable `hosts` files, and merges them
into a unified hosts file with duplicates removed.  A variety of tailored hosts files are provided.

* Last updated: **July 28 2021**.
* Here's the [raw hosts file with base extensions](https://raw.githubusercontent.com/osurgac/hosts/master/hosts) containing 83,662 entries.


**Expectation**: These unified hosts files should serve all devices, regardless
of OS.

## Sources of hosts data unified in this variant

Updated `hosts` files from the following locations are always unified and
included:

Host file source | Description | Home page | Raw hosts | Update frequency | License | Issues
-----------------|-------------|:---------:|:---------:|:----------------:|:-------:|:------:
Steven Black's ad-hoc list | Additional sketch domains as I come across them. |[link](https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts) | [raw](https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts) | occasionally | MIT | [issues](https://github.com/StevenBlack/hosts/issues)
AdAway | AdAway is an open source ad blocker for Android using the hosts file. |[link](https://adaway.org/) | [raw](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt) | frequently | CC BY 3.0 | [issues](https://github.com/AdAway/adaway.github.io/issues)
add.2o7Net | 2o7Net tracking sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Dead | Dead sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Dead/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Risk | Risk content sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Spam | Spam sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
AdguardTeam cname trackers | CNAME-cloaked tracking abuses. |[link](https://github.com/AdguardTeam/cname-trackers) | [raw](https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/combined_disguised_trackers_justdomains.txt) | occasionally | MIT | [issues](https://github.com/AdguardTeam/cname-trackers/issues)
Mitchell Krog's - Badd Boyz Hosts | Sketchy domains and Bad Referrers from my Nginx and Apache Bad Bot and Spam Referrer Blockers |[link](https://github.com/mitchellkrogza/Badd-Boyz-Hosts) | [raw](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts) | weekly | MIT | [issues](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/issues)
hostsVN | Hosts block ads of Vietnamese |[link](https://github.com/bigdargon/hostsVN) | [raw](https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN) | occasionally | MIT | [issues](https://github.com/bigdargon/hostsVN/issues)
KADhosts | Fraud/adware/scam websites. |[link](https://kadantiscam.netlify.app/) | [raw](https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt) | frequently | CC BY-SA 4.0 | [issues](https://github.com/PolishFiltersTeam/KADhosts/issues)
MetaMask eth-phishing-detect | Phishing domains targeting Ethereum users. |[link](https://github.com/MetaMask/eth-phishing-detect) | [raw](https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/hosts.txt) | frequent | DON'T BE A DICK PUBLIC LICENSE | [issues](https://github.com/MetaMask/eth-phishing-detect/issues)
minecraft-hosts | Minecraft related tracker hosts |[link](https://github.com/jamiemansfield/minecraft-hosts) | [raw](https://raw.githubusercontent.com/jamiemansfield/minecraft-hosts/master/lists/tracking.txt) | occasionally | CC0-1.0 | [issues](https://github.com/jamiemansfield/minecraft-hosts/issues)
MVPS hosts file | The purpose of this site is to provide the user with a high quality custom HOSTS file. |[link](https://winhelp2002.mvps.org/) | [raw](https://winhelp2002.mvps.org/hosts.txt) | monthly | CC BY-NC-SA 4.0 | [issues](mailto:winhelp2002@gmail.com)
orca.pet | This is a domain list for blocking phishing and malware sites . |[link](https://orca.pet/notonmyshift/) | [raw](https://orca.pet/notonmyshift/hosts.txt) | frequent | ISC | [issues](https://github.com/socram8888/not-on-my-shift)
osint.digitalside.it | DigitalSide Threat-Intel malware domains list. |[link](https://github.com/davidonzo/Threat-Intel) | [raw](https://raw.githubusercontent.com/davidonzo/Threat-Intel/master/lists/latestdomains.piHole.txt) | daily | MIT | [issues](https://github.com/davidonzo/Threat-Intel/issues)
shady-hosts | Analytics, ad, and activity monitoring hosts |[link](https://github.com/shreyasminocha/shady-hosts) | [raw](https://raw.githubusercontent.com/shreyasminocha/shady-hosts/main/hosts) | occasionally | CC0-1.0 | [issues](https://github.com/shreyasminocha/shady-hosts/issues)
Dan Pollock – [someonewhocares](https://someonewhocares.org/) | How to make the internet not suck (as much). |[link](https://someonewhocares.org/hosts/) | [raw](https://someonewhocares.org/hosts/zero/hosts) | frequently | non-commercial with attribution | [issues](mailto:hosts@someonewhocares.org)
Tiuxo hostlist - ads | Categorized hosts files for DNS based content blocking |[link](https://github.com/tiuxo/hosts) | [raw](https://raw.githubusercontent.com/tiuxo/hosts/master/ads) | occasional | CC BY 4.0 | [issues](https://github.com/tiuxo/hosts/issues)
UncheckyAds | Windows installers ads sources sites based on https://unchecky.com/ content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
URLHaus | A project from [abuse.ch](https://abuse.ch/) with the goal of sharing malicious URLs. |[link](https://urlhaus.abuse.ch/) | [raw](https://urlhaus.abuse.ch/downloads/hostfile/) | weekly | CC0 | [issues](mailto:contactme@abuse.ch)
yoyo.org | Blocking with ad server and tracking server hostnames. |[link](https://pgl.yoyo.org/adservers/) | [raw](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0) | frequently |  | [issues](mailto:pgl@yoyo.org)

## Location of your hosts file

To modify your current `hosts` file, look for it in the following places and modify it with a text
editor.

**macOS (until 10.14.x macOS Mojave), iOS, Android, Linux**: `/etc/hosts` file.

**macOS Catalina:** `/private/etc/hosts` file.

**Windows**: `%SystemRoot%\system32\drivers\etc\hosts` file.

## Gentoo

Gentoo users may find [`sb-hosts`](https://github.com/PF4Public/gentoo-overlay/tree/master/net-misc/sb-hosts) in [::pf4public](https://github.com/PF4Public/gentoo-overlay) Gentoo overlay

## Updating hosts file on Windows

(NOTE: See also some third-party Hosts managers, listed below.)

On Linux and macOS, run the Python script. On Windows more
work is required due to compatibility issues so it's preferable to run the batch file as follows:

```sh
updateHostsWindows.bat
```

This file **MUST** be run in command prompt with administrator privileges in
the repository directory. In addition to updating the hosts file, it can also
replace the existing hosts file, and reload the DNS cache. It goes without
saying that for this to work, you must be connected to the internet.

To open a command prompt as administrator in the repository's directory, do the following:

**Windows XP**: Start → Run → `cmd`

**Windows Vista, 7**: Start Button → type `cmd` → right-click Command Prompt →
"Run as Administrator"

**Windows 8**: Start → Swipe Up → All Apps → Windows System → right-click Command Prompt →
"Run as Administrator"

**Windows 10**: Start Button → type `cmd` → right-click Command Prompt →
"Run as Administrator"

You can also refer to the "Third-Party Hosts Managers" section for further recommended solutions from third parties.

### Warning: Using this `hosts` file in Windows may require disabling DNS Cache service.

Windows has issues with larger hosts files. Recent changes in security within Windows 10 denies
access to changing services via other tools except registry hacks. Use the `disable-dnscache-service-win.cmd`
file to make proper changes to the Windows registry. You will need to reboot your device once that's done.
See the [the comments within the `cmd` file](https://github.com/StevenBlack/hosts/blob/master/disable-dnscache-service-win.cmd)
for more details.

## Reloading hosts file

Your operating system will cache DNS lookups. You can either reboot or run the following commands to
manually flush your DNS cache once the new hosts file is in place.

| The Google Chrome browser may require manually cleaning up its DNS Cache on `chrome://net-internals/#dns` page to thereafter see the changes in your hosts file. See: <https://superuser.com/questions/723703>

### Windows

Open a command prompt with administrator privileges and run this command:

```bat
ipconfig /flushdns
```

### Linux

Open a Terminal and run with root privileges:

**Debian/Ubuntu** `sudo service network-manager restart`

**Linux Mint** `sudo /etc/init.d/dns-clean start`

**Linux with systemd**: `sudo systemctl restart network.service`

**Fedora Linux**: `sudo systemctl restart NetworkManager.service`

**Arch Linux/Manjaro with Network Manager**: `sudo systemctl restart NetworkManager.service`

**Arch Linux/Manjaro with Wicd**: `sudo systemctl restart wicd.service`

**RHEL/Centos**: `sudo /etc/init.d/network restart`

**FreeBSD**: `sudo service nscd restart`

To enable the `nscd` daemon initially, it is recommended that you run the following commands:

```sh
sudo sysrc nscd_enable="YES"
sudo service nscd start
```

Then modify the `hosts` line in your `/etc/nsswitch.conf` file to the following:

```text
hosts: cache files dns
```

**Others**: Consult [this Wikipedia article](https://en.wikipedia.org/wiki/Hosts_%28file%29#Location_in_the_file_system).

### macOS

Open a Terminal and run:

```sh
sudo dscacheutil -flushcache;sudo killall -HUP mDNSResponder
```

## Goals of this unified hosts file

The goals of this repo are to:

1. automatically combine high-quality lists of hosts,

2. provide situation-appropriate extensions,

3. de-dupe the resultant combined list,

4. and keep the resultant file reasonably sized.

A high-quality source is defined here as one that is actively curated.  A
hosts source should be frequently updated by its maintainers with both
additions and removals.  The larger the hosts file, the higher the level of
curation is expected.

It is expected that this unified hosts file will serve both desktop and mobile
devices under a variety of operating systems.

## Third-Party Hosts Managers

* [Unified Hosts AutoUpdate](https://github.com/ScriptTiger/Unified-Hosts-AutoUpdate "Unified Hosts AutoUpdate") (for Windows): The Unified Hosts AutoUpdate package is purpose-built for this unified hosts project as well as in active development by community members. You can install and uninstall any blacklist and keep it automatically up to date, and can be placed in a shared network location and deployed across an organization via group policies. And since it is in active development by community members, your bug reports, feature requests, and other feedback are most welcome.

* [ViHoMa](https://github.com/cmabad/ViHoMa) is a Visual Hosts file Manager, written in Java, by Christian Martínez.  Check it out!

## Interesting Applications

* [Maza ad blocking](https://github.com/tanrax/maza-ad-blocking) is a bash script that automatically updates host file. You can also update a fresh copy. And each time it generates a dnsmasq-compatible configuration file. Fast installation, compatible with MacOS, Linux and BSD.

* [Hostile](https://github.com/feross/hostile) is a nifty command line utility to easily add or remove domains from your hosts file.  If our hosts files are too aggressive for you, you can use `hostile` to remove domains, or you can use `hostile` in a bash script to automate a post process each time you download fresh versions of hosts.

* [macOS Scripting for Configuration, Backup and Restore](https://github.com/tiiiecherle/osx_install_config) helps customizing, re-installing and using macOS. It also provides a [script](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/launchd_and_script/hosts_file_generator.sh) to install and update the hosts file using this project on macOS. In combination with a [launchd](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/launchd_and_script/com.hostsfile.install_update.plist) it updates the hosts file every x days (default is 4). To install both download the GitHub repo and run the [install script](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/install_hosts_file_generator_and_launchdservice.sh) from the directory one level up.

* [Pi-hole](https://pi-hole.net/) is a network-wide DHCP server and ad blocker that runs on [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi). Pi-hole uses this repository as one of its sources.

* [Block ads and malware via local BIND9 DNS server](https://github.com/mueller-ma/block-ads-via-dns "Block ads and malware via local DNS server") (for Debian, Raspbian & Ubuntu): Set up a local DNS server with a `/etc/bind/named.conf.blocked` file, sourced from here.

* [Block ads, malware, and deploy parental controls via local DualServer DNS/DHCP server](https://scripttiger.github.io/dualserver/ "Block ads, malware, and deploy parental controls via local DualServer DNS/DHCP server") (for BSD, Windows & Linux): Set up a blacklist for everyone on your network using the power of the unified hosts reformatted for DualServer. And if you're on Windows, this project also maintains an update script to make updating DualServer's blacklist even easier.

* [Blocking ads and malwares with unbound](https://deadc0de.re/articles/unbound-blocking-ads.html "Blocking ads and malwares with unbound") – [Unbound](https://www.unbound.net/ "Unbound is a validating, recursive, and caching DNS resolver.") is a validating, recursive, and caching DNS resolver.

* [dnsmasq conversion script](https://gist.github.com/erlepereira/c11f4f7a3f60cd2071e79018e895fc8a#file-dnsmasq-antimalware) This GitHub gist has a short shell script (bash, will work on any 'nix) and uses `wget` & `awk` present in most distros, to fetch a specified hosts file and convert it the format required by dnsmasq. Supports IPv4 and IPv6. Designed to be used as either a shell script, or can be dropped into /etc/cron.weekly (or wherever suits). The script is short and easily edited, also has a short document attached with notes on dnsmasq setup.

* [BlackHosts - Command Line Installer/Updater](https://github.com/Lateralus138/blackhosts) This is a cross-platform command line utility to help install/update hosts files found at this repository.
