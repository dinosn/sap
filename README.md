# sap
Collection of SAP resources for penetration testing
SAP Solution Manager (User Experience Monitoring), version- 7.2, due to Missing Authentication Check does not perform any authentication for a service resulting in complete compromise of all SMDAgents connected to the Solution Manager.
</code>

- [chipik/SAP_EEM_CVE-2020-6207](https://github.com/chipik/SAP_EEM_CVE-2020-6207)

### CVE-2020-6286 (2020-07-14)

<code>
The insufficient input path validation of certain parameter in the web service of SAP NetWeaver AS JAVA (LM Configuration Wizard), versions - 7.30, 7.31, 7.40, 7.50, allows an unauthenticated attacker to exploit a method to download zip files to a specific directory, leading to Path Traversal.
</code>

- [murataydemir/CVE-2020-6286](https://github.com/murataydemir/CVE-2020-6286)

### CVE-2020-6287 (2020-07-14)

<code>
SAP NetWeaver AS JAVA (LM Configuration Wizard), versions - 7.30, 7.31, 7.40, 7.50, does not perform an authentication check which allows an attacker without prior authentication to execute configuration tasks to perform critical actions against the SAP Java system, including the ability to create an administrative user, and therefore compromising Confidentiality, Integrity and Availability of the system, leading to Missing Authentication Check.
</code>

- [chipik/SAP_RECON](https://github.com/chipik/SAP_RECON)
- [duc-nt/CVE-2020-6287-exploit](https://github.com/duc-nt/CVE-2020-6287-exploit)
- [Onapsis/CVE-2020-6287_RECON-scanner](https://github.com/Onapsis/CVE-2020-6287_RECON-scanner)
- [ynsmroztas/CVE-2020-6287-Sap-Add-User](https://github.com/ynsmroztas/CVE-2020-6287-Sap-Add-User)
- [murataydemir/CVE-2020-6287](https://github.com/murataydemir/CVE-2020-6287)

### CVE-2020-6308 (2020-10-20)

<code>
SAP BusinessObjects Business Intelligence Platform (Web Services) versions - 410, 420, 430, allows an unauthenticated attacker to inject arbitrary values as CMS parameters to perform lookups on the internal network which is otherwise not accessible externally. On successful exploitation, attacker can scan internal network to determine internal infrastructure and gather information for further attacks like remote file inclusion, retrieve server files, bypass firewall and force the vulnerable server to perform malicious requests, resulting in a Server-Side Request Forgery vulnerability.
</code>

- [InitRoot/CVE-2020-6308-PoC](https://github.com/InitRoot/CVE-2020-6308-PoC)
- [freeFV/CVE-2020-6308-mass-exploiter](https://github.com/freeFV/CVE-2020-6308-mass-exploiter)

### CVE-2018-2380 (2018-03-01)

<code>
SAP CRM, 7.01, 7.02,7.30, 7.31, 7.33, 7.54, allows an attacker to exploit insufficient validation of path information provided by users, thus characters representing &quot;traverse to parent directory&quot; are passed through to the file APIs.
</code>

- [erpscanteam/CVE-2018-2380](https://github.com/erpscanteam/CVE-2018-2380)

### CVE-2018-2392 (2018-02-14)

<code>
Under certain conditions SAP Internet Graphics Server (IGS) 7.20, 7.20EXT, 7.45, 7.49, 7.53, fails to validate XML External Entity appropriately causing the SAP Internet Graphics Server (IGS) to become unavailable.
</code>

- [Vladimir-Ivanov-Git/sap_igs_xxe](https://github.com/Vladimir-Ivanov-Git/sap_igs_xxe)

### CVE-2016-2386 (2016-02-16)

<code>
SQL injection vulnerability in the UDDI server in SAP NetWeaver J2EE Engine 7.40 allows remote attackers to execute arbitrary SQL commands via unspecified vectors, aka SAP Security Note 2101079.
</code>

- [murataydemir/CVE-2016-2386](https://github.com/murataydemir/CVE-2016-2386)


### CVE-2016-4014 (2016-04-14)

<code>
XML external entity (XXE) vulnerability in the UDDI component in SAP NetWeaver JAVA AS 7.4 allows remote attackers to cause a denial of service (system hang) via a crafted DTD in an XML request to uddi/api/replication, aka SAP Security Note 2254389.
</code>

- [murataydemir/CVE-2016-4014](https://github.com/murataydemir/CVE-2016-4014)

### CVE-2013-3319 (2013-08-16)

<code>
The GetComputerSystem method in the HostControl service in SAP Netweaver 7.03 allows remote attackers to obtain sensitive information via a crafted SOAP request to TCP port 1128.
</code>

- [integrity-sa/cve-2013-3319](https://github.com/integrity-sa/cve-2013-3319)
