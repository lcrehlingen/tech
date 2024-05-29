# Netzwerkadressen und Ports

## Netzwerkadressen

| IP  | Funktion  |
|---|---|
| 192.168.100.100  | Auswertung (Rehlingen) |
| 192.168.100.101  | Hauptaufnahme (Omega,Rehlingen)  |
| 192.168.100.102  | Backupaufnahme (Omega,Mannheim) |
| 192.168.100.103  | Frontkamera (Scaider,Rehlingen)  |
| 192.168.100.104  | Timing Client (Seltec)  |

Dass sind nicht die IPs für die Kameras, sondern die IPs für das jeweilige LAN Interface an den Rechnern Rechner. Bei
Auswerterechner und Timing Client sind es die primären IPs, die Rechner werden nur eine IP haben.
Bei den Aufnahmerechnern sind es die IPs des sekundären Interface (bei NUCs über USB/Ethernat Adapter). Das primäre Interface (bei NUCs das eingebaute Onboard Interface) hat eine
Direktverbindung zur Kamera. 

- Das Interface für die beiden Aufnahme Kameras hat immer die IP: **192.168.0.100**
- Das Interface für die Scaider Frontkamera hat immer die IP: **192.168.2.100**