# Router Configurations

This directory contains individual router configuration files for the enterprise hub-and-spoke VPN lab.

## Configuration Files

- **DAL-R1-Hub.cfg** - Hub router with dual ISP connectivity
- **LAX-R1-Spoke.cfg** - Los Angeles spoke site
- **DEN-R1-Spoke.cfg** - Denver spoke site  
- **ATL-R1-Spoke.cfg** - Atlanta spoke site
- **WDC-R1-Spoke.cfg** - Washington DC spoke site
- **ISP1-R1.cfg** - Primary ISP simulation
- **ISP2-R1.cfg** - Backup ISP simulation

## Deployment Order

1. Deploy ISP routers first
2. Deploy hub router (DAL-R1)
3. Deploy spoke routers one by one
4. Verify connectivity at each step

## Security Note

⚠️ **Remember to change default PSKs before production deployment!**
