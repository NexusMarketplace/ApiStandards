# What are the relevant standards for NZ Government APIs?

### API standards in a nutshell
Please select the relevant stack. Read below for more guidance which to use.
* [SOAP](https://www.ict.govt.nz/guidance-and-resources/standards-compliance/new-zealand-secure-web-services-standard/)
* [REST](/REST.md)

### Background
The New Zealand Government has adopted a number of ICT standards and they are all available on [ict.govt.nz](https://www.ict.govt.nz/). The most relevant standard for APIs is the [New Zealand Secure Web Services](https://www.ict.govt.nz/guidance-and-resources/standards-compliance/new-zealand-secure-web-services-standard/) Standard.

While it refers to ‘Web Services’ (which in this context is a synonym for APIs) it does that in a more traditional way which only covers SOAP web services and it specifically mentions that *"This standard does not apply to REST based Web Services"*.

It also only applies to web services providing information classified as either UNCLASSIFIED or IN-CONFIDENCE as per the Government’s security policy statements. For more details see [The NZ Information Security Manual](http://www.gcsb.govt.nz/news/the-nz-information-security-manual).

Where does that leave REST APIs? Can NZ Government agencies build some or do they have to use SOAP? There is some confusion among agencies about this, so we talked to the GCIO who said: *“The GEA-NZ secure web services standard states that its scope is WS-&#42;/SOAP-based web services and it does not apply to REST-based services. That does not mean that you have to use the former, just that we hadn’t settled on preferred standards and patterns at the time.”*

The Nexus Marketplace is working with the [GCIO](https://www.ict.govt.nz/governance-and-leadership/the-gcio-team/) to develop a set of REST based API standards to give API suppliers and consumer guidance and assurance on how to build and consume NZ government APIs.

### How can I contribute?
This document captures **Nexus's view of API best practices and standards**. We aim to incorporate as many of them as possible into our work. To contribute please contact us at nexusmarketplace@gmail.com or send a pull request.
