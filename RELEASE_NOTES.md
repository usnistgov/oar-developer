# NIST OAR Data Dissemination System: RELEASE NOTES

including:
 * Science Data Portal (SDP)
 * Public Data Repository (PDR)
 * supporting API-enabled services (RMM, DS)


An ODD Release is embodied by a release and deployment of the systems
provided by the oar-docker repository (https://github.com/usnistgov/oar-docker,
private).

## Version 1.14.4 (2025-09-22)

Bug fix Release:  More performance and bug fixes
  * RMM: fix releasesets, versions search responses
  * PDR Landing Page service: broken link fix
  * PDR Resolver service: fix access to versions
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.5
  pdr-py:               oar-pdr-py       v2.1.5
  pdr-py:               oar-metadata     v2.1.5
  pdr-lps:              oar-pdr-angular  v1.4.2
  sdp:                  oar-sdp          v2.1.5
  oar-rmm-python:       oar-rmm-python   v2.0.2
  pdr-py:               oar-pdr-py       v2.1.5
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.5.1
  oar-config-server:    oar-config       v1.14.3
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.14.3 (2025-09-16)

Bug fix Release:  More performance and bug fixes
  * RMM: fix access to releasesets collection
  * SDP:
     * Access to RMM more efficient for improved performance
     * Layout tweaks
  * PDR Distribution Service: bug fix to access to %-encoded URLs
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.5
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.5
  pdr-lps:              oar-pdr-angular  v1.4.1
  sdp:                  oar-sdp          v2.1.5
  oar-rmm-python:       oar-rmm-python   v2.0.1
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.5.1
  oar-config-server:    oar-config       v1.14.3
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.14.2 (2025-09-15)

Bug fix Release:  RMM performance improvements
  * RMM: run new python server using multiple gunicorn workers
  * SDP: improve filter loading efficiency
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.5
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.5
  pdr-lps:              oar-pdr-angular  v1.4.1
  sdp:                  oar-sdp          v2.1.4
  oar-rmm-python:       oar-rmm-python   v2.0.0
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.5.0
  oar-config-server:    oar-config       v1.14.2
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.14.1 (2025-09-08)

Bug fix Release:  LPS fixes, stability improvements
  * PDR: fix various LPS layout issues
  * SDP/PDR: improve browser caching behavior
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.5
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.5
  pdr-lps:              oar-pdr-angular  v1.4.1
  sdp:                  oar-sdp          v2.1.3
  oar-rmm-python:       oar-rmm-python   v2.0.0
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.5.0
  oar-config-server:    oar-config       v1.14.0
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.14.0 (2025-09-03)

Feature Release:  rclone support
  * PDR: new codebase compatible with new, forthcoming MIDAS
    o  Angular GUI framework updated to v18
    o  various presentation tweaks
    o  updated bulk download documentation
    o  distribution service: rclone support
  * RMM: new python-based implementation (precursor to NGI capabilities)
  * SDP: new home page layout
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.5
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.5
  pdr-lps:              oar-pdr-angular  v1.4.0
  sdp:                  oar-sdp          v2.1.3
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.5.0
  oar-config-server:    oar-config       v1.14.0
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.16
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.13.4 (2025-05-21)

Bug Fix Release:
  * PDR:
    o  Restricted Access: fix config for no-approval request forms
    o  Disitrubtion service: avoid timeouts while caching RPA data
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.3
  oar-rmm-service:      oar-rmm          v1.3.0
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.4
  pdr-lps:              oar-pdr          v1.11.1
  sdp:                  oar-sdp          v2.1.2
  pdr-rpa-request:      oar-pdr-angular  v1.3.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.3.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.4.3
  oar-config-server:    oar-config       v1.13.4
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.13.3 (2025-04-28)

Bug Fix Release:
  * PDR: fix metrics page for large collections
  * SDP: update NIST, X logos
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.3
  oar-rmm-service:      oar-rmm          v1.3.0
  pdr-py:               oar-pdr-py       v2.1.3
  pdr-py:               oar-metadata     v2.1.4
  pdr-lps:              oar-pdr          v1.11.1
  sdp:                  oar-sdp          v2.1.2
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.2
  auth-py:              oar-metadata     v2.1.4
  oar-dist-service:     oar-dist-service v2.4.1
  oar-config-server:    oar-config       v1.13.2
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.13.2 (2025-04-21)

