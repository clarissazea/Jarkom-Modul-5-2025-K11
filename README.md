# Jarkom-Modul-5-2025-K11

<img width="1316" height="792" alt="TopologiModul5" src="https://github.com/user-attachments/assets/bd69381f-205d-4c9a-84ff-b9cf52b8f8f8" />


<img width="1280" height="770" alt="JARKOM MODUL 5" src="https://github.com/user-attachments/assets/fd3017e2-2118-46f5-bc94-dcfb209ed0f6" />

## Tabel Subnetting - Jarkom Modul 5 K11

| Subnet | Rute | Jumlah Host | Jumlah Host + Gateway | Netmask |
|--------|------|--------------|------------------------|---------|
| A1     | Moria > Switch > IronHills | 2   | 2   | /30 |
| A2     | Wilderland > Durin          | 50  | 51  | /26 |
| A3     | Wilderland > Switch > Khamul | 5   | 6   | /29 |
| A4     | Rivandell > Switch > Vilya > Switch > Narya | 3 | 3 | /29 |
| A5     | Minastir > Switch > Elendil > Switch > Isildur | 230 | 231 | /24 |
| A6     | Pelargir > Palantir         | 2   | 2   | /30 |
| A7     | AnduinBanks > Switch > Gilgalad > Switch > Cirdan | 120 | 121 | /25 |
| A8     | Moria > Wilderland          | 2   | 2   | /30 |
| A9     | Osgiliath > Moria           | 2   | 2   | /30 |
| A10    | Osgiliath > Rivandell       | 2   | 2   | /30 |
| A11    | Osgiliath > Minastir        | 2   | 2   | /30 |
| A12    | Minastir > Pelargir         | 2   | 2   | /30 |
| A13    | Pelargir > AnduinBanks      | 2   | 2   | /30 |
| **Total** |                          | **424** | **428** | **/23** |


## Tree

<img width="1072" height="655" alt="K11_Tree Modul 5" src="https://github.com/user-attachments/assets/97504eb9-c129-4c2f-9c78-8dbc507a2e14" />

## Tabel Subnetting

| Subnet | Netmask (CIDR) | Network ID   | Netmask           | Broadcast     | Range IP                     |
|--------|----------------|--------------|-------------------|---------------|------------------------------|
| A1     | /30            | 10.69.0.16   | 255.255.255.252   | 10.69.0.19    | 10.69.0.17 – 10.69.0.18      |
| A2     | /26            | 10.69.0.64   | 255.255.255.192   | 10.69.0.127   | 10.69.0.65 – 10.69.0.126     |
| A3     | /29            | 10.69.0.56   | 255.255.255.248   | 10.69.0.63    | 10.69.0.57 – 10.69.0.62      |
| A4     | /29            | 10.69.0.48   | 255.255.255.248   | 10.69.0.55    | 10.69.0.49 – 10.69.0.54      |
| A5     | /24            | 10.69.1.0    | 255.255.255.0     | 10.69.1.255   | 10.69.1.1 – 10.69.1.254      |
| A6     | /30            | 10.69.0.20   | 255.255.255.252   | 10.69.0.23    | 10.69.0.21 – 10.69.0.22      |
| A7     | /25            | 10.69.0.128  | 255.255.255.128   | 10.69.0.255   | 10.69.0.129 – 10.69.0.254    |
| A8     | /30            | 10.69.0.24   | 255.255.255.252   | 10.69.0.27    | 10.69.0.25 – 10.69.0.26      |
| A9     | /30            | 10.69.0.28   | 255.255.255.252   | 10.69.0.31    | 10.69.0.29 – 10.69.0.30      |
| A10    | /30            | 10.69.0.32   | 255.255.255.252   | 10.69.0.35    | 10.69.0.33 – 10.69.0.34      |
| A11    | /30            | 10.69.0.36   | 255.255.255.252   | 10.69.0.39    | 10.69.0.37 – 10.69.0.38      |
| A12    | /30            | 10.69.0.40   | 255.255.255.252   | 10.69.0.43    | 10.69.0.41 – 10.69.0.42      |
| A13    | /30            | 10.69.0.44   | 255.255.255.252   | 10.69.0.47    | 10.69.0.45 – 10.69.0.46      |
