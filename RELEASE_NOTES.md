# NIST OAR Data Dissemination System: RELEASE NOTES

including:
 * Science Data Portal (SDP)
 * Public Data Repository (PDR)
 * supporting API-enabled services (RMM, DS)


An ODD Release is embodied by a release and deployment of the systems
provided by the oar-docker repository (https://github.com/usnistgov/oar-docker,
private).

## Version 1.4.7 (2021-03-18)

Bug Fix Release
* SDP:
   * improved search results page performace
   * cosmetic changes to filters, key datasets list
* PDR-LPS:
   * bug fix in download-all feature for large collections, datasets using new
     ark ids
   * fix rendering of references
* PDR Publishing:
   * fix labeling of references for proper rendering
   * new CLI publishing tool for administrators
   * new API for preservation service (requiring POD record as input)
   * fix affiliation encoding for DataCite
* DS:
   * enhanced logging for metrics harvesting
* RMM:
   * fix CORS configuration for public access to API

oar-apps
  oar-rmm-service:      oar-rmm          v1.0.7
  sdp:                  oar-sdp          v1.3.2
  pdr-nerdm:            oar-metadata     v1.0.18
  nerdm-docs:           oar-metadata     v1.0.18
  pdr-lps:              oar-pdr          v1.4.6
  oar-dist-service:     oar-dist-service v2.1.8
  oar-config-server:    oar-config       v1.4.7

oar-publish
  pdr-publish:          oar-pdr          v1.4.6
  pdr-publish:          oar-metadata     v1.0.18
  pdr-lps:              oar-pdr          v1.4.6
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.4.7

## Version 1.4.6 (2020-11-26)

Bug Fix Release
* SDP:
   * query processing fixes
   * additional advanced query improvements
* PDR
   * fix similar dataset searches
   * small customizing interface improvements
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.6
  sdp:                  oar-sdp          v1.3.1
  pdr-nerdm:            oar-metadata     v1.0.17
  nerdm-docs:           oar-metadata     v1.0.17
  pdr-lps:              oar-pdr          v1.4.5
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.6

oar-publish
  pdr-publish:          oar-pdr          v1.4.3
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.5
  customization-api:    oar-pdr          v1.4.3
  oar-config-server:    oar-config       v1.4.6
```

## Version 1.4.5 (2020-10-08)

Bug Fix Release
* PDR Customization: updated NIST SSO metdata

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.6
  sdp:                  oar-sdp          v1.3.0
  pdr-nerdm:            oar-metadata     v1.0.16
  nerdm-docs:           oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.4
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.5

oar-publish
  pdr-publish:          oar-pdr          v1.4.3
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.4
  customization-api:    oar-pdr          v1.4.3
  oar-config-server:    oar-config       v1.4.5
```

## Version 1.4.4 (2020-10-07)

Bug Fix Release
* RMM: fix tagging error from previous release
* PDR about page: fixed link to GitHub

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.6
  sdp:                  oar-sdp          v1.3.0
  pdr-nerdm:            oar-metadata     v1.0.16
  nerdm-docs:           oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.4
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.4

oar-publish
  pdr-publish:          oar-pdr          v1.4.3
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.4
  customization-api:    oar-pdr          v1.4.3
  oar-config-server:    oar-config       v1.4.4
```

## Version 1.4.3 (2020-10-01)

Bug Fix Release
* SDP/RMM
    * Fixed/improved advanced search builder and documentation
    * Improved RMM API search syntax
* PDR Publishing Service (pubserver)
    * Update NERDm schema version
    * Fix clean-up/versioning error

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.5
  sdp:                  oar-sdp          v1.3.0
  pdr-nerdm:            oar-metadata     v1.0.16
  nerdm-docs:           oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.3
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.3

oar-publish
  pdr-publish:          oar-pdr          v1.4.3
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.4.3
  customization-api:    oar-pdr          v1.4.3
  oar-config-server:    oar-config       v1.4.3
```

## Version 1.4.2 (2020-09-14)

Bug Fix Release
* PDR Publishing Service (pubserver)
    * Fix bag clean-up during multibag splitting causing failures
    * Fix error handling during DOI minting
    * Update NERDm schema, disallowing null landing page URL
    * Mark submissions with authors as a "DataPublication" type
 * PDR Landing Page Service
    * Fix Resource type handling

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.4
  sdp:                  oar-sdp          v1.2.10
  pdr-nerdm:            oar-metadata     v1.0.15
  nerdm-docs:           oar-metadata     v1.0.15
  pdr-lps:              oar-pdr          v1.4.2
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.2

