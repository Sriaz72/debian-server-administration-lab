# Services and systemd

## Objective

The objective of this lab was to practice managing Linux services using systemd on a Debian server.

## Tasks Performed

- Checked the status of the Nginx service
- Started the Nginx service
- Enabled Nginx to start automatically at boot
- Restarted the Nginx service
- Checked the status of the SSH service
- Practiced checking and managing services with systemctl

## Services Tested

- Nginx web server
- SSH remote access service

## Commands Used

```bash
sudo systemctl status nginx
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl is-enabled nginx
sudo systemctl restart nginx
sudo systemctl status nginx

sudo systemctl status ssh