Bug Fix Release:
  * PDR: make pdrdownload.py available as a client-side download tool,
    update NIST, X logos
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.3
  oar-rmm-service:      oar-rmm          v1.3.0
  pdr-py:               oar-pdr-py       v2.1.1
  pdr-py:               oar-metadata     v2.1.3
  pdr-lps:              oar-pdr          v1.11.0
  sdp:                  oar-sdp          v2.1.1
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0
  auth-py:              oar-auth-py      v1.0.1
  auth-py:              oar-metadata     v2.1.3
  oar-dist-service:     oar-dist-service v2.4.1
  oar-config-server:    oar-config       v1.13.2
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.13.1 (2025-03-07)

Bug Fix Release:
  * DS: fix bug caching large files to AWS
  * PDR: fix bug displaying download links of public files in RPS datasets
  * SDP: fix search button sensitivity
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.3
  oar-rmm-service:      oar-rmm          v1.3.0
  pdr-py:               oar-pdr-py       v2.1.1
  pdr-py:               oar-metadata     v2.1.1
  pdr-lps:              oar-pdr          v1.10.2
  sdp:                  oar-sdp          v2.1.1
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0rc1
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0rc1
  auth-py:              oar-auth-py      v1.0.1
  auth-py:              oar-metadata     v2.1.3
  oar-dist-service:     oar-dist-service v2.4.1
  oar-config-server:    oar-config       v1.13.1
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish:
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.13.1
```

## Version 1.13.0 (2025-03-04)

Note: this release was never actually deployed in production; v1.13.0rc3 was
      deployed in 2025-01.

Feature Release: New SDP implementation, replaced original RPA implementation
  * SDP: updated to Angular 18, modified look-feel in prep for NGI
  * DS: upgraded to AWS SDK v2 to address S3 streaming issues
  * PDR: replace original automated (no approval required) RPA using newer
    approval-required framework
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.2
  oar-rmm-service:      oar-rmm          v1.3.0
  pdr-py:               oar-pdr-py       v2.1.1
  pdr-py:               oar-metadata     v2.1.1
  pdr-lps:              oar-pdr          v1.10.1
  pdr-lps:              oar-metadata     v1.0.25
  sdp:                  oar-sdp          v2.1.0
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.2.0rc1
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.2.0rc1
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.1
  oar-dist-service:     oar-dist-service v2.4.0
  oar-config-server:    oar-config       v1.13.0
  nerdm-docs:           oar-metadata     v2.1.1

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.12.1
```

## Version 1.12.2 (2024-10-25)

Incremental Release: Fix RPA Caching Bug
  * DS: Fix AWS-RPA caching bug
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.1
  oar-rmm-service:      oar-rmm          v1.2.4
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.10.0
  sdp:                  oar-sdp          v2.0.0
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.4
  oar-config-server:    oar-config       v1.12.1
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.12.1
```

## Version 1.12.1 (2024-10-09)

Incremental Release: Fix dependency problem with RPA SMA authentication
  * PDR: fixed failing authentication service problem
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.1
  oar-rmm-service:      oar-rmm          v1.2.4
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.10.0
  sdp:                  oar-sdp          v2.0.0
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.3
  oar-config-server:    oar-config       v1.12.1
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.25
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.12.1
```

## Version 1.12.0 (2024-09-24)

Feature Release: Introduction of METIS Collection
  * SDP: Overhaul of UI look-and-feel (in prep for expanded capabilities)
  * PDR:
     * Landing Page Service:
       *  updates to support METIS Collection & metadata
       *  look-and-feel updates
     * Distribution service:  improvements to RPA handling
  * RMM: new search API documentation
```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.1
  oar-rmm-service:      oar-rmm          v1.2.4
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.10.0
  sdp:                  oar-sdp          v2.0.0
  pdr-rpa-request:      oar-pdr-angular  v1.2.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.2.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.3
  oar-config-server:    oar-config       v1.12.0
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.10.0
  pdr-publish:          oar-metadata     v1.0.24
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.2
```

## Version 1.11.4 (2024-09-07)

Incremental Release: Fix over-queries in SDP
  * PDR: Distribution service:  improvements to caching API, expanded cache

