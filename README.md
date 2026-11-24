# Network Witch

Network repair and VPN connection toolkit for Windows 10/11.

- **VPN won't connect**: 13 checks of your line and PC (packet size / MTU black holes, IPv6, DNS tampering, UDP blocking, TLS interference, clock, line quality, double NAT, Windows settings, leftover VPN firewall rules), each explained in plain words with a matching fix.
- **Presets** for common problems, plus single repair actions.
- **VPN apps**: see every installed VPN client and keep only the one you use.
- **Tools**: ping, route, DNS comparison, port & TLS test, MTU finder, speed test.
- Every step is shown live; every change can be undone; a change that breaks the internet is rolled back automatically.

## Install

1. Install the [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) (x64) if you don't have it.
2. Download `NetworkWitch.exe` from the [latest release](../../releases/latest) and run it. It asks for administrator rights.
3. Optional: check the download against `NetworkWitch.exe.sha256`.

Start it with `--simulate` to try every action without changing anything.