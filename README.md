This is the official site of TSS-WEB, an **open requirement framework for web-based applications & services**. All these requirements are based on common best practices (including those from OWASP, SAFECode, ISO/IEC 27002, and NIST) and our own experiences in this field.

For instance, implementing TSS-WEB also meets 14.2.1 control ("Secure Development Policy") of ISO/IEC 27002. Detailed compliance mappings are shared below.

## Purpose

The purpose of this framework is to provide a comprehensive and consistent collection of technical and organizational AppSec controls for creating your own security standards, policies, or security concepts. The idea is not to have various variants of requirements that cover every possible scenario, but one that works for most organizations, at least as a baseline. You can use all of them or just select the ones you need. In many cases, you might need to adapt some or add others more relevant to your specific organization or technology stack.


## A. General
 
 * [{{site.TITLE_GENERAL_REQUIREMENTS}}]({{site.URL_GENERAL_REQUIREMENTS}})
 * [{{site.TITLE_GENERAL_TERMS}}]({{site.URL_GENERAL_TERMS}})
 * [{{site.TITLE_GENERAL_ROLES}}]({{site.URL_GENERAL_ROLES}})
 * [{{site.TITLE_GENERAL_ASSURANCECLASSES}}]({{site.URL_GENERAL_ASSURANCECLASSES}})

## B. SSDLC Requirements

* [{{site.TITLE_SSDLC_REMEDIATION}}]({{site.URL_SSDLC_REMEDIATION}})
* [{{site.TITLE_SSDLC_SECOP}}]({{site.URL_SSDLC_SECOP}})
* [{{site.TITLE_SSDLC_SECENV}}]({{site.URL_SSDLC_SECENV}})
* [{{site.TITLE_SSDLC_SDLC}}]({{site.URL_SSDLC_SDLC}})
* [{{site.TITLE_SSDLC_SECTESTS}}]({{site.URL_SSDLC_SECTESTS}})
* [{{site.TITLE_SSDLC_OUTDEV}}]({{site.URL_SSDLC_OUTDEV}})

## C. Implementation Requirements

* [{{site.TITLE_IMPL_PRINCIPLES}}]({{site.URL_IMPL_PRINCIPLES}})
* [{{site.TITLE_IMPL_INPUTVAL}}]({{site.URL_IMPL_INPUTVAL}})
* [{{site.TITLE_IMPL_FILEUPLOADS}}]({{site.URL_IMPL_FILEUPLOADS}})
* [{{site.TITLE_IMPL_OUTPUTVAL}}]({{site.URL_IMPL_OUTPUTVAL}})
* [{{site.TITLE_IMPL_USERAUTH}}]({{site.URL_IMPL_USERAUTH}})
* [{{site.TITLE_IMPL_USERPASSWD}}]({{site.URL_IMPL_USERPASSWD}})
* [{{site.TITLE_IMPL_SESSIONMGMT}}]({{site.URL_IMPL_SESSIONMGMT}})
* [{{site.TITLE_IMPL_AUTHZ}}]({{site.URL_IMPL_AUTHZ}})
* [{{site.TITLE_IMPL_ERRORLOG}}]({{site.URL_IMPL_ERRORLOG}})
* [{{site.TITLE_IMPL_CRYPTO}}]({{site.URL_IMPL_CRYPTO}})
* [{{site.TITLE_IMPL_SECRETS}}]({{site.URL_IMPL_SECRETS}})
* [{{site.TITLE_IMPL_CLIENTSEC}}]({{site.URL_IMPL_CLIENTSEC}})
* [{{site.TITLE_IMPL_APISEC}}]({{site.URL_IMPL_APISEC}})

## D. Additional Material
* [{{site.TITLE_MATERIAL_SECHEADER}}]({{site.URL_MATERIAL_SECHEADER}})
* [{{site.TITLE_MATERIAL_TOPTENMAPPING}}]({{site.URL_MATERIAL_TOPTENMAPPING}})
* [{{site.TITLE_MATERIAL_SAMMMAPPING}}]({{site.URL_MATERIAL_SAMMMAPPING}})
  
## Legacy Versions

You can find older versions of TSS-WEB in both English and German in PDF and Word format [here](https://secodis.atlassian.net/wiki/spaces/TSSWEB).

## Related Standards

Generally, we aim to integrate all useful requirements from existing standards and best practices into TSS-WEB that we find helpful for baseline security in that field. This does not mean that every requirement is or should be integrated, especially when they are more advanced or very specific.

The following table outlines coverage of the most important standards and best practices in this field.

| Standard  | Coverage |
| ------------- | ------------- |
| [OWASP TOP Ten 2021](https://owasp.org/www-project-top-ten/) | Full coverage withing implementation controls. See [{{site.TITLE_MATERIAL_TOPTENMAPPING}}]({{site.URL_MATERIAL_TOPTENMAPPING}}). |
| [OWASP SAMM 2.0](https://owaspsamm.org/model/) | OWASP SAMM has a different scope and goal but many of its practices are covered. See [{{site.TITLE_MATERIAL_SAMMMAPPING}}]({{site.URL_MATERIAL_SAMMMAPPING}}). |
| [ISO/IEC 27002:2022](https://www.iso.org/standard/27001)  | TSS-WEB meets 14.2.1 control ("Secure Development Policy") and covers controls 8.24 - 8.31 |
| [NIST SSSDF]( https://csrc.nist.gov/Projects/ssdf)  | TBD  |
| [SAFECode Fundamental Practices for Secure Development](https://safecode.org/resource-secure-development-practices/fundamental-practices-secure-software-development-2/) | TBD |

Also, you may have a look at [OpenCRE](https://www.opencre.org/) which provides a general requirement mapping over many more standards.

## License
The document is licensed under Creative Commons By 4.0 and can therefore be used and changed to individual needs free of charge and without any other obligations than to name the document and author of the used template. Furthermore, any adapted version of this document does not have to be published under the same license.

## Author
This site is maintained by [Secodis GmbH](https://www.secodis.com). Responsible for the content is [Matthias Rohr](https://www.linkedin.com/in/matthias-rohr/). 
