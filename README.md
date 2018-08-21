# Para revivir la vpn en windows 10 desde REGEDIT:
1. Equipo\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RasMan
2. Equipo\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RemoteAccess

En ambos crear la clave *SvcHostSplitDisable* como tipo REG_DWORD con valor **1**
Listo
