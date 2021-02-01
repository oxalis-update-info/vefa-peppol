[![Build Status](https://travis-ci.org/difi/vefa-peppol.svg?branch=master)](https://travis-ci.org/difi/vefa-peppol)
[![CodeCov](https://codecov.io/gh/difi/vefa-peppol/branch/master/graph/badge.svg)](https://codecov.io/gh/difi/vefa-peppol)
[![Maven Central](https://img.shields.io/maven-central/v/no.difi.vefa/peppol-parent.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22no.difi.vefa%22%20AND%20a%3A%22peppol-parent%22)

The contents of this repository is currently in the process of switching ownership to [NorStella Oxalis Community](https://www.oxalis.network/). You as a user of Oxalis may find it interesting to [join the community](https://www.oxalis.network/join) for access to support, roadmap, early access and more. The founding meeting held online, Thursday November 19, 2020, at 08:30–10:30 CET. 

The Oxalis Community annual meeting scheduled to be held on 25th of March 2021. Should you wish to sign up as a member of the Oxalis Community, please use the registration form available from this site: [link](https://www.oxalis.network/join)  

---
# Upcoming changes
* Organizational changes to project - GroupID, Package name refactoring etc.
* Addition of new approved ICD values
* Change in default lookup behavior to CNAME (as per Peppol SML specification) 


---
# VEFA PEPPOL

This project implements some aspects of PEPPOL for inclusion in other projects.

* [Common](peppol-common) - Data model for PEPPOL functionality.
* [Evidence](peppol-evidence) - Implementation of ETSI REM Evidence.
* ICD - Handling of ICDs as used in PEPPOL.
* [Lookup](peppol-lookup) - Functionality for looking up participants in PEPPOL.
* Mode - Feature to configure a PEPPOL application based on a PEPPOL certificate.
* Publisher - Generic implementation of SMP interface.
* SBDH - Optimized library for handling of envelope.
* [Security](peppol-security) - Security features for PEPPOL.

Please see [changelog](/CHANGELOG.md) for changes.
