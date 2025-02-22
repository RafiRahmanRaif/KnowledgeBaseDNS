---
title: Pregled
sidebar_position: 1
slug: Početna stranica
---

## Šta je DNS

DNS stands for "Domain Name System", and its purpose is to convert websites' names into IP addresses. Svaki put kada odete na Web lokaciju, vaš pregledač šalje DNS upit DNS serveru da bi provalio IP adresu Web lokacije. A običan DNS razrešivač jednostavno vraća IP adresu zahtevanog domena.

> Podrazumevani DNS server obično obezbeđuje dobavljač Internet usluga. To znači da dobavljač Internet usluga može da prati vašu aktivnost na mreži i da prodaje evidencije trećim licima.

![Uređaj uvek koristi neki DNS server da bi dobio IP adrese aplikacija za ime domena do kojih želite da se krećete](https://cdn.adguard.com/content/blog/articles/dns-cbs/scr1.png)

There are also DNS servers that can block certain websites at DNS-level. Kako funkcionišu? When your device sends a "bad" request, be it an ad or a tracker, a DNS server prevents the connection by responding with a non-routable IP address for a blocked domain.

## Zašto koristiti DNS za blokiranje sadržaja

Sve je ovih dana povezano sa internetom, od TV-a do pametnih sijalica, od mobilnih uređaja do pametnog automobila. A gde je internet, tu su i reklame i tragači. U ovom slučaju, blokator reklama zasnovan na pregledniku izgleda da nije dovoljan. Da biste dobili bolju zaštitu, koristite DNS u kombinaciji sa VPN i blokatorom reklama.

Korišćenje DNS-a za blokiranje sadržaja ima neke prednosti, kao i očigledne nedostatke. S jedne strane, DNS nema slepe tačke pošto posmatra sve uređaje i ne samo pretraživače. Ali, sa druge strane, samo blokiranje DNS-a ne može da obezbedi kozmetičku filtraciju.

## Šta je AdGuard DNS

AdGuard DNS je jedna od DNS usluga koje najviše čuvaju privatnost na tržištu. Podržava takve pouzdane protokole za šifriranje kao što su DNS-over-HTTPS, DNS-over-TLS i DNS-over-QUIC. It can work as a regular DNS resolver in Non-filtering mode, but also it can provide DNS-level content blocking: identify requests to ad, tracking, and/or adult domains (optionally), and respond with an empty response. AdGuard ima sopstvenu bazu imena domena koja služe reklamama, tragačima i prevarama i redovno se ažurira.

![Približna šema kako AdGuard DNS funkcioniše](https://cdn.adguard.com/public/Adguard/Blog/scr2.png)

> Oko 75% AdGuard DNS saobraćaja je šifrovano. Ovo je zapravo ono što razlikuje sadržaj koji blokira DNS servere od drugih. Ako pogledate CloudFlare ili Quad9 statistiku, videćete da je šifrovani DNS samo mali deo svih upita.

AdGuard DNS postoji u dva glavna oblika: [javni AdGuard DNS](public-dns/overview.md) i [privatni AdGuard DNS](private-dns/overview.md). Obe ove usluge ne zahtevaju instaliranje aplikacija. One se lako podešavaju i koriste i pružaju korisnicima minimalne funkcije neophodne za blokiranje reklama, praćenja, zlonamernih Veb lokacija i sadržaja za odrasle (ako je potrebno). Ne postoje ograničenja na kojim uređajima mogu da se koriste.

Uprkos toliko sličnosti, privatni AdGuard DNS i javni AdGuard DNS su dve različite usluge. Njihova glavna razlika je u tome što možete da prilagodite privatni AdGuard DNS, dok javni AdGuard DNS ne možete.

## DNS podprogram za filtriranje u AdGuard proizvodima

Svi glavni AdGuard proizvodi, uključujući AdGuard VPN, imaju **DNS podprogram za filtriranje** gde možete izabrati DNS server od strane dobavljača u kojeg imate poverenja. Naravno, AdGuard DNS podrazumevani, AdGuard DNS bez filtriranja i AdGuard DNS porodična zaštita su na listi. Takođe, AdGuard aplikacije omogućavaju korisnicima da [konfigurišu i koriste AdGuard DNS](https://adguard-dns.io/en/public-dns.html) – javni ili privatni.







