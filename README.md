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

## Task 9 TCP Traffic
[RFC 793 - Transmission Control Protocol](https://datatracker.ietf.org/doc/html/rfc793)

## Task 10 DNS Traffic
[https://www.ietf.org/rfc/rfc1035.txt](https://www.ietf.org/rfc/rfc1035.txt)

## Task 11 HTTP Traffic
[Download Task File](https://github.com/r1skkam/TryHackMe-Wireshark-101/blob/main/http.cap)

[IETF on HTTP methods](https://www.ietf.org/rfc/rfc2616.txt)

### Wireshark's built-in features
[Statistics > Protocol Hierarchy](https://github.com/r1skkam/TryHackMe-Wireshark-101/blob/main/Wireshark%20-%20Protocol%20Hierarchy%20Statistics.png)

[File > Export Objects > HTTP](https://github.com/r1skkam/TryHackMe-Wireshark-101/blob/main/Wireshark%20-%20Export%20-%20HTTP%20object%20list.png)

[Statistics > Endpoints](https://github.com/r1skkam/TryHackMe-Wireshark-101/blob/main/Wireshark%20-%20Endpoints.png)