oar-publish
  pdr-publish:          oar-pdr          v1.4.2
  pdr-publish:          oar-metadata     v1.0.15
  pdr-lps:              oar-pdr          v1.4.2
  customization-api:    oar-pdr          v1.4.0
  oar-config-server:    oar-config       v1.4.2
```

## Version 1.4.1 (2020-08-10)

Bug Fix Release
 * PDR Landing Page Service
    * Fix version listing (temporarily disable some linking)
    * Fix JSON export links
    * Dependency security updates
 * SDP:  dependency security updates

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.4
  sdp:                  oar-sdp          v1.2.10
  pdr-nerdm:            oar-metadata     v1.0.14
  nerdm-docs:           oar-metadata     v1.0.14
  pdr-lps:              oar-pdr          v1.4.1
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.2

oar-publish
  pdr-publish:          oar-pdr          v1.4.1
  pdr-publish:          oar-metadata     v1.0.14
  pdr-lps:              oar-pdr          v1.4.1
  customization-api:    oar-pdr          v1.4.0
  oar-config-server:    oar-config       v1.4.2
```

## Version 1.4.0 (2020-08-10)

Major Feature Release: Landing Page Editing/Customization

The internal Landing Page Service (LPS) now supports an editing mode that can
be invoked through MIDAS, allowing users to edit select metadata directly on
the landing page.  As part of this, the assigned DOIs now match the internal
local identifiers.  

Additional minor changes:
   * RMM:  fix to swagger documentation
   * SDP:  improvements to advance search layout.

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.4
  sdp:                  oar-sdp          v1.2.9
  pdr-nerdm:            oar-metadata     v1.0.13
  nerdm-docs:           oar-metadata     v1.0.13
  pdr-lps:              oar-pdr          v1.4.0
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.4.0

oar-publish
  pdr-publish:          oar-pdr          v1.4.0
  pdr-publish:          oar-metadata     v1.0.13
  pdr-lps:              oar-pdr          v1.4.0
  customization-api:    oar-pdr          v1.4.0
  oar-config-server:    oar-config       v1.4.0
```

## Version 1.3.8 (2020-06-12)

Bug Fix Release:
   * PDR
     * Data cart now provides more information on downloads
     * more robust display of email addresses
     * improved citation display on mobile devices
     * security updates (for 3rd party libraries)
   * PDR Distribution Service
     * provide more information to data cart
   * SDP
     * secuirty updates (for 3rd party libraries)
   * RMM
     * reduced logging rate

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.3
  sdp:                  oar-sdp          v1.2.8
  pdr-nerdm:            oar-metadata     v1.0.12
  nerdm-docs:           oar-metadata     v1.0.12
  pdr-lps:              oar-pdr          v1.3.8
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.0.14

oar-publish
  pdr-lps:              oar-pdr          v1.3.8
  pdr-publish:          oar-pdr          v1.3.7
  pdr-publish:          oar-metadata     v1.0.12
  oar-config-server:    oar-config       v1.0.14
```

## Version 1.3.7 (2020-05-21)

Bug Fix Release:
   * SDP
     * fix support for author filter
     * added apple-touch icon for browsing on IOS platforms
   * PDR
     * improved data cart messaging and error handling
     * publishing:
       * fix research topic processing
       * fix download URL munging error
     * distribution service: updated bundling service to support data cart improvements

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.7
  pdr-nerdm:            oar-metadata     v1.0.12
  nerdm-docs:           oar-metadata     v1.0.12
  pdr-lps:              oar-pdr          v1.3.7
  oar-dist-service:     oar-dist-service v2.1.7
  oar-config-server:    oar-config       v1.0.14

oar-publish
  pdr-lps:              oar-pdr          v1.3.7
  pdr-publish:          oar-pdr          v1.3.7
  pdr-publish:          oar-metadata     v1.0.12
  oar-config-server:    oar-config       v1.0.14
```

## Version 1.3.6 (2020-05-05)

Bug Fix Release:
   * PDR
     * publish (mdserver/pubserver): fixed sha-file deletion bug
     * added apple-touch icon for browsing on IOS platforms

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.6
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.6
  oar-dist-service:     oar-dist-service v2.1.6
  oar-config-server:    oar-config       v1.0.13

oar-publish
  pdr-lps:              oar-pdr          v1.3.6
  pdr-publish:          oar-pdr          v1.3.6
  pdr-publish:          oar-metadata     v1.0.11
  oar-config-server:    oar-config       v1.0.13
```

## Version 1.3.5 (2020-04-29)