```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.0
  oar-rmm-service:      oar-rmm          v1.2.3
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.1
  pdr-lps:              oar-pdr          v1.9.3
  sdp:                  oar-sdp          v1.3.13
  pdr-rpa-request:      oar-pdr-angular  v1.1.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.1.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.2.1
  oar-config-server:    oar-config       v1.11.4
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.9.3
  pdr-publish:          oar-metadata     v1.0.24
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.2
```

## Version 1.11.3 (2024-05-21)

Incremental Release: Fix over-queries in SDP
  * SDP
    * fix search querying bug

```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.0
  oar-rmm-service:      oar-rmm          v1.2.3
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.1
  pdr-lps:              oar-pdr          v1.9.3
  sdp:                  oar-sdp          v1.3.13
  pdr-rpa-request:      oar-pdr-angular  v1.1.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.1.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.2
  oar-config-server:    oar-config       v1.11.3
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.9.3
  pdr-publish:          oar-metadata     v1.0.24
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.2
```

## Version 1.11.2 (2024-03-12)

Incremental Release: Tweak RPA, metrics, pdr-publish bug fixes
  * Distribution Service:
    * fix retrieval of RPA datacart file list when data has been purged
    * fix download filename for Safari
    * security fixes: upgrade dependencies
  * SDP
    * fix fields download bug
  * PDR
    * fix display of RPA datacart when data has been purged
    * fix publishing workflow bugs

```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.0
  oar-rmm-service:      oar-rmm          v1.2.3
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.9.3
  sdp:                  oar-sdp          v1.3.12
  pdr-rpa-request:      oar-pdr-angular  v1.1.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-request:      oar-lps          v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.1.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-lps          v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.2
  oar-config-server:    oar-config       v1.11.2
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.9.3
  pdr-publish:          oar-metadata     v1.0.24
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.2
```

## Version 1.11.1 (2024-03-12)

Incremental Release: Uncaching support for restricted public data
  * Distribution Service:
    * uncache requested RPA data either if declined after approval or
      after a configured time period
    * support auto-rejection of RPA requests from blacklisted countries, emails
  * RMM
    * improved download metrics for RPA downloads
  * PDR
    * tweaks to file list presentation; remove download icon from folder rows
    * support new download URL pattern for RPA data

```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.0
  oar-rmm-service:      oar-rmm          v1.2.3
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.9.2
  sdp:                  oar-sdp          v1.3.11
  pdr-rpa-request:      oar-pdr-angular  v1.1.0
  pdr-rpa-request:      oar-lib-angular  v1.1.0
  pdr-rpa-request:      oar-lps          v1.1.0
  pdr-rpa-approve:      oar-pdr-angular  v1.1.0
  pdr-rpa-approve:      oar-lib-angular  v1.1.0
  pdr-rpa-approve:      oar-lps          v1.1.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.1
  oar-config-server:    oar-config       v1.11.1
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.8.2
  pdr-publish:          oar-metadata     v1.0.22
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.0

```

## Version 1.11.0 (2024-01-16)

Feature Release: New service for requesting restricted public data
  * Distribution Service
    * add suport for managing restricted data requests
  * PDR
    * new front end forms for requesting and approviing restricted data access
    * support for downloading restricted data through the data cart
    * improved data download metrics tracking for greater accuracy
    * tweaks to Google Analytics tracking
    * various security improvements
  * SDP
    * updated some dependency versions and cleaned up build
    * minor bug fixes
  * RMM
    * minor build and security fixes

```
oar-apps
  pdr-nerdm:            oar-metadata     v2.1.0
  oar-rmm-service:      oar-rmm          v1.2.3
  pdr-py:               oar-pdr-py       v2.1.0
  pdr-py:               oar-metadata     v2.1.0
  pdr-lps:              oar-pdr          v1.9.0
  sdp:                  oar-sdp          v1.3.11
  pdr-rpa-request:      oar-pdr-angular  v1.0.0
  pdr-rpa-request:      oar-lib-angular  v1.0.0
  pdr-rpa-approve:      oar-pdr-angular  v1.0.0
  pdr-rpa-approve:      oar-lib-angular  v1.0.0
  auth-py:              oar-auth-py      v1.0.0
  auth-py:              oar-metadata     v2.1.0
  oar-dist-service:     oar-dist-service v2.3.0
  oar-config-server:    oar-config       v1.11.0
  nerdm-docs:           oar-metadata     v1.0.21

oar-publish
  pdr-publish:          oar-pdr          v1.8.2
  pdr-publish:          oar-metadata     v1.0.22
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.11.0
```

