## Methodologies


### mySapAdventures (26 Aug 2020)

<code>
A quick methodology on testing/hacking SAP Applications for n00bz and bug bounty hunters
</code>

- [shipcod3/mySapAdventures](https://github.com/shipcod3/mySapAdventures)

### Metasploit generic
<code>
  Penetration test item command execution list using metasploit

1. Sap service discovery, for generic SAP discovery
- msf > use auxiliary/scanner/sap/sap_service_discovery

2. Sap info request, for route discovery
- use auxiliary/scanner/sap/sap_router_info_request

3. Sap router portscaner for proxy and dispacher identification.
- use auxiliary/scanner/sap/sap_router_portscanner

4. Service identification behind the sapni proxy
- use auxiliary/scanner/sap/sap_service_discovery

5. Testing a limited credential list.
- use auxiliary/scanner/sap/sap_soap_rfc_brute_login
[username, password - client]
SAP*, 06071992,PASS - 001, 066
DDIC, 199920706 - 000, 001
EARLYWATCH, SUPPORT - 000
SAPCPIC, ADMIN - 000, 001
TMSADM, PASSWORD,$1Pawd2& - 006
</code>
