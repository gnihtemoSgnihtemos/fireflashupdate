fireflashupdate
====

Adobe Flash Player installer/updater for Mozilla Firefox on Linux.

Tested in Debian 9 stable (stretch), but should work on every Linux distro.

## Getting started

1) Clone the repository using git or download it manually

2) Unzip the repository and set the execution permission to the script:

```bash
 $chmod +x fireflashupdate.sh
```
3) Execute the script to install or update Adobe Flash Player for Mozilla Firefox:

```bash
 $./fireflashupdate.sh
```

## How To

- Execute the script daily with cron/anacron for automatic update:
```bash
$sudo chown root:root fireflashupdate.sh
$sudo mv fireflashupdate.sh /etc/cron.daily/fireflashupdate
```

License and Donations
-------

Coded by Andrea Dari and licensed under GNU GPL v2.0

Support me for updates and new projects: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=andreadari91%40gmail%2ecom&lc=IT&item_name=Andrea%20Dari%20FOSS%20developer%20support&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" alt="[paypal]" /></a>

Thank you!