## Version 1.10.1 (2023-07-03)

(Note: version 1.9.X skipped)

Bug Fix Release:  
  * SDP
    *  Support Google Analytics 4
  * PDR
    *  Support Google Analytics 4
    *  LPS landing page layout fixes (scrolling data list, button/icon spacing)
  * RMM
    *  Robustness fixes
  * Distribution Service, RMM
    *  security fixes

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.2.2
  pdr-nerdm:            oar-metadata     v2.0.1
  nerdm-docs:           oar-metadata     v1.0.21
  pdr-py:               oar-pdr-py       v2.0.2
  pdr-py:               oar-metadata     v2.0.1
  pdr-lps:              oar-pdr          v1.8.3
  sdp:                  oar-sdp          v1.3.10
  oar-dist-service:     oar-dist-service v2.2.7
  oar-config-server:    oar-config       v1.10.1

oar-publish
  pdr-publish:          oar-pdr          v1.8.2
  pdr-publish:          oar-metadata     v1.0.22
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.10.1
```

## Version 1.10.0 (2023-01-25)

(Note: version 1.9.X skipped)

Feature Release:  the Forensics Portal and Large Collectino Support
  * SDP
    *  New icon marker for home feature boxes pointing to a Science Theme
    *  Forensics feature box now points to Forensics portal page
    *  security fixes
  * PDR
    *  Improved support for collection displays
    *  Improved display of large collections featuring scrolling bar and
       expanding windows.
    *  security fixes
  * Distribution Service, RMM
    *  Build and security fixes

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.2.1
  pdr-nerdm:            oar-metadata     v2.0.1
  nerdm-docs:           oar-metadata     v1.0.21
  pdr-py:               oar-pdr-py       v2.0.2
  pdr-py:               oar-metadata     v2.0.1
  pdr-lps:              oar-pdr          v1.8.1
  sdp:                  oar-sdp          v1.3.9
  oar-dist-service:     oar-dist-service v2.2.6
  oar-config-server:    oar-config       v1.10.0

oar-publish
  pdr-publish:          oar-pdr          v1.8.2
  pdr-publish:          oar-metadata     v1.0.22
  pdr-lps:              oar-pdr          v1.8.1
  customization-api:    oar-pdr          v1.8.1
  oar-config-server:    oar-config       v1.10.0
```

## Version 1.8.0 (2022-08-29)

Feature release: Versions and Science Themes

This release has two major goals that resulted in changes across most components:
  * to complete the support for access to past versions of datasets
  * to complete the support for science theme pages for the roll out of the Forensics
    focus area collection

Details:
  * PDR-LPS
     *  Support links to previous (and later) versions
     *  Expand support for Science Theme landing page theme, including file
        dataset browser for collection constituents
     *  Various layout fixes
  * RMM
     *  Expansion of internal database model to support access to older versions
  * PDR
     *  Added new ID resolver service
     *  New ingest service to support new internal database
  * SDP
     *  Migrated improvements in filtering and layout used in Science Themes to
        the general search view
     *  Add special pointer to the Forensics Science Theme page
     *  Various layout fixes

```
oar-apps
Components: 

  oar-rmm-service:      oar-rmm          v1.2.0
  pdr-nerdm:            oar-metadata     v2.0.0
  nerdm-docs:           oar-metadata     v1.0.21
  pdr-py:               oar-pdr-py       v2.0.0
  pdr-py:               oar-metadata     v2.0.0
  pdr-lps:              oar-pdr          v1.8.0
  sdp:                  oar-sdp          v1.3.8
  oar-dist-service:     oar-dist-service v2.2.5
  oar-config-server:    oar-config       v1.8.0

oar-publish
Components: 

  pdr-publish:          oar-pdr          v1.8.0
  pdr-publish:          oar-metadata     v1.0.21
  pdr-lps:              oar-pdr          v1.8.0
  customization-api:    oar-pdr          v1.7.0
  oar-config-server:    oar-config       v1.8.0
```

## Version 1.7.1 (2022-05-31)

Bug fix release:
* PDR-LPS
   * restore display of research topics

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.7
  pdr-nerdm:            oar-metadata     v1.0.21
  nerdm-docs:           oar-metadata     v1.0.21
  pdr-lps:              oar-pdr          v1.7.1
  oar-dist-service:     oar-dist-service v2.2.5
  oar-config-server:    oar-config       v1.7.1

