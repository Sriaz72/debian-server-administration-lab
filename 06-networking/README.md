# Networking

## Objective

The objective of this lab was to practice basic network administration and troubleshooting commands on a Debian Linux server.

## Tasks Performed

- Checked network interfaces and IP addresses
- Checked the routing table
- Displayed the server IP address
- Tested network connectivity
- Tested DNS resolution
- Checked listening network ports

## Commands Used

```bash
ip addr
ip route
hostname -I
ping -c 4 8.8.8.8
ping -c 4 google.com
sudo ss -tulpn
