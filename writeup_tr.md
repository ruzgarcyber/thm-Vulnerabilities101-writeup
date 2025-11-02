## TryHackMe Vulnerabilities 101 Writeup.
> Merhabalar, bugün sizlere **Vulnerabilities 101** Lab'ını Writeup şeklinde sunacağım.

## Bilgiler.
- Lab zorluğu: *Kolay*
- Writeup Yazarı: *Rüzgar Umut Gündoğan*
- Lab adı: *Vulnerabilities 101*
- Writeup Yazılma Tarihi: *2.11.2025*

## Lab'dan öğrendiklerim.
- Güvenlik Açıklarının veritabanını yani bulunmuş güvenlik açıklarının **Exploit-DB**'de ve **NVD – National Vulnerability Database**'de bulunduğunu öğrendim.
- *Vulnerability*, *Exploit*, *Proof of Concept (PoC)*, Bu terimlerin ne olduğunu ve anlamlarını öğrendim.
- Güvenlik açıklarının neden oluştuğunu öğrendim ve kategorilerini öğrendim; *Operating System*, *(Mis)Configuration-based*, *Weak or Default Credentials*, *Application Logic*, *Human-Factor*.

## Lab Sırasında yaptıklarım.
- TryHackMe içinde ki Web sayfasında, Jr. Penetration Tester olarak bi *Penetration Test* yaptım.
- İlk olarak Nmap taraması yaptım, ondan sonra açık olan port'a göre yola devam ettim. Açık olan Port'lar *22*, *80*, *443*, bu Portlardı ve ondan sonra o web sitesine bi Exploit yükledim. Ve böylece Flag'i Bulmuş oldum.
> NOT; Web sitesinde ki Güvenlik açığı Remote Code Execution (RCE) Açığıydı ve ona göre bi Exploit yüklemesi yapıldı.

## Hangi komutları kullandım;
- nmap 240.228.189.136
- run exploit -u http://240.228.189.136

## Referanslar.
- [TryHackMe](https://tryhackme.com)
- [TryHackMe | Vulnerabilities 101](https://tryhackme.com/room/vulnerabilities101)
- [nmap](https://nmap.org/)
- [Exploit-DB](https://www.exploit-db.com/)
- [NVD – National Vulnerability Database](https://nvd.nist.gov/)

## Teşekkür.
> Yazmış olduğum Writeup'ı okuduğunuz için çok teşekkür ederim, başka bi writeup'da görüşmek üzere...