Bug Fix Release:
   * PDR distrib service:
      *  fix AWS pagination error
      *  raise limit on open descriptors

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.6
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.3
  oar-dist-service:     oar-dist-service v2.1.6
  oar-config-server:    oar-config       v1.0.13

oar-publish
  pdr-lps:              oar-pdr          v1.3.3
  pdr-publish:          oar-pdr          v1.3.5
  pdr-publish:          oar-metadata     v1.0.11
  oar-config-server:    oar-config       v1.0.13
```

## Version 1.3.4 (2020-04-16)

Bug Fix Release:
   * PDR mdserver/pubserver: fix JSON file locking bug fix
   * updated displayed version

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.6
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.3
  oar-dist-service:     oar-dist-service v2.1.5
  oar-config-server:    oar-config       v1.0.13

oar-publish
Components: 

  pdr-lps:              oar-pdr          v1.3.3
  pdr-publish:          oar-pdr          v1.3.5
  pdr-publish:          oar-metadata     v1.0.11
  oar-config-server:    oar-config       v1.0.13
```

## Version 1.3.3 (2020-04-15)

Bug Fix Release:
   * PDR mdserver/pubserver: fix JSON file locking bug

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.6
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.3
  oar-dist-service:     oar-dist-service v2.1.5
  oar-config-server:    oar-config       v1.0.12

oar-publish
  pdr-lps:              oar-pdr          v1.3.3
  pdr-publish:          oar-pdr          v1.3.4
  pdr-publish:          oar-metadata     v1.0.11
  oar-config-server:    oar-config       v1.0.12
```

## Version 1.3.2 (2020-04-13)

Bug Fix Release:
  * PDR bug fixes:
    * restored View Metadata functionality
    * updated algorithm for detecting PDR home page URLs (used to display
      "Visit Home Page" button) to support new ID convention
  * SDP: improve start-up performance
  * Distribution service: return more summary information in bundle plans

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.6
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.3
  oar-dist-service:     oar-dist-service v2.1.5
  oar-config-server:    oar-config       v1.0.12

oar-publish
  pdr-lps:              oar-pdr          v1.3.3
  pdr-publish:          oar-pdr          v1.2.9
  pdr-publish:          oar-metadata     v1.0.9
  oar-config-server:    oar-config       v1.0.12
```

## Version 1.3.1 (2020-04-07)

Bug Fix Release
  * updated production site certificates
  * publish: moved stage_dir to larger partition
  * PDR: Landing Page Service (LPS)
      * adjust Google Analytics config (rm yt=true)
      * address dependency vulnerabilities
  * SDP
      * adjust Google Analytics config (rm yt=true)
      * address dependency vulnerabilities
      * remove ultima dependency (for start-up performance)

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.5
  pdr-nerdm:            oar-metadata     v1.0.11
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.2
  oar-dist-service:     oar-dist-service v2.1.4
  oar-config-server:    oar-config       v1.0.12

oar-publish
  pdr-lps:              oar-pdr          v1.3.2
  pdr-publish:          oar-pdr          v1.2.9
  pdr-publish:          oar-metadata     v1.0.9
  oar-config-server:    oar-config       v1.0.12
```

## Version 1.3.0 (2020-02-03)

Bug Fix Release:
  * distribution service: fix file descriptor leak and issues with large
    datasets (again)
  * SDP:  fix links, 508 compliance support
  * PDR:  new code layout 

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.4
  pdr-nerdm:            oar-metadata     v1.0.10
  nerdm-docs:           oar-metadata     v1.0.8
  pdr-lps:              oar-pdr          v1.3.0
  oar-dist-service:     oar-dist-service v2.1.4
  oar-config-server:    oar-config       v1.0.12

oar-publish
  pdr-lps:              oar-pdr          v1.3.0
  pdr-publish:          oar-pdr          v1.2.9
  pdr-publish:          oar-metadata     v1.0.9
  oar-config-server:    oar-config       v1.0.12
```

## Version 1.2.7 (2019-12-13)

Bug Fix Release:
  * distribution service: fix file descriptor leak and issues with large datasets
  * SDP:  fix links, Google Analytics support, other finer fixes
  * PDR:  fix search-by-authors

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.3
  pdr-nerdm:            oar-metadata     v1.0.8
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.9
  oar-dist-service:     oar-dist-service v2.1.3
  oar-config-server:    oar-config       v1.0.11

oar-publish
  pdr-lps:              oar-pdr          v1.2.9
  pdr-publish:          oar-pdr          v1.2.8
  pdr-publish:          oar-metadata     v1.0.9
  oar-config-server:    oar-config       v1.0.11