oar-publish
  pdr-publish:          oar-pdr          v1.7.0
  pdr-publish:          oar-metadata     v1.0.21
  pdr-lps:              oar-pdr          v1.7.1
  customization-api:    oar-pdr          v1.7.0
  oar-config-server:    oar-config       v1.7.1
```

## Version 1.7.0 (2022-05-30)

Feature Release: Support for Science Themes
* NERDm:
   * new NERDm extension for aggregations: nerdm-agg-schema.json
   * update to core (v0.6): supporting fixes
* SDP:
   * new front pages with support for links to science themes
   * search result layout improvements inspired by science theme support
* PDR-LPS
   * support for science-themes related layout
   * upgrade to angular 13
   * layout bug fixes
* Distribution Serivce
   * bug fix: properly capture bundle downloads for metrics
   * fix file and thread leaks

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.7
  pdr-nerdm:            oar-metadata     v1.0.21
  nerdm-docs:           oar-metadata     v1.0.21
  pdr-lps:              oar-pdr          v1.7.0
  oar-dist-service:     oar-dist-service v2.2.5
  oar-config-server:    oar-config       v1.7.0

oar-publish
  pdr-publish:          oar-pdr          v1.7.0
  pdr-publish:          oar-metadata     v1.0.21
  pdr-lps:              oar-pdr          v1.7.0
  customization-api:    oar-pdr          v1.7.0
  oar-config-server:    oar-config       v1.7.0
```

## Version 1.6.5 (2022-04-10)

Bug fix Release
* Distribution Serivce
   * fix file and thread leaks
   * a cache queue service endpoint
   * allow addition bucket access to dist bundler

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.2
  oar-dist-service:     oar-dist-service v2.2.4
  oar-config-server:    oar-config       v1.6.5

oar-publish
  pdr-publish:          oar-pdr          v1.6.1
  pdr-publish:          oar-metadata     v1.0.20
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.5
```

## Version 1.6.4 (2022-03-31)

Bug fix Release
* Distribution Serivce
   * make AWS checksum checks faster

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.2
  oar-dist-service:     oar-dist-service v2.2.3
  oar-config-server:    oar-config       v1.6.4

oar-publish
  pdr-publish:          oar-pdr          v1.6.1
  pdr-publish:          oar-metadata     v1.0.20
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.4
```

## Version 1.6.3 (2022-02-15)

Bug fix Release
* Distribution Serivce
   * fix some file descriptor leaks in the cache manager

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.2
  oar-dist-service:     oar-dist-service v2.2.1
  oar-config-server:    oar-config       v1.6.3

oar-publish
  pdr-publish:          oar-pdr          v1.6.1
  pdr-publish:          oar-metadata     v1.0.20
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.3
```

## Version 1.6.2 (2022-02-11)

Feature Release
* Distribution Serivce
   * introducing the cache manager for improved performance and robustness
     of data delivery
* PDR-LPS
   * Fix metrics "More..." link

```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.2
  oar-dist-service:     oar-dist-service v2.2.0
  oar-config-server:    oar-config       v1.6.2.1

oar-publish
  pdr-publish:          oar-pdr          v1.6.1
  pdr-publish:          oar-metadata     v1.0.20
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.2.1
```

## Version 1.6.1 (2021-12-21)

Bug Fix Release

Version 1.6.0 was not deployed to production due to some minor oversights
(namely, the version displayed on web pages was not correct); this release
corrects those issues.

See V1.6.0 below for features introduced with this version.  
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.0
  oar-dist-service:     oar-dist-service v2.1.10
  oar-config-server:    oar-config       v1.6.1

oar-publish
  pdr-publish:          oar-pdr          v1.6.1
  pdr-publish:          oar-metadata     v1.0.20
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.1
```

## Version 1.6.0 (2021-12-21)

Feature Release
* SDP:
   * new search auto-suggest feature based on parmenides
* PDR-Publish:
   * Special processing added for restricted public access
   * Updated spring SAML support
   * Built-in health monitoring of the public PDR/SDP services
* PDR-LPS:
   * new file detail display
   * tweak to metrics display
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.6
  pdr-nerdm:            oar-metadata     v1.0.20
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.6.0
  oar-dist-service:     oar-dist-service v2.1.10
  oar-config-server:    oar-config       v1.6.0

