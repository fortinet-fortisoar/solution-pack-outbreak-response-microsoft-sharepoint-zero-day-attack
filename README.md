# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has detected and successfully blocked hundreds of exploitation attempts targeting a newly discovered zero-day vulnerability chain in on-premises Microsoft SharePoint servers. This active campaign is being exploited by multiple threat actors and poses a significant risk to a wide range of sectors including including government, education, healthcare, and large enterprises. 

 The **Outbreak Response - Microsoft SharePoint Zero-day Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.1.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/microsoft-sharepoint-zero-day) contains information about the outbreak alert **Outbreak Response - Microsoft SharePoint Zero-day Attack**. 

## Background: 

These vulnerabilities, particularly when chained together, allow unauthenticated remote attackers to gain unauthorized access and execute arbitrary commands on vulnerable SharePoint instances. Dubbed `ToolShell` by researchers, the attack chains together two previously addressed vulnerabilities (CVE‑2025‑49704 and CVE‑2025‑49706) into new zero-day variant (CVE‑2025‑53770 and CVE‑2025‑53771) .

As of this writing, Microsoft has observed two named Chinese nation-state actors, Linen Typhoon and Violet Typhoon exploiting these vulnerabilities.

Microsoft has released security updates that fully protect customers using all supported versions of SharePoint affected by CVE-2025-53770 and CVE-2025-53771 and has assessed with high confidence that threat actors will continue to integrate them into their attacks against unpatched on-premises SharePoint systems.

-To mitigate this threat, apply the latest security updates to affected versions of on-premises SharePoint servers.
-Follow recommended best practices and detection methods to reduce exposure.
-Monitor systems closely for signs of exploitation. 

## Announced: 

FortiGuard customers are protected by multiple layers of defense against these exploits. However, immediate patching of all affected SharePoint instances is strongly advised. The FortiGuard Incident Response team can be engaged to help with any suspected compromise.  

## Latest Developments: 

July 22, 2025: CISA added two new vulnerabilities to its Known Exploited Vulnerabilities (KEV) Catalog, based on evidence of active exploitation. CVE-2025-49704 Microsoft SharePoint Code Injection Vulnerability and CVE-2025-49706 Microsoft SharePoint Improper Authentication Vulnerability.


July 21, 2025: CISA adds CVE-2025-53770 to the Known Exploited Vulnerabilities (KEV) catalog. Organizations advised to remediate by federal deadlines.

July 20, 2025: FortiGuard publishes an Threat Signal providing more details. 
https://www.fortiguard.com/threat-signal-report/6159/microsoft-sharepoint-zero-day

July 19, 2025: Microsoft has observed two named Chinese nation-state actors, Linen Typhoon and Violet Typhoon exploiting these vulnerabilities targeting internet-facing SharePoint servers.
https://www.microsoft.com/en-us/security/blog/2025/07/22/disrupting-active-exploitation-of-on-premises-sharepoint-vulnerabilities/

July 19, 2025: On July 19, 2025, Microsoft Security Response Center (MSRC) published a blog addressing active attacks against on-premises SharePoint servers that exploit CVE-2025-49706, a spoofing vulnerability, and CVE-2025-49704, a remote code execution vulnerability. 
https://www.microsoft.com/en-us/security/blog/2025/07/22/disrupting-active-exploitation-of-on-premises-sharepoint-vulnerabilities/

July 19, 2025: Microsoft published information on CVE-2025-53770 and CVE-2025-53771.
https://msrc.microsoft.com/blog/2025/07/customer-guidance-for-sharepoint-vulnerability-cve-2025-53770/

July 17, 2025: Microsoft confirms active exploitation and begins investigation. 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
