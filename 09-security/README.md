# Basic Security

## Objective

The objective of this lab was to practice basic Linux server security checks on a Debian server.

## Tasks Performed

- Checked the SSH service status
- Reviewed listening network ports
- Reviewed SSH service logs
- Identified users with interactive shells
- Checked sudo permissions

## Commands Used

```bash
sudo systemctl status ssh
sudo ss -tulpn
sudo journalctl -u ssh --since "today"
grep -E '/bin/bash|/bin/sh' /etc/passwd
sudo -l
