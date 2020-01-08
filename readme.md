# Open Access to Research Developer Repository (OAR-Developer)

The NIST _Science Data Portal_ and _Public Data Repository_ software is a collection of shared software repositories developed for the NIST Open Access to Research (OAR) public data infrastructure.   These software repositories include functionality for discovery, search,  filtering and access to [NIST public data](https://www.nist.gov/open) as per government policy.  

The main web entry point for NIST data dissemination and public access system is available at https://data.nist.gov.    Once a user completes a search operation,   a resulting list of records in the public data repository are available for exploration.   Underlying datasets may be downloaded.    The goal of this suite of tools and services is to implement community best practices for data and software solutions, facilitate FAIR data principles, and adhere to government requirements.

## OAR Public Software Repository List 

**Science Data Portal** ([oar-sdp](https://github.com/usnistgov/oar-sdp))  --> Data discovery user interface web application software repository

**Public Data Repository** ([oar-pdr](https://github.com/usnistgov/oar-pdr))  --> NIST public data repository user interface web application including access to data distributions,   metadata and associated publications 

**Data Access (Distribution Service)** ([oar-dist-service](https://github.com/usnistgov/oar-dist-service)) --> Data distribution API service software for individual and bulk file access and download

**Resource metadata access** ([oar-rmm](https://github.com/usnistgov/oar-rmm)) --> Data record metadata API service for search and access to dataset metadata (descriptive information) following the [NERDm JSON specification](https://data.nist.gov/od/dm/nerdm/)

**Build Software** ([oar-build](https://github.com/usnistgov/oar-build)) --> Software repository for building OAR software

**Metadata generation** ([oar-metadata](https://github.com/usnistgov/oar-metadata)) --> Metadata services software repository for working with the OAR internal metadata representation [NERDm JSON](https://data.nist.gov/od/dm/nerdm/)

Consult the README.md files in the individual repository for details on software components.    Note Docker files used for building and deploying this software are currently restricted.   

## License and Disclaimer
This software was developed by employees and contractors of the National Institute of Standards and Technology (NIST), an agency of the Federal Government and is being made available as a public service. Pursuant to title 17 United States Code Section 105, works of NIST employees are not subject to copyright protection in the United States. This software may be subject to foreign copyright. Permission in the United States and in foreign countries, to the extent that NIST may hold copyright, to use, copy, modify, create derivative works, and distribute this software and its documentation without fee is hereby granted on a non-exclusive basis, provided that this notice and disclaimer of warranty appears in all copies.

THE SOFTWARE IS PROVIDED 'AS IS' WITHOUT ANY WARRANTY OF ANY KIND, EITHER EXPRESSED, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTY THAT THE SOFTWARE WILL CONFORM TO SPECIFICATIONS, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND FREEDOM FROM INFRINGEMENT, AND ANY WARRANTY THAT THE DOCUMENTATION WILL CONFORM TO THE SOFTWARE, OR ANY WARRANTY THAT THE SOFTWARE WILL BE ERROR FREE. IN NO EVENT SHALL NIST BE LIABLE FOR ANY DAMAGES, INCLUDING, BUT NOT LIMITED TO, DIRECT, INDIRECT, SPECIAL OR CONSEQUENTIAL DAMAGES, ARISING OUT OF, RESULTING FROM, OR IN ANY WAY CONNECTED WITH THIS SOFTWARE, WHETHER OR NOT BASED UPON WARRANTY, CONTRACT, TORT, OR OTHERWISE, WHETHER OR NOT INJURY WAS SUSTAINED BY PERSONS OR PROPERTY OR OTHERWISE, AND WHETHER OR NOT LOSS WAS SUSTAINED FROM, OR AROSE OUT OF THE RESULTS OF, OR USE OF, THE SOFTWARE OR SERVICES PROVIDED HEREUNDER.
