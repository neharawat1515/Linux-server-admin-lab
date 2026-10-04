# Storage & LVM

## Objective
Configured LVM-based storage on the RHEL server.

## Storage Configuration
- Disk: /dev/sda (5 GB)
- Physical Volume: /dev/sda
- Volume Group: company_vg
- Logical Volume: company_data
- Filesystem: XFS
- Mount Point: /company-data

## Persistence
Configured /etc/fstab using the filesystem UUID so the storage mounts automatically.

## Verification
Verified the LVM storage and successful mount using df -h.
