# TSS-WEB (an Open Framework of Security Requirements for Web-based Applications & Services)

This is the official site of TSS-WEB, an open requirement framework consisting more than 200 general AppSec requirements. All these requirements are based on common best practices (including those from OWASP, SAFECode, ISO/IEC 27002, and NIST), along with our own experiences in this field.

For instance, implementing TSS-WEB also meets 14.2.1 control ("Secure Development Policy") of ISO/IEC 27002. Detailed compliance mappings are detailed below.

## Purpose

The purpose of this framework is to provide a comprehensive collection of technical and organizational AppSec controls for creating your own security standards, policies, or security concepts. You can use all of them or just select the ones you need. In many cases, you might need to adapt some of them or add others that are more relevant to your specific organization or technology stack.

## Types of Requirements

The requirements in this framework are primarily baseline requirements, suitable for all applications and services. Additionally, there are a few requirements specifically for more critical applications. These requirements often demand more effort to implement and address risks that may not be significant for all applications. To differentiate these, we use the term "assurance level."

## SSDLC Requirements

1. [General](A_SSDLC_Requirements/01_General.md) (Roles, Assurance Classes & Definitions)
2. [Remediation of Vulnerabilities in Production](A_SSDLC_Requirements/02_Vulnerability-Remediation.md) 
3. [Secure Operation](A_SSDLC_Requirements/03_Secure-Operation.md)
4. [Secure Development Environment](A_SSDLC_Requirements/04_Secure-Dev-Environment.md)
5. [Security within the SDLC](A_SSDLC_Requirements/05_Security-wthin-SDLC.md)
6. [Security Tests](A_SSDLC_Requirements/06_Security-Tests.md)
7. [Outsourced Development](A_SSDLC_Requirements/07_Outsourced-Development.md)

## Implementation Requirements

1. [Secure Design Principles](B_Implementation_Requirements/01_Secure-Design-Principles.md)
2. [Input Validation](B_Implementation_Requirements/02_InputVal.md)
3. [File Uploads & Downloads](B_Implementation_Requirements/03_FileUploads.md)
4. [Output Validation (Encoding & Escaping)](B_Implementation_Requirements/04_OutputVal.md)
5. [User Authentication and Registration](B_Implementation_Requirements/05_UserAuth.md)
6. [User Passwords](B_Implementation_Requirements/06_User-Passwords.md)
7. [Hardening of Session Management](B_Implementation_Requirements/07_Session-Mgmt.md)
8. [Access Control](B_Implementation_Requirements/08_Access-Control.md)
9. [Error Handling & Logging](B_Implementation_Requirements/09_Error-Handling-And-Logging.md)
10. [Data Security & Cryptography](B_Implementation_Requirements/10_Data-Security.md)
11. [Protection of Secrets](B_Implementation_Requirements/11_Secrets.md)
12. [Client-Side Security](B_Implementation_Requirements/12_Client-Side-Security.md)
13. [Services & API Security](B_Implementation_Requirements/13_API-Security.md)

## Material

- [Requiremetns for HTTP Security Header](Material/RequirementsforHTTPSecurityHeader.md)

## Legacy Versions

You can find older versions of TSS-WEB in both English and German in PDF and Word format at the [here](https://secodis.atlassian.net/wiki/spaces/TSSWEB).

## Related Standards

Generally, we aim to integrate all useful requirements from existing standards and best practices into TSS-WEB that we find helpful for baseline security in that field. This does not mean that every requirement is or should be integrated, especially when they are more advanced or very specific.

The following table outlines coverage of the most important standards and best pratices in this field.

| Standard  | Coverage |
| ------------- | ------------- |
| [OWASP TOP Ten 2021][OWASPTOPTEN] | Full coverage withing implementation controls. See [OWASP Top Ten Mapping](Material/OWASP_Top_Ten_Mapping.md). |
| [OWASP SAMM 2.0](https://owaspsamm.org/model/) | OWASP SAMM has a different scope and goal but many of its practices are covered. See detailed [OWASP SAMM Mapping](Material/OWASP_SAMM-2.0-Mapping.md) |
| [ISO/IEC 27002:2022](https://www.iso.org/standard/27001)  | TSS-WEB meets 14.2.1 control ("Secure Development Policy") and covers controls 8.24 - 8.31 |
| [NIST SSSDF](https://csrc.nist.gov/Projects/ssdf)  | TBD  |
| [SAFECode Fundamental Practices for Secure Development](https://safecode.org/uncategorized/fundamental-practices-secure-software-development/) | TBD |

Also, you may have a look at [OpenCRE](https://www.opencre.org/) which provides a general requirement mapping over many more standards.

## License
The document is licensed under Creative Commons By 4.0 and can therefore be used and changed to individual needs free of charge and without any other obligations than to name the document and author of the used template. Furthermore, any adapted version of this document does not have to be published under the same license.

## Author
This site is maintained by Secodis GmbH. Responsible for the content is Matthias Rohr. 

## Feedback 
Feedback about this content is very much welcome. Please post it in the TSS-WEB Google Group or send it directly to tss-web@googlegroups.com.

[OWASPTOPTEN]: https://owasp.org/www-project-top-ten/
