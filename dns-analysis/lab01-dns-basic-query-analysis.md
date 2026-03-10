# DNS Traffic Analysis

## Filter Used

dns

## Description

DNS (Domain Name System) is responsible for translating domain names into IP addresses.

When a user visits a website, the system first needs to discover the IP address associated with the domain.

Example:

example.com → 93.184.216.34

## Observations

During the capture the system sent a DNS query requesting the IP address of:

- example.com
- wikipedia.org
- instagram.com

The DNS server responded with the corresponding IP addresses.

## Security Insight

DNS traffic analysis can help detect:

- DNS tunneling
- Suspicious domains
- Malware communication
