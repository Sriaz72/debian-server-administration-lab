# Users and Groups

## Objective

The objective of this lab was to practice Linux user and group management on a Debian server.

## Tasks Performed

- Checked the current logged-in user
- Created a test user named `labuser`
- Created an administrative group named `sysadmins`
- Added `labuser` to the `sysadmins` group
- Verified the user's group membership

## Commands Used

```bash
whoami
sudo adduser labuser
sudo groupadd sysadmins
sudo usermod -aG sysadmins labuser
id labuser
getent group sysadmins
