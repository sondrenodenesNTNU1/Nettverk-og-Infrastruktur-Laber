# Nettverk-og-Infrastruktur-Laber
Samling av praktiske nettverkstekniske prosjekter gjennomført i emnet Datakommunikasjon og nettverk (DCST1006) og Sammenkoblede nettverk og nettverkssikkerhet (DCST2001). Labene ga praktisk erfaring av nettverksprotokoller, distribuert systemkommunikasjon og bedriftsnettverksarkitektur.

📡 Implementering av Nettverksprotokoller
VLAN & Inter-VLAN Routing Konfigurasjon
Teknologier: Cisco-svitsjer, Router-on-a-Stick, VLAN-segmentering
Implementering: Konfigurerte flere VLANer med inter-VLAN routing for nettverkssegmentering
Nøkkellæring: Forståelse av Layer 2/3 kommunikasjon essensielt for distribuert videokonferansearkitektur
Relevans for programvareutvikling: Nettverksisolering og routing-konsepter kritisk for mikrotjeneste-kommunikasjon

DHCPv4/DHCPv6 & SLAAC Implementering
Teknologier: Dynamisk IP-tildeling, IPv6 auto-konfigurasjon, DHCP relay
Implementering: Satte opp bedrifts-DHCP-tjenester med IPv4/IPv6 dual-stack konfigurasjon
Nøkkellæring: Automatisert nettverkskonfigurasjon og tjenesteoppdagelse
Relevans: Forståelse av dynamisk tjenestetildeling for skalerbare sky-videotjenester

IPv6 Nettverkskonfigurasjon & ICMPv6 Analyse
Teknologier: IPv6-adressering, SLAAC, Router Advertisements, ICMPv6
Implementering: Konfigurerte native IPv6-nettverk med automatisk adressekonfigurasjon
Nøkkellæring: Moderne IP-protokoller og neighbor discovery-mekanismer
Relevans: IPv6 er essensielt for global-skala videokonferanseplattformer

🔄 Høy Tilgjengelighet & Lastdistribusjon
HSRP (Hot Standby Router Protocol) Konfigurasjon
Teknologier: First Hop Redundancy, automatisk failover, virtuell IP
Implementering: Konfigurerte redundante gateway-tjenester for høy tilgjengelighet
Nøkkellæring: Failover-mekanismer og tjenestekontinuitet
Relevans: Kritisk for å bygge feiltolerante videokonferanse-infrastrukturer

STP & EtherChannel Implementering
Teknologier: Spanning Tree Protocol, Link Aggregation, redundante stier
Implementering: Forhindret nettverksløkker samtidig som redundans ble opprettholdt
Nøkkellæring: Nettverksresiliens og båndbreddeoptimalisering
Relevans: Load balancing og redundans-konsepter for distribuerte videotjenester

OSPF (Open Shortest Path First) Implementering - OBLIGATORISK LAB
Teknologier: Dynamisk routing, link-state protokoll, area-design
Implementering: Konfigurerte OSPF routing protocol for automatisk path-optimalisering
Nøkkellæring: Skalerbar routing og nettverkskonvergering
Relevans: Kritisk for intelligente path-selection i store video-distribusjonsnettverk

Statisk Ruting & Path Control
Teknologier: Route tables, administrative distance, route redistribution
Implementering: Manuell route-konfigurasjon og traffic engineering
Nøkkellæring: Granular control over nettverks-traffic flow
Relevans: Essensielt for optimalisering av video-traffic routing og QoS

🔒 Nettverkssikkerhet & Ytelse
Access Control Lists (ACL) Implementering - OBLIGATORISK LAB
Teknologier: Standard/Extended ACLs, traffic filtering, security policies
Implementering: Konfigurerte granular traffic control og sikkerhetsfiltrering
Nøkkellæring: Network-level access control og threat mitigation
Relevans: Fundamental for sikring av enterprise videokonferanse-traffic og data protection

Avansert Nettverkssikkerhet
Teknologier: Advanced security protocols, intrusion prevention, network hardening
Implementering: Implementerte comprehensive security measures for enterprise nettverk
Nøkkellæring: Multi-layered security approach og best practices
Relevans: Kritisk for sikring av sensitive business communications og video data

Nettverkssikkerhets-hardening
Teknologier: Svitsj-sikkerhet, port-sikkerhet, tilgangskontroll
Implementering: Konfigurerte bedriftssikkerhetstiltak og tilgangskontroller
Nøkkellæring: Nettverkssikkerhet beste praksis og trussel-redusering
Relevans: Sikkerhet er avgjørende i bedrifts-videokonferanseløsninger

Nettverksytelses-analyse med Wireshark
Teknologier: Pakkefangst, TCP/HTTP-analyse, protokoll-debugging
Implementering: Dyp pakkeinspeksjon og nettverksfeilsøking
Nøkkellæring: Forståelse av nettverks-ytelsesbegrensninger og optimalisering
Relevans: Essensielt for optimalisering av video-streaming protokoller og redusering av latens

Nettverksforbindelses-testing & Diagnostikk
Teknologier: Ping, Traceroute, RTT-måling, ARP-analyse
Implementering: Systematisk nettverksdiagnostikk og ytelsesmåling
Nøkkellæring: Nettverksfeilsøking-metodikker og ytelsesmetrikker
Relevans: Kritisk for overvåking og optimalisering av videokonferanse-kvalitet

🏗️ Nettverksdesign & Arkitektur
Bedriftsnettverks-designprosjekt
Teknologier: Nettverkstopologi-design, subnetting, VLSM
Implementering: Designet og implementerte komplett bedriftsnettverks-infrastruktur
Nøkkellæring: Skalerbar nettverksarkitektur og adresseringsskjemaer
Relevans: Forståelse av infrastrukturkrav for store-skala videotjenester

