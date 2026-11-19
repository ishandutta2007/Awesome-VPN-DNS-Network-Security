# Awesome-VPN-DNS-Network-Security

## Top VPN & DNS Network Security Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on DNS Tunneling VPNs, Encrypted DNS (DoH/DoT/DoQ/DNSCrypt), Network-Wide Ad/Malware Sinkholes, Mesh VPNs & Censorship-Resistant Transports*  

**Last updated: November 2026**



This repository (`Awesome-VPN-DNS-Network-Security`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **VPN & DNS Network Security** — Top VPN DNS Network Security (Opensource) 🌟 Star if you like it! 🌟. These tools combine encrypted VPN routing with DNS-level threat filtering, tunnel IP/TCP traffic inside legitimate DNS queries to traverse restrictive captive portals and firewalls, enforce DNS-over-HTTPS (DoH) / DNS-over-TLS (DoT) / DNS-over-QUIC (DoQ), and deploy self-hosted recursive DNS resolvers alongside mesh overlays.



**Examples** include Tailscale, Cloudflare WARP, ZeroTier, Mullvad VPN, Proton VPN, NordVPN, ExpressVPN, Surfshark, IVPN, Windscribe, and `masterking32/MasterDnsVPN` (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for DNS-over-VPN tunneling utilities, self-hosted DNS sinkholes and recursive resolvers, encrypted DNS proxies, mesh overlay networks, and obfuscated VPN engines — ideal for network security engineers, privacy advocates, sysadmins, and self-hosters.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cloudflare WARP & 1.1.1.1 / Gateway](https://one.one)**  

  Global anycast encrypted VPN and Zero Trust DNS filtering platform combining BoringTun WireGuard tunnels with ultra-fast DoH/DoT/DoQ resolution and malware blocking.



- **[Tailscale](https://tailscale.com)**  

  Zero-config WireGuard mesh VPN featuring built-in MagicDNS internal service discovery, split-DNS routing, NextDNS/Mullvad exit-node integration, and automatic NAT traversal.



- **[ZeroTier](https://zerotier.com)**  

  Software-defined virtual Ethernet and peer-to-peer mesh overlay network providing encrypted Layer-2/Layer-3 connectivity and private network DNS resolution across NATs.



- **[Mullvad VPN & Mullvad DNS](https://mullvad.net)**  

  Privacy-first VPN provider offering anonymous accounts, WireGuard multihop tunnels, DAITA anti-tracking, and free public encrypted DNS resolvers with ad/tracker/malware blocking.



- **[Proton VPN & NetShield](https://protonvpn.com)**  

  Swiss-based privacy VPN service featuring open-source clients, Secure Core routing, Stealth obfuscation, and NetShield DNS-level ad, tracker, and malware filtering.



- **[NordVPN & Threat Protection](https://nordvpn.com)**  

  Commercial VPN service built around NordLynx (WireGuard), Meshnet peer routing, and DNS-level Threat Protection against phishing domains and trackers.



- **[ExpressVPN](https://expressvpn.com)**  

  Global commercial VPN platform operating private, zero-knowledge encrypted DNS on every server alongside the Lightway protocol and TrustedServer RAM-only architecture.



- **[Surfshark & CleanWeb](https://surfshark.com)**  

  Cross-platform cloud VPN service featuring WireGuard tunneling, CleanWeb DNS ad/malware blocking, MultiHop routing, and rotating IP protection.



- **[IVPN & AntiTracker](https://ivpn.net)**  

  Independently audited privacy VPN offering open-source clients, WireGuard key rotation, multi-hop tunnels, and AntiTracker DNS blocklists.



- **[Windscribe & R.O.B.E.R.T.](https://windscribe.com)**  

  Cloud VPN and customizable DNS firewall service allowing granular domain/IP blocking, WireGuard/OpenVPN config generation, and stealth protocol obfuscation.



- **[NextDNS](https://nextdns.io)**  

  Cloud-hosted customizable encrypted DNS firewall offering real-time analytics, threat intelligence feeds, parental controls, and native integration with Tailscale and mobile OSes.



- **[Control D](https://controld.com)**  

  Programmable cloud DNS resolver and smart-routing proxy capable of blocking ads/malware and tunneling specific domains through global exit locations without a full VPN.



## Open-Source GitHub Projects



- **[MasterDnsVPN (masterking32/MasterDnsVPN)](https://github.com)**  

  High-speed, multi-threaded open-source DNS tunnel VPN written in Python with asynchronous I/O, SOCKS5 proxy support, multi-resolver load balancing, and automatic MTU negotiation for traversing restrictive firewalls.



- **[iodine (yarrick/iodine)](https://github.com)**  

  Classic open-source IP-over-DNS tunneling daemon written in C that encapsulates full IPv4 network traffic inside standard DNS queries and responses when only DNS port 53 is open.



- **[dnscat2 (iagox86/dnscat2)](https://github.com)**  

  Open-source encrypted Command-and-Control and TCP tunneling utility designed to establish secure, authenticated channels purely over the DNS protocol.



- **[dns2tcp (alex-sector/dns2tcp)](https://github.com)**  

  Lightweight open-source tool for relaying TCP connections (such as SSH or SOCKS proxies) encapsulated inside DNS TXT/KEY queries without requiring TUN/TAP interfaces.



- **[Slipstream / dnstt (Mygod/dnstt)](https://github.com)**  

  Modern censorship-resistant open-source DNS tunnel supporting encrypted DNS-over-HTTPS (DoH) and DNS-over-TLS (DoT) resolvers with Noise protocol cryptography and KCP reliability.



- **[AdGuard Home (AdguardTeam/AdGuardHome)](https://github.com)**  

  Self-hosted open-source network-wide DNS sinkhole and encrypted DNS server supporting DoH, DoT, DoQ, and DNSCrypt with per-client firewall rules for VPN gateways.



- **[Pi-hole (pi-hole/pi-hole)](https://github.com)**  

  Industry-standard open-source network-level DNS ad and tracker blocker widely deployed alongside WireGuard and OpenVPN to protect mobile and home networks.



- **[Technitium DNS Server (TechnitiumSoftware/DnsServer)](https://github.com)**  

  Full-featured open-source authoritative and recursive DNS server written in C#/.NET supporting DNSSEC, DoH, DoT, DoQ, split-horizon zones, and threat blocklists.



- **[Unbound (NLnetLabs/unbound)](https://github.com)**  

  Validating, recursive, and caching open-source DNS resolver written in C supporting DNSSEC validation, DNS-over-TLS, QNAME minimization, and zero third-party DNS logging.



- **[CoreDNS (coredns/coredns)](https://github.com)**  

  CNCF graduated open-source DNS server written in Go featuring a flexible plugin chain for service discovery, DNS-over-TLS/gRPC/QUIC, and Kubernetes/VPN split DNS.



- **[Blocky (0xERR0R/blocky)](https://github.com)**  

  Fast, lightweight open-source DNS proxy and ad-blocker written in Go supporting DoH/DoT, Prometheus metrics, Redis caching, and per-group client filtering.



- **[dnscrypt-proxy (DNSCrypt/dnscrypt-proxy)](https://github.com)**  

  Flexible open-source encrypted DNS proxy supporting DNSCrypt v2, DNS-over-HTTPS (DoH), Anonymized DNS relays, and local domain cloaking/filtering.



- **[Headscale (juanfont/headscale)](https://github.com)**  

  Open-source self-hosted control server for Tailscale providing private mesh VPN coordination, MagicDNS split-DNS resolution, and exit node routing.



- **[NetBird (netbirdio/netbird)](https://github.com)**  

  Open-source zero-trust peer-to-peer VPN platform combining WireGuard encryption with custom private DNS management, SSO authentication, and WebRTC NAT traversal.



- **[Netmaker (gravitl/netmaker)](https://github.com)**  

  High-speed open-source WireGuard mesh overlay and automated virtual networking platform with integrated CoreDNS private domain resolution.



- **[Firezone (firezone/firezone)](https://github.com)**  

  Open-source zero-trust access platform built on WireGuard supporting wildcard DNS resource routing, split tunneling, and identity-based access policies.



- **[WireGuard (WireGuard/wireguard-linux & wireguard-go)](https://github.com)**  

  Modern, cryptographically lean open-source VPN protocol integrated into the Linux kernel with official cross-platform mobile and desktop clients.



- **[AmneziaVPN & AmneziaWG (amnezia-vpn/amnezia-client)](https://github.com)**  

  Open-source censorship-resistant VPN suite deploying obfuscated WireGuard (`AmneziaWG`), OpenVPN over Cloak, and Xray-Reality alongside self-hosted DNS containers.



- **[wg-easy (wg-easy/wg-easy)](https://github.com)**  

  All-in-one open-source Docker container combining WireGuard and a modern web admin UI with configurable custom DNS servers and one-click mobile QR codes.



- **[sing-box (SagerNet/sing-box)](https://github.com)**  

  Universal open-source proxy and VPN platform written in Go featuring a rule-based fake-IP/DoH/DoQ DNS engine alongside WireGuard, VLESS-Reality, and Hysteria2 transports.



- **[Xray-core (XTLS/Xray-core)](https://github.com)**  

  High-performance open-source encrypted tunneling core featuring built-in DNS routing, split tunneling, VLESS, and XTLS-Reality camouflage.



- **[RethinkDNS / Rethink Firewall + DNS + VPN (celzero/rethink-app)](https://github.com)**  

  Open-source Android on-device VPN firewall, WireGuard client, and encrypted DNS resolver (DoH/DNSCrypt/ODoH) blocking trackers and spyware without root.



- **[PersonalDNSfilter (IngoZenz/personaldnsfilter)](https://github.com)**
