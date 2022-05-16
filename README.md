# Wireshark 101
```Learn the basics of Wireshark and how to analyze various protocols and PCAPs```

[TryHackMe | Wireshark 101](https://tryhackme.com/room/wireshark)

## Task 1 Introduction
[TryHackMe | Network Fundamentals](https://tryhackme.com/module/network-fundamentals)

## Task 2 Installation
[Wireshark · Download](https://www.wireshark.org/download.html)

[Wireshark · Documentation](https://www.wireshark.org/docs/)

## Task 3 Wireshark Overview
[CaptureFilters](https://wiki.wireshark.org/CaptureFilters)

## Task 4 Collection Methods

## Task 5 Filtering Captures

### Filtering Operators
```
    and - operator: and / &&
    or - operator: or / ||
    equals - operator: eq / ==
    not equal - operator: ne / !=
    greater than - operator: gt /  >
    less than - operator: lt / <
```

[6.4. Building Display Filter Expressions](https://www.wireshark.org/docs/wsug_html_chunked/ChWorkBuildDisplayFilterSection.html)

### Basic Filtering
`ip.addr == <IP Address>`

`ip.src == <SRC IP Address> and ip.dst == <DST IP Address>`

`tcp.port eq <Port #> or <Protocol Name>`

`udp.port eq <Port #> or <Protocol Name>`

## Task 6 Packet Dissection

## Task 7 ARP Traffic

## Task 8 ICMP Traffic
[RFC 792 - Internet Control Message Protocol](https://datatracker.ietf.org/doc/html/rfc792)



