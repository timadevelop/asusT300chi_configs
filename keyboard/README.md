# Asus t300 chi dual boot keyboard auto pairing
###(windows with linux)
1) Copy key from
```
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\services\BTHPORT\Parameters\Keys\aa1111111111\bb2222222222
```
2) Create a new linkkeys & fix permission in path
```
/var/lib/bluetooth/XXXXXXXXXXXXX/
```
3) Past 1C:B7:2C:04:C5:F9 folder to
```
/var/lib/bluetooth/XXXXXXXXXXXXX/
```
4) Then replace the link key you get in windows using the correct format:
```
1C:B7:2C:04:C5:F9 xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx 0 6
```
