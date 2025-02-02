============================================
selfhosted.services Release Notes
============================================

.. contents:: Topics

V1.4.1
======

Fix
---

- Fix a typo with Bookstack db template (commit b752ac10b5814c00b7245ae68b445c6a84ad2fea)

V1.4.0
======

Major Changes
-------------

- Added Kavita role (commit a04e6be409c01b0d25c646056dccddbec2463680)
- Added Sabnzbd Role (commit a04e6be409c01b0d25c646056dccddbec2463680)

Minor Changes
-------------

- Update all services to latest commits
- Added the option for folder labeling
- Added the option for custom container values
- locked down github actions to specific versions

Breaking
--------

- Jellyfin now use /data instead of /media for uniformity with other services

V1.3.2
======

Minor Changes
-------------

- remove recursive attribute for folder creation

V1.3.1
======

Minor Changes
-------------

- Update all services to latest commits
- Fix selinux volume label missing from templates
- Fix discrepencies between actual and documented default variables
- Remove yamllint from workflow in favor of ansible-lint

v1.3.0
======

Major Changes
-------------

- Added Bookstack role (commit 98869fb78c6bddf536969f9a7d37b4a682de2575)
- Added Pi-Hole Role (commit db981f6f9ea1d14509b9979e7bc306911b638773)

Minor Changes
-------------

- Updated all roles to their latest release 

v1.2.0
======

Major Changes
-------------

- Added Jellyfin role (commit 64c0ff6bf81f36bb894c89ecbb9c59ecb459d08c)
- Added Frigate role (commit f8421e6ea71a1bc1435cd6608ce7e633ccdbc8dc)
- Added Sonarr role (commit ef7b1be536440b193d7ddff216f492e8fc14a1dd)
- Added Radarr role (commit 1cd652ecc14b241c6674e34bff1301b729414fc5)
- Added Lidarr role (commit c467f7a9f51d572a3815438089ac5c191f6c3d59)
- Added Prowlarr role (commit 2f7827cfecb93f4fec52c47ded939b7e1a39d028)
- Added Readarr role (commit 95d3a10fb5a7a7b527dc449ce9e98b032844f25c)
- Added Jellyseerr role (commit 8a59fe0ed768909950ac8be27dd2513502b5d27c)

Minor Changes
-------------

- Update Gitea & Homepage to latest releases 

v1.1.0
======

Major Changes
-------------

- Added gitea role

v1.0.0
======

Major Changes
-------------

- First functional Release
- Added homepage role