Subnetting & VLSM (Variable Length Subnet Masking)
Teknologier: IP-adressering, subnet-optimalisering, adresserom-planlegging
Implementering: Effektiv IP-adresse tildeling for komplekse nettverkstopologier
Nøkkellæring: Nettverksressurs-optimalisering og skalerings-planlegging
Relevans: Essensielt for å designe skalerbare sky-videokonferansenettverk

🔧 Nettverksfeilsøking & Optimalisering
MAC-adresse & ARP-tabell Analyse
Teknologier: Layer 2-adressering, ARP-protokoll, nettverksoppdagelse
Implementering: Analyserte nettverkskommunikasjon på datalink-laget
Nøkkellæring: Forståelse av lavnivå nettverkskommunikasjons-mekanismer
Relevans: Grunnleggende kunnskap for optimalisering av video-streaming protokoller

TCP/HTTP Protokoll-analyse
Teknologier: Applikasjonslag-protokoller, økt-styring, ytelses-analyse
Implementering: Analyserte applikasjonsnivå nettverkskommunikasjons-mønstre
Nøkkellæring: Forståelse av hvordan applikasjoner kommuniserer over nettverk
Relevans: Direkte anvendelse til HTTP-baserte videokonferanse APIer og WebRTC

💡 Viktige Tekniske Ferdigheter Utviklet
Nettverksprogrammerings-konsepter
Socket-nivå kommunikasjon forståelse fra protokoll-analyse
Samtidig tilkoblings-håndtering fra svitsj/ruter-konfigurasjon
Load balancing-strategier fra HSRP og EtherChannel implementering
Ytelses-optimalisering fra Wireshark-analyse og nettverks-tuning
Distribuert System Arkitektur
Tjenesteoppdagelse gjennom DHCP og IPv6 auto-konfigurasjon
Feiltoleranse gjennom redundans-protokoller (HSRP, STP)
Skaleringsplanlegging gjennom nettverks-designprosjekter
Sikkerhets-implementering på nettverksinfrastruktur-nivå
Protokoll-implementerings Forståelse
TCP/UDP-oppførsel fra pakke-nivå analyse
Sanntids-kommunikasjon krav fra nettverks-ytelsestesting
Quality of Service betraktninger fra nettverks-optimaliseringslaber
IPv4/IPv6 dual-stack implementering for global tilkobling
🎯 Relevans for Videokonferanse & Sanntidskommunikasjon
Denne praktiske nettverkserfaringen gir avgjørende forståelse for å bygge skalerbare videokonferanseplattformer:

Nettverks-latens optimalisering - Essensielt for sanntids video/audio
Load balancing implementering - Nødvendig for håndtering av tusenvis av samtidige video-strømmer
Failover og redundans - Kritisk for bedrifts-videokonferanse pålitelighet
Protokoll-nivå forståelse - Nødvendig for optimalisering av WebRTC og tilpassede video-protokoller
Sikkerhets-implementering - Nødvendig for bedrifts-grad sikre kommunikasjoner
Ytelses-analyse - Essensielt for opprettholdelse av videokvalitet under varierende nettverksforhold
📚 Støttende Kunnskapsområder
Nettverksytelse & QoS
Forståelse av båndbredde-styring, latens-optimalisering og quality of service implementering - direkte anvendbart for opprettholdelse av videokonferanse-kvalitet.

IPv6 & Moderne Nettverk
Praktisk erfaring med IPv6-implementering essensielt for global-skala videokonferanseplattformer som betjener internasjonale brukere.

Sikkerhets Beste Praksis
Nettverksnivå sikkerhetsforståelse gir grunnlag for implementering av sikre videokonferanseløsninger.

📁 Labdokumentasjon og Ressurser
Gjennomførte Labøvinger (DCST1006 - Vårtermin)
Lab 2: Grunnleggende svitsj-konfigurasjon og Wireshark
Lab 3: Subnett og ruter-konfigurasjon
Lab 4: MAC, ARP, RTT konsolidering
Lab 5: Bygg svitsj og ruter nettverk
Lab 7: IP Subnetting og VLSM (Obligatorisk godkjenning)
Lab 9: IPv6/ICMPv6 og Wireshark TCP/HTTP analyse (Obligatorisk)
Lab 12: VLAN Router-on-a-Stick (Obligatorisk godkjenning)
Lab 13: STP og EtherChannel
Lab 14: DHCPv4/DHCPv6 implementering (Obligatorisk)
Lab 15: HSRP konfigurasjon
Lab 17: Svitsj-sikkerhet konfigurasjon
Avanserte Nettverkslaber (Høsttermin)
Lab Uke 34: Statisk ruting konfigurasjon
Lab Uke 35: OSPF (Open Shortest Path First) - OBLIGATORISK
Lab Uke 36: Network Security implementering
Lab Uke 37: Access Control Lists (ACL) - OBLIGATORISK
Tekniske Verktøy & Platformer
Cisco Packet Tracer: Nettverks-simulering og konfigurasjon
Cisco IOS: Ruter og svitsj kommandolinje-konfigurasjon
Wireshark: Pakke-analyse og protokoll-debugging
IPv6 implementering: SLAAC, DHCPv6, ICMPv6
Enterprise networking: VLAN, HSRP, STP, EtherChannel
Security protocols: ACLs, network hardening, access control
Denne praktiske nettverkserfaringen, kombinert med programmeringsferdigheter, gir et sterkt grunnlag for å bygge robust, skalerbar og sikker videokonferanse-infrastruktur.