```

## Version 1.2.6 (2019-12-13)

Bug Fix Release:
  * PDR publishing bug fix: fix processing of DOIs in metadata
  * add a robots.txt file

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.2
  pdr-nerdm:            oar-metadata     v1.0.8
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.6
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.10

oar-publish
  pdr-lps:              oar-pdr          v1.2.6
  pdr-publish:          oar-pdr          v1.2.8
  pdr-publish:          oar-metadata     v1.0.9
  oar-config-server:    oar-config       v1.0.10
```

## Version 1.2.5 (2019-08-23)

Bug Fix Release:
  * PDR preservation bug fix: ensure NERDm cache gets updated

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.2
  pdr-nerdm:            oar-metadata     v1.0.8
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.6
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9

oar-publish
  pdr-lps:              oar-pdr          v1.2.6
  pdr-publish:          oar-pdr          v1.2.7
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.2.4 (2019-08-19)

Bug Fix Release:
  * PDR preservation bug fix: DataChecker AVAIL_ const typo

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.2
  pdr-nerdm:            oar-metadata     v1.0.8
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.6
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9

oar-publish
  pdr-lps:              oar-pdr          v1.2.6
  pdr-publish:          oar-pdr          v1.2.6
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.2.3 (2019-08-08)

Bug Fix Release:
  * preservation service bug fix: handle rapid updates
  * enhancements to Google Analytics support

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.2
  pdr-nerdm:            oar-metadata     v1.0.8
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.5
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9

oar-publish
  pdr-lps:              oar-pdr          v1.2.5
  pdr-publish:          oar-pdr          v1.2.5
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.2.2 (2019-07-31)

Bug Fix Release:
  * preservation service: protect from overwriting bags in long-term storage

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.1
  pdr-nerdm:            oar-metadata     v1.0.7
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.3
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9

oar-publish
  pdr-lps:              oar-pdr          v1.2.3
  pdr-publish:          oar-pdr          v1.2.4
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.2.1 (2019-07-28)

Bug Fix Release:
  * update certs for oardev, datapubtest
  * pdr-publish:  bug fixes for ARK-ID support

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.1
  pdr-nerdm:            oar-metadata     v1.0.7
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.3
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9


oar-publish
  pdr-lps:              oar-pdr          v1.2.3
  pdr-publish:          oar-pdr          v1.2.3
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.2.0 (2019-07-21)

Features/Fixes:
  * full-featured use of Google Analytics
  * fixed support for Internet Explorer 11
  * support for new ARK-based IDs for the EDI IDs
  * PDR LPS:
    * new configuration framework; fix server-side rendering
    * turn AOT compilation back on
  * PDR Publishing:
    * support for rich reference descriptions (via DOI metadata resolution)
  * SDP: don't rely on PDR for configuration

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.2
  sdp:                  oar-sdp          v1.2.1
  pdr-nerdm:            oar-metadata     v1.0.7
  nerdm-docs:           oar-metadata     v1.0.7
  pdr-lps:              oar-pdr          v1.2.2
  oar-dist-service:     oar-dist-service v2.1.2
  oar-config-server:    oar-config       v1.0.9

oar-publish
  pdr-lps:              oar-pdr          v1.2.2
  pdr-publish:          oar-pdr          v1.2.2
  pdr-publish:          oar-metadata     v1.0.7
  oar-config-server:    oar-config       v1.0.9
```

## Version 1.1.8 (2019-05-22)

Features/Fixes:
  * SDP: Angular Seed-less
  * PDR: UI and unit test improvements
    * unit tests were made functional again
    * "Visit Home Page" button only appears when it is not the PDR landing page
    * bug with adding all data to data cart for projects having
      multiple folders fixed 
    * fixed error handling in the data car
    * fixed formatting issue for file description pop-up
  * Dist service: data packaging improvements (error handling)
  * relax CORS restrictions

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.2.0
  pdr-nerdm:            oar-metadata     v1.0.6
  nerdm-docs:           oar-metadata     v1.0.6
  pdr-lps:              oar-pdr          v1.2.1
  oar-dist-service:     oar-dist-service v2.1.1
  oar-config-server:    oar-config       v1.0.8

oar-publish
  pdr-lps:              oar-pdr          v1.2.1
  pdr-publish:          oar-pdr          v1.2.0
  pdr-publish:          oar-metadata     v1.0.6
  oar-config-server:    oar-config       v1.0.8
```

## Version 1.1.7 (2019-04-05)

Features/Fixes:
  * Distrib Service: Fix swagger docs
  * PDR: nerdm docs
  * SDP: user interface fixes

### Components