oar-publish
  pdr-publish:          oar-pdr          v1.6.0
  pdr-publish:          oar-metadata     v1.0.20rc1
  pdr-lps:              oar-pdr          v1.6.0
  customization-api:    oar-pdr          v1.6.0
  oar-config-server:    oar-config       v1.6.0
```

## Version 1.5.3 (2021-10-25)

Incremental Release
* PDR-LPS:
   * replace "Metadata" setions with "About This Dataset"
   * tweak sections formatting, tools contents
   * display ORCIDs
   * fix primary reference display bug
   * fix resource type label bug
* RMM & Distribution Service:
   * fix and update Swagger API documentation
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.2
  sdp:                  oar-sdp          v1.3.5
  pdr-nerdm:            oar-metadata     v1.0.19
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.3
  oar-dist-service:     oar-dist-service v2.1.10
  oar-config-server:    oar-config       v1.5.3

oar-publish
  pdr-publish:          oar-pdr          v1.5.1
  pdr-publish:          oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.3
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.5.3
```

## Version 1.5.2 (2021-10-13)

Incremental Release
* PDR-LPS:
   * fix Safari landing page rendering bug
   * update NIST footer
   * truncate time from dates
* SDP:
   * update SDP footer
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.1
  sdp:                  oar-sdp          v1.3.5
  pdr-nerdm:            oar-metadata     v1.0.19
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.2
  oar-dist-service:     oar-dist-service v2.1.9
  oar-config-server:    oar-config       v1.5.2

oar-publish
  pdr-publish:          oar-pdr          v1.5.1
  pdr-publish:          oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.2
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.5.2
```

## Version 1.5.1 (2021-10-01)

Incremental Release
* PDR:
   * hide SHA files from file listing
   * improved metadata viewer
   * more up-to-date metrics
   * tweaks to display of access page links
   * security updates to dependencies
* SDP:
   * security updates to dependencies
* RMM:
   * fixed swagger docs
   * security updates to dependencies
* PDR Publishing
   * fix misspellings in auto-generated README
   * updated NERDm metadata support
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.1
  sdp:                  oar-sdp          v1.3.4
  pdr-nerdm:            oar-metadata     v1.0.19
  nerdm-docs:           oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.1
  oar-dist-service:     oar-dist-service v2.1.9
  oar-config-server:    oar-config       v1.5.1

oar-publish
Components: 

  pdr-publish:          oar-pdr          v1.5.1
  pdr-publish:          oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.5.1
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.5.1
```

## Version 1.5.0 (2021-07-08)

Feature Release
* PDR:
   * Introduction on dataset download metrics visible from landing page
   * Schema.org metadata embedded in landing pages for external harvesting
     (e.g. by Google)
   * minor display tweaks
* SDP
   * Fix handling of quoted text in search box
   * tweaks to menus
   * security up-revs of dependency packages
* PDR Publishing:
   * added support for changes in NIST data publication revision policy
   * added service for automated README generation
* RMM:
   * improved internal logging
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.1.0
  sdp:                  oar-sdp          v1.3.3
  pdr-nerdm:            oar-metadata     v1.0.19
  nerdm-docs:           oar-metadata     v1.0.18
  pdr-lps:              oar-pdr          v1.5.0
  oar-dist-service:     oar-dist-service v2.1.8
  oar-config-server:    oar-config       v1.5.0

oar-publish
  pdr-publish:          oar-pdr          v1.5.0
  pdr-publish:          oar-metadata     v1.0.19
  pdr-lps:              oar-pdr          v1.4.6
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.5.0
```

## Version 1.4.8 (2021-03-26)

Bug Fix Release
* PDR Publishing:
   * fix download file name on pre-publication landing page
```
oar-apps
  oar-rmm-service:      oar-rmm          v1.0.7
  sdp:                  oar-sdp          v1.3.2
  pdr-nerdm:            oar-metadata     v1.0.18
  nerdm-docs:           oar-metadata     v1.0.18
  pdr-lps:              oar-pdr          v1.4.6
  oar-dist-service:     oar-dist-service v2.1.8
  oar-config-server:    oar-config       v1.4.8

oar-publish
  pdr-publish:          oar-pdr          v1.4.7
  pdr-publish:          oar-metadata     v1.0.18
  pdr-lps:              oar-pdr          v1.4.6
  customization-api:    oar-pdr          v1.4.6
  oar-config-server:    oar-config       v1.4.8
```

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

```
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
```

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

