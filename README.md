# About

This is the official site of TSS-WEB, an open security requirement framework for web-based applications and services. All requirements here are based on common standards and best practices, including those from [OWASP](https://www.owasp.org), [Microsoft](https://www.microsoft.com), [NIST](https://www.nist.gov), [SAFECode](https://www.safecode.org) and [ISO/IEC](https://www.iso.org).

Note that this project and its content is provided "as-is" without any guarantees. The information and views expressed are subject to change without notice. You assume all risks associated with using this content.

# Purpose

The purpose of this framework is to offer a comprehensive, consistent, and practical set of technical and organizational AppSec controls that organizations can adopt and tailor to their own security standards, policies, or concepts.

The goal is to provide a foundation that works for most organizations. In many cases, you may want to adapt only some controls or add others that are more suitable to your specific organization or technology stack.

# General
* [{{site.TITLE_GENERAL_REQUIREMENTS}}]({{site.URL_GENERAL_REQUIREMENTS}})
* [{{site.TITLE_GENERAL_TERMS}}]({{site.URL_GENERAL_TERMS}})
* [{{site.TITLE_GENERAL_ROLES}}]({{site.URL_GENERAL_ROLES}})
* [{{site.TITLE_GENERAL_RISKCLASSES}}]({{site.URL_GENERAL_RISKCLASSES}})
* [{{site.TITLE_GENERAL_FAQ}}]({{site.URL_GENERAL_FAQ}})
* [{{site.TITLE_GENERAL_LICENSE}}]({{site.URL_GENERAL_LICENSE}})

# Part A: SSDLC Controls
* [{{site.TITLE_SSDLC_SECENV}}]({{site.URL_SSDLC_SECENV}})
* [{{site.TITLE_SSDLC_SECDEV}}]({{site.URL_SSDLC_SECDEV}})
* [{{site.TITLE_SSDLC_SECTESTS}}]({{site.URL_SSDLC_SECTESTS}})
* [{{site.TITLE_SSDLC_OUTDEV}}]({{site.URL_SSDLC_OUTDEV}})
* [{{site.TITLE_SSDLC_SECOP}}]({{site.URL_SSDLC_SECOP}})

# Part B: Secure Implementation Controls
* [{{site.TITLE_IMPL_PRINCIPLES}}]({{site.URL_IMPL_PRINCIPLES}})
* [{{site.TITLE_IMPL_INPUTVAL}}]({{site.URL_IMPL_INPUTVAL}})
* [{{site.TITLE_IMPL_FILEUPLOADS}}]({{site.URL_IMPL_FILEUPLOADS}})
* [{{site.TITLE_IMPL_OUTPUTVAL}}]({{site.URL_IMPL_OUTPUTVAL}})
* [{{site.TITLE_IMPL_USERAUTH}}]({{site.URL_IMPL_USERAUTH}})
* [{{site.TITLE_IMPL_USERPASSWD}}]({{site.URL_IMPL_USERPASSWD}})
* [{{site.TITLE_IMPL_SESSIONMGMT}}]({{site.URL_IMPL_SESSIONMGMT}})
* [{{site.TITLE_IMPL_AUTHZ}}]({{site.URL_IMPL_AUTHZ}})
* [{{site.TITLE_IMPL_ERRORLOG}}]({{site.URL_IMPL_ERRORLOG}})
* [{{site.TITLE_IMPL_DATASEC}}]({{site.URL_IMPL_DATASEC}})
* [{{site.TITLE_IMPL_SECRETS}}]({{site.URL_IMPL_SECRETS}})
* [{{site.TITLE_IMPL_APISEC}}]({{site.URL_IMPL_APISEC}})
* [{{site.TITLE_IMPL_CLIENTSEC}}]({{site.URL_IMPL_CLIENTSEC}})
* [{{site.TITLE_IMPL_HTTPHEADERSEC}}]({{site.URL_IMPL_HTTPHEADERSEC}})
  
# Legacy Versions

You can find older versions of TSS-WEB in both English and German in PDF and MS Word format [here](https://secodis.atlassian.net/wiki/spaces/TSSWEB).

# Related Standards

Generally, TSS-WEB aims to incorporate requirements from existing standards and best practices in this field that are suitable to establish baseline security. However, that does not mean that every requirement is integrated, particularly those that address edge case or too specific scenarios.

The following table outlines the coverage of some important standards in this area.

| Standard  | Coverage |
| ------------- | ------------- |
| [Microsoft SDL (2024)](https://www.microsoft.com/en-us/securityengineering/sdl) | Full coverage by SSDLC controls. See [{{site.TITLE_MATERIAL_MSSDLMAPPING}}]({{site.URL_MATERIAL_MSSDLMAPPING}}). |
| [NIST SSDF 1.1](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf)  | NIST SP 800-218, the Secure Software Development Framework (SSDF). See [{{site.TITLE_MATERIAL_SSDFMAPPING}}]({{site.URL_MATERIAL_SSDFMAPPING}}). |
| [ISO/IEC 27002:2022](https://www.iso.org/standard/27001)  | TSS-WEB implements 14.2.1 control ("Secure Development Policy") and covers controls 8.24 - 8.31. |
| [OWASP TOP Ten 2021](https://owasp.org/www-project-top-ten/) | Full coverage by implementation controls. See [{{site.TITLE_MATERIAL_TOPTENMAPPING}}]({{site.URL_MATERIAL_TOPTENMAPPING}}). |
| [OWASP SAMM 2.0](https://owaspsamm.org/model/) | OWASP SAMM has a different scope and goal but practices related to security requirements should generally be covered. See [{{site.TITLE_MATERIAL_SAMMMAPPING}}]({{site.URL_MATERIAL_SAMMMAPPING}}). |
| [Microsoft S2CF](https://www.microsoft.com/en-us/securityengineering/sdl/s2c2f) | TSS-WEB coveres [Practice 2: Scan It](https://github.com/ossf/s2c2f/blob/main/specification/framework.md#practice-2-scan-it) as well as [Practice 4: Update It](https://github.com/ossf/s2c2f/blob/main/specification/framework.md#practice-4-update-it), mostly by [{{site.TITLE_SSDLC_SECDEV_3RDPARTY}}]({{site.URL_SSDLC_SECDEV_3RDPARTY}}) at the moment. |
| [OWASP Top 10 CI/CD Security Risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/) | Many recommendations are covered, mostly in [{{site.TITLE_SSDLC_SECDEV_BUILD}}]({{site.URL_SSDLC_SECDEV_BUILD}}) and [{{site.TITLE_SSDLC_SECENV}}]({{site.URL_SSDLC_SECENV}}). However TSS-WEB is, and will not be, that specific. You may therefore use this ressource for additional ideas and best practices in particular for improving pipeline security.|

Also, you may have a look at [OpenCRE](https://www.opencre.org/) which provides a general requirement mapping over many more standards.

# License
The document is licensed under [Creative Commons By 4.0](https://creativecommons.org/licenses/by/4.0/deed.en) and can therefore be used and changed to individual needs free of charge and without any other obligations than to name the document and author of the used template. Furthermore, any adapted version of this document does not have to be published under the same license.

# Author
This site is maintained by [Secodis GmbH](https://www.secodis.com). Responsible for the content is [Matthias Rohr](https://www.linkedin.com/in/matthias-rohr/).

# Thanks
Tanks a lot to Timo Pagel and Christian Schneider for their input!
