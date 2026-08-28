# ufw.us-firewall-panel
Simple UFW firewall management tool for Ubuntu/Debian Manage firewall rules with ufw.us

# UFW Firewall Panel
Simple UFW firewall management tool
Supported Systems: (Ubuntu/Debian)

## Install
Copy and run:
```bash
bash <(curl -s https://raw.githubusercontent.com/MillySoyYo/ufw.us-firewall-panel/main/ufw.us.txt)
```
## Open Panel
Run:
```bash
ufw.us
```
## Uninstall
Run:
```bash
sudo rm -rf /usr/local/bin/ufw.us /opt/ufw-panel
```
## Features
View rules  
Add ports  
Delete ports  
TCP/UDP support  
Port range support  

Manage UFW rules with a simple panel

## Panel Preview
```bash
Main Menu
┌────────────────────────────────────────┐
│ ====================================== │
│     UFW Firewall Management Panel      │
│ ====================================== │
│                                        │
│ Type ufw.us to open this firewall panel│
│                                        │
│ 1. View Firewall Rules                 │
│ 2. Add Port Rule                       │
│ 3. Delete Port Rule                    │
│ 4. Exit Panel                          │
│                                        │
│ Enter your choice [1-4]:               │
│                                        │
└────────────────────────────────────────┘
Main menu for managing Ufw
Firewall Rules
```

```bash
┌────────────────────────────────────────┐
│ ====================================== │
│       Live UFW Firewall Rules          │
│ ====================================== │
│                                        │
│ Status: active                         │
│ Logging: on (low)                      │
│                                        │
│ Default:                               │
│ deny (incoming)                        │
│ allow (outgoing)                       │
│                                        │
│ To              Action                 │
│ --              ------                 │
│ 22/tcp          ALLOW IN               │
│ 443/udp         ALLOW IN               │
│                                        │
│ Press Enter to return...               │
│                                        │
└────────────────────────────────────────┘
Shows current firewall status
Add Port Rule
```

``bash
┌────────────────────────────────────────┐
│ ====================================== │
│            Add Port Rule               │
│ ====================================== │
│                                        │
│ 0. Back                                │
│                                        │
│ WARNING:                               │
│ A large port range may open many ports.│
│ Only use a range when you understand   │
│ the security impact.                   │
│                                        │
│ Enter Port or Port Range:              │
│                                        │
│ Select Protocol:                       │
│                                        │
│ 1. TCP                                 │
│ 2. UDP                                 │
│ 0. Back                                │
│                                        │
│ Choose option [0-2]:                   │
│                                        │
└────────────────────────────────────────┘
Add TCP or UDP port rules
Delete Port Rule uses the same interface
```
