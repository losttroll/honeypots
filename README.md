# Honeypots

This is an export of information from a few honeypots

### More info at:
A honeybot will Tweet about some of the sources: https://twitter.com/ShoestringSoc
And most are reported to AbuseIPDB: https://www.abuseipdb.com/user/52708

## Internet Noise Lists
Collection of lists focusing on internet-wide scans.  Blocking these sources may help to reduce load on the exposed service.

### SSH Brute Force Attacks
This is a list of sources that have had 10+ failed logins in the past 30 days. Connections are to ports 22,222,2220-2229.
https://github.com/losttroll/honeypots/blob/master/ssh_ips_last30days.txt

## Credential Lists
These are usernames and passwords used in internet-wide brute force attacks. Use these lists to audit exposesd services - if they really need to be on the Internet.

### SSH Brute Force Passwords
List of the most common passwords in the past 30 days. Ordered from most frequently used to least.
https://github.com/losttroll/honeypots/blob/master/ssh_top_passwords_last30days.txt

### SSH Top Credentials
Most frequently used username / password combinations seen in the last 30 days.  While a majority use root for the username, there are others that may be overlooked.
https://github.com/losttroll/honeypots/blob/master/ssh_top_credentials_last30days.txt
