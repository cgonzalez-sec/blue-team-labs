# Basic Network Traffic Analysis with Wireshark

## Objective

Understand how common web traffic works by capturing and analyzing packets using Wireshark.

The goal of this lab was to observe how protocols like DNS, TCP, HTTP and TLS interact during normal web browsing.

---

## Environment

Tool used:

- Wireshark

Websites tested:

- example.com
- wikipedia.org
- instagram.com

Filters used:

- dns
- tcp.flags.syn == 1 && tcp.flags.ack == 0
- tls
- http
- ip.addr == X

---

## Traffic Capture Process

1. Start packet capture using Wireshark.
2. Open a web browser.
3. Visit different websites.
4. Apply filters to isolate specific network protocols.

---

## Protocols Observed

During the capture the following protocols were observed:

DNS → Domain name resolution  
TCP → Connection establishment  
TLS → Encrypted communication  
HTTP → Web content transfer

---

## Key Learning

When visiting a website several network steps occur:

1. DNS resolves the domain name to an IP address
2. TCP establishes a connection between client and server
3. TLS creates an encrypted channel (HTTPS)
4. HTTP transfers the requested content

Understanding this sequence is fundamental for network security analysis.

---

## Tools Used

Wireshark
