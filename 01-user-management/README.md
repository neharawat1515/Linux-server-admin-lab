# User & Access Management

## Objective
Configured users, groups, ownership, permissions, and access control on the RHEL server.

## Users
- Kavita → linuxadmin
- Muskan → developers
- Puja → support

## Groups
- linuxadmin
- developers
- support

## Directory Structure
- /srv/company-data/admins
- /srv/company-data/developers
- /srv/company-data/support

## Permissions
Each department directory is owned by root and its respective group with 770 permissions.

## Access Testing
- kavita successfully accessed the admins directory.
- puja successfully accessed the developers directory.
- muskan and  puja successfully accessed the support directory.
- Unauthorized access was tested and Permission denied was verified.
