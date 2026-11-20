# Server setup

## Hardware, netwerk & OS

| Specificatie | Waarde                    |
|--------------|---------------------------|
| CPU          | 2 cores                   |
| RAM          | 4 GiB                     |
| Disk         | 32 GiB                    |
| Network ID   | 45.132.41.72/29           |
| IP address   | 45.132.41.76              |
| Gateway      | 45.132.41.73              |
| DNS          | 9.9.9.9, 149.112.112.112  |
| Hostname     | hu-s1p3-tribelink         |
| OS           | Ubuntu Server 26.04.1 LTS |

## OS Setup

| Specificatie          | Waarde                                                                                                           |
|-----------------------|------------------------------------------------------------------------------------------------------------------|
| ISO live image        | [ubuntu-26.04.1-live-server-amd64.iso](https://releases.ubuntu.com/26.04.1/ubuntu-26.04.1-live-server-amd64.iso) |
| Language              | (default) `English`                                                                                              |
| Keyboard layout       | (default) `English (US)`                                                                                         |
| Keyboard variant      | (default) `English (US)`                                                                                         |
| Type of installation  | (default) `Ubuntu Server`                                                                                        |
| Network configuration | static IP, zie [[#Hardware, netwerk & OS]]                                                                       |
| Proxy address         | (geen)                                                                                                           |
| Mirror location       | (default) `http://archive.ubuntu.com/ubuntu/`                                                                    |
| Storage layout        | (default) Guided, use entire disk, setup LVM                                                                     |
| Username              | `bart`                                                                                                           |
| Server name           | zie hostname bij [[#Hardware, netwerk & OS]]                                                                     |
| Ubuntu pro            | (default) skip                                                                                                   |
| SSH configuration     | check: Install OpenSSH server                                                                                    |
| Featured server snaps | (default) none                                                                                                   |

# Software

De volgende packages moeten geïnstalleerd worden voor TribeLink:

```bash
sudo apt install 
```