# Notes

- Started initial recon using Nmap
- Identified multiple exposed services
- SMB ports 139/445 open
- enum4linux revealed host information
- FTP allowed anonymous login
- HTTP service detected on port 80

## Commands Used

nmap -A <target-ip>

enum4linux <target-ip>

ftp <target-ip>

whatweb <target-ip>

## Next Steps

- analyze HTTP headers
- inspect exposed directories
- improve documentation