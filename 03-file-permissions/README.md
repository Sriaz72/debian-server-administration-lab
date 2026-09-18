# File Permissions

## Objective

The objective of this lab was to practice Linux file permissions, ownership, and group management.

## Tasks Performed

- Created a test file
- Checked the default file permissions
- Changed the file permissions using `chmod`
- Changed the file owner and group using `chown`
- Verified the resulting permissions and ownership

## Commands Used

```bash
touch testfile.txt
ls -l testfile.txt
chmod 600 testfile.txt
ls -l testfile.txt
sudo chown labuser:sysadmins testfile.txt
ls -l testfile.txt