```
oar-apps
Components: 
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.4
  pdr-nerdm:            oar-metadata     v1.0.6
  nerdm-docs:           oar-metadata     v1.0.6
  pdr-lps:              oar-pdr          v1.2.0
  oar-dist-service:     oar-dist-service v2.1.0
  oar-config-server:    oar-config       v1.0.8

oar-publish
  pdr-lps:              oar-pdr          v1.2.0
  pdr-publish:          oar-pdr          v1.2.0
  pdr-publish:          oar-metadata     v1.0.6
  oar-config-server:    oar-config       v1.0.8
```

## Version 1.1.6 (2019-02-11)

Bug fix release: Add intermediate CA for new certs

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.3
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-pdr          v1.1.1
  oar-dist-service:     oar-dist-service v2.0.1
  oar-config-server:    oar-config       v1.0.7

oar-publish
  pdr-lps:              oar-pdr          v1.1.1
  pdr-publish:          oar-pdr          v1.1.2
  pdr-publish:          oar-metadata     v1.0.5
  oar-config-server:    oar-config       v1.0.7
```

## Version 1.1.5 (2019-02-07)

Update production site certs

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.3
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-pdr          v1.1.1
  oar-dist-service:     oar-dist-service v2.0.1
  oar-config-server:    oar-config       v1.0.7

oar-publish
  pdr-lps:              oar-pdr          v1.1.1
  pdr-publish:          oar-pdr          v1.1.2
  pdr-publish:          oar-metadata     v1.0.5
  oar-config-server:    oar-config       v1.0.7
```

## Version 1.1.3 (2019-02-05)

Bug fix release: Distributions service: fix semicolon bug

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.3
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-pdr          v1.1.1
  oar-dist-service:     oar-dist-service v2.0.1
  oar-config-server:    oar-config       v1.0.7

oar-publish
  pdr-lps:              oar-pdr          v1.1.1
  pdr-publish:          oar-pdr          v1.1.2
  pdr-publish:          oar-metadata     v1.0.5
  oar-config-server:    oar-config       v1.0.7
```

## Version 1.1.2 (2018-17-06)

Bug fix release
PDR-Publish:
 * Fix how we determine which distributions should be included
 * build system fixes

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.3
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-pdr          v1.1.1
  oar-dist-service:     oar-dist-service v2.0.0
  oar-config-server:    oar-config       v1.0.7

oar-publish
  pdr-lps:              oar-pdr          v1.1.1
  pdr-publish:          oar-pdr          v1.1.2
  pdr-publish:          oar-metadata     v1.0.5
  oar-config-server:    oar-config       v1.0.7

```

## Version 1.1.1 (2018-12-06)

Bug fix release

### Components

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.1
  sdp:                  oar-sdp          v1.1.3
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-pdr          v1.1.1
  oar-dist-service:     oar-dist-service v2.0.0
  oar-config-server:    oar-config       v1.0.7

oar-publish
  pdr-lps:              oar-pdr          v1.1.1
  pdr-publish:          oar-pdr          v1.1.0
  pdr-publish:          oar-metadata     v1.0.5rc1
  oar-config-server:    oar-config       v1.0.7
```

## Version 1.1.0 (2018-11-01)

First non-Beta release.  Key changes:
  * Landing page service moved from oar-sdp to oar-pdr
  * PDR: Data cart added
  * Fixed Distribution service
  * SDP: Improve Advanced Search

## Version 1.0.19

Last Beta release

### Component Versions

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.0
  sdp:                  oar-sdp          v1.1.1
  pdr-nerdm:            oar-metadata     v1.0.5
  pdr-lps:              oar-sdp          v1.0.4
  oar-dist-service:     oar-dist-service v1.0.6
  oar-config-server:    oar-config       v1.0.6

oar-publish
  pdr-lps:              oar-sdp          v1.0.3
  pdr:                  oar-pdr          v1.0.8
  pdr:                  oar-metadata     v1.0.5
  oar-config-server:    oar-config       v1.0.6

```

## Version 1.0.2

First officially tagged release, Beta.

### Component Versions

```
oar-apps:
  oar-rmm-service:      oar-rmm          v1.0.0
  sdp:                  oar-sdp          v1.1.0
  pdr-nerdm:            oar-metadata     v1.0.0
  pdr-lps:              oar-sdp          v1.0.1
  oar-dist-service:     oar-dist-service v1.0.0
  oar-config-server:    oar-config       v1.0.1

oar-publish
  pdr-lps:              oar-sdp          v1.0.1
  pdr:                  oar-pdr          v1.0.0
  pdr:                  oar-metadata     v1.0.0
  oar-config-server:    oar-config       v1.0.1
```

