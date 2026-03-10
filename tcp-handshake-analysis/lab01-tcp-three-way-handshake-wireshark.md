# TCP Three-Way Handshake Analysis

## Filter Used

tcp.flags.syn == 1 && tcp.flags.ack == 0

## Description

TCP uses a three-step handshake to establish a reliable connection between a client and a server.

Sequence:

1. SYN
2. SYN-ACK
3. ACK

## Observations

Using the filter it was possible to identify packets initiating new TCP connections.

These packets represent the first step of the TCP handshake.

## Security Insight

Monitoring SYN packets can help detect:

- SYN flood attacks
- Unusual connection attempts
- Network scanning activity
