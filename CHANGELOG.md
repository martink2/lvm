lvm Cookbook CHANGELOG
======================
This file is used to list changes made in each version of the lvm cookbook.


v0.8.12
-------
### Improvement
- **[COOK-2991](https://tickets.opscode.com/browse/COOK-2991)** - Add SLES support

### Bug
- **[COOK-2348](https://tickets.opscode.com/browse/COOK-2348)** - Fix `lvm_logical_volume` when `mount_point` parameter is a String

v0.8.10
-------
### Bug
- [COOK-3031]: `ruby_block` to create logical volume is improperly named, causing collisions

v0.8.8
------
- [COOK-2283] - lvm version mismatch on fresh amazon linux install
- [COOK-2733] - Fix invalid only_if command in lvm cookbook
- [COOK-2822] - install, don't upgrade, lvm2 package

v0.8.6
------
- [COOK-2348] - lvm `logical_volume` doesn't work with `mount_point` parameter as String

v0.8.4
------
- [COOK-1977] - Typo "stripesize" in LVM cookbook
- [COOK-1994] - Cannot create a logical volume if fstype is not given

v0.8.2
------
- [COOK-1857] - `lvm_logical_volume` resource callback conflicts with code in provider.

v0.8.0
------
- Added providers for managing the creation of LVM physical volumes, volume groups, and logical volumes.

v0.7.1
------
- Current public release
