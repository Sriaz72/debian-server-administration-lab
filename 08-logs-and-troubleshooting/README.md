# Logs and Troubleshooting

## Objective

The objective of this lab was to practice viewing and analyzing system logs on a Debian Linux server.

## Tasks Performed

- Viewed system logs from the current boot
- Checked for error-level messages
- Viewed Nginx service logs
- Displayed recent Nginx log entries

## Commands Used

```bash
sudo journalctl -b
sudo journalctl -p err -b
sudo journalctl -u nginx
sudo journalctl -u nginx -n 20
