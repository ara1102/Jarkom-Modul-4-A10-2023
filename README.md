# Jarkom-Modul-4-A10-2023

## Anggota Kelompok

| NRP        | Name                        |
| ---------- | --------------------------- |
| 5025211081 | Gabriella Natasya Br Ginting|
| 5025211102 | Adhira Riyanti Amanda       |

## Topologi GNS VLSM

![Topologi VLSM](/images/topologi/vlsm.jpg)

## Topologi Cisco CIDR

![Topologi CIDR](/images/topologi/cidr.png)

## Rute Subnet

![Rute](/images/rute.jpg)

## VLSM

### Tree

![Tree VLSM](/images/tree/vlsm.jpg)

### Pembagian IP

![VLSM](/images/vlsm-ip.jpg)

### Konfigurasi
- Aura
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
address 10.4.7.121
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 10.4.7.105
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.4.7.125
netmask 255.255.255.252
```

- Denken

```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.106
netmask 255.255.255.252
gateway 10.4.7.105

auto eth1
iface eth1 inet static
address 10.4.8.1
netmask 255.255.255.0
```

- RoyalCapital
```
auto eth0
iface eth0 inet static
address 10.4.8.2
netmask 255.255.255.0
gateway 10.4.8.1

```

- WilleRegion
```
auto eth0
iface eth0 inet static
address 10.4.8.65
netmask 255.255.255.0
gateway 10.4.8.1

```

- Frieren
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.117
netmask 255.255.255.252

auto eth1
iface eth1 inet static
address 10.4.7.161
netmask 255.255.255.224

auto eth2
iface eth2 inet static
address 10.4.7.122
netmask 255.255.255.252
gateway 10.4.7.121

```

- LakeKorridor
```
auto eth0
iface eth0 inet static
address 10.4.7.162
netmask 255.255.255.224
gateway 10.4.7.161

```

- Flamme
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.109
netmask 255.255.255.252

auto eth1
iface eth1 inet static
address 10.4.12.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.4.7.113
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.4.7.118
netmask 255.255.255.252
gateway 10.4.7.117

```

- Fern
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.24.1
netmask 255.255.248.0

auto eth1
iface eth1 inet static
address 10.4.7.110
netmask 255.255.255.252
gateway 10.4.7.109

```

- LaubHills
```
auto eth0
iface eth0 inet static
address 10.4.24.2
netmask 255.255.248.0
gateway 10.4.24.1

```

- RohrRoad
```
auto eth0
iface eth0 inet static
address 10.4.25.144
netmask 255.255.248.0
gateway 10.4.24.1

```

- AppetitRegion
```
auto eth0
iface eth0 inet static
address 10.4.25.144
netmask 255.255.248.0
gateway 10.4.24.1

```

- RohrRoad
```
auto eth0
iface eth0 inet static
address 10.4.12.2
netmask 255.255.252.0
gateway 10.4.12.1

```

- Himmel
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.114
netmask 255.255.255.252
gateway 10.4.7.113

auto eth1
iface eth1 inet static
address 10.4.7.145
netmask 255.255.255.248

```

- SchwerMountains
```
auto eth0
iface eth0 inet static
address 10.4.7.146
netmask 255.255.255.248
gateway 10.4.7.145

```

- Eisen
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.126
netmask 255.255.255.252
gateway 10.4.7.125

auto eth1
iface eth1 inet static
address 10.4.7.153
netmask 255.255.255.248

auto eth2
iface eth2 inet static
address 10.4.7.137
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.4.7.129
netmask 255.255.255.252

auto eth4
iface eth4 inet static
address 10.4.7.133
netmask 255.255.255.252

```

- Richter
```
auto eth0
iface eth0 inet static
address 10.4.7.154
netmask 255.255.255.248
gateway 10.4.7.153

```

- Revolte
```
auto eth0
iface eth0 inet static
address 10.4.7.155
netmask 255.255.255.248
gateway 10.4.7.153

```

- Lugner
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.134
netmask 255.255.255.252
gateway 10.4.7.133

auto eth1
iface eth1 inet static
address 10.4.16.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.4.9.1
netmask 255.255.255.0

```

- TurkRegion
```
auto eth0
iface eth0 inet static
address 10.4.16.2
netmask 255.255.252.0
gateway 10.4.16.1

```

- GrobeForest
```
auto eth0
iface eth0 inet static
address 10.4.9.2
netmask 255.255.255.0
gateway 10.4.9.1

```

- Stark
```
auto eth0
iface eth0 inet static
address 10.4.7.130
netmask 255.255.255.252
gateway 10.4.7.129

```

- Linie
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.10.1
netmask 255.255.254.0

auto eth1
iface eth1 inet static
address 10.4.7.138
netmask 255.255.255.252
gateway 10.4.7.137

auto eth2
iface eth2 inet static
address 10.4.7.141
netmask 255.255.255.252

```

- Lawine
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.142
netmask 255.255.255.252
gateway 10.4.7.141

auto eth1
iface eth1 inet static
address 10.4.7.193
netmask 255.255.255.192

```

- BredtRegion
```
auto eth0
iface eth0 inet static
address 10.4.7.194
netmask 255.255.255.192
gateway 10.4.7.193

```

- Heiter
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.4.7.224
netmask 255.255.255.192
gateway 10.4.7.193

auto eth1
iface eth1 inet static
address 10.4.20.1
netmask 255.255.252.0

```

- Sein
```
auto eth0
iface eth0 inet static
address 10.4.20.2
netmask 255.255.252.0
gateway 10.4.20.1

```

- RiegelCanyon
```
auto eth0
iface eth0 inet static
address 10.4.20.3
netmask 255.255.252.0
gateway 10.4.20.1

```

- GranzChannel
```
auto eth0
iface eth0 inet static
address 10.4.10.2
netmask 255.255.252.0
gateway 10.4.10.1

```

### Routing

- Flamme

```
route add -net 10.4.24.0 netmask 255.255.248.0 gw 10.4.7.110
route add -net 10.4.7.144 netmask 255.255.255.248  gw 10.4.7.114

```

- Frieren

```
#A14
route add -net 10.4.7.116 netmask 255.255.255.252 gw 10.4.7.118

#A19
route add -net 10.4.24.0 netmask 255.255.248.0 gw 10.4.7.118

#A17
route add -net 10.4.12.0 netmask 255.255.252.0 gw 10.4.7.118

#A16
route add -net 10.4.7.144 netmask 255.255.255.248 gw 10.4.7.118

```

- Aura

```
#Frieren
#A19
route add -net 10.4.24.0 netmask 255.255.248.0 gw 10.4.7.122

#A17
route add -net 10.4.12.0 netmask 255.255.252.0 gw 10.4.7.122

#A16
route add -net 10.4.7.144 netmask 255.255.255.248 gw 10.4.7.122

#A14
route add -net 10.4.7.116 netmask 255.255.255.252 gw 10.4.7.122

#A13
route add -net 10.4.7.160 netmask 255.255.255.224 gw 10.4.7.122

#A15
route add -net 10.4.7.112 netmask 255.255.255.252 gw 10.4.7.122

#A18
route add -net 10.4.7.160 netmask 255.255.255.252 gw 10.4.7.122

#Denken
#A21
route add -net 10.4.8.0 netmask 255.255.255.0 gw 10.4.7.106

#Eisen
#A1
route add -net 10.4.20.0 netmask 255.255.252.0 gw 10.4.7.126

#A2
route add -net 10.4.7.192 netmask 255.255.255.192 gw 10.4.7.126

#A3
route add -net 10.4.7.140 netmask 255.255.255.252 gw 10.4.7.126

#A4
route add -net 10.4.10.0 netmask 255.255.254.0 gw 10.4.7.126

#A5
route add -net 10.4.7.136 netmask 255.255.255.252 gw 10.4.7.126

#A6
route add -net 10.4.7.152 netmask 255.255.255.248 gw 10.4.7.126
#A7
route add -net 10.4.7.132 netmask 255.255.255.252 gw 10.4.7.126
#A8
route add -net 10.4.16.0 netmask 255.255.252.0 gw 10.4.7.126
#A9
route add -net 10.4.9.0 netmask 255.255.255.0 gw 10.4.7.126

#A10
route add -net 10.4.7.128 netmask 255.255.255.252 gw 10.4.7.126

```

- Lawine

```
#A1
route add -net 10.4.20.0 netmask 255.255.252.0 gw 10.4.7.224
```

- Linie

```
#A1
route add -net 10.4.20.0 netmask 255.255.252.0 gw 10.4.7.142

#A2
route add -net 10.4.7.192 netmask 255.255.255.192 gw 10.4.7.142
```

- Eisen

```
#Lugner
#A8
route add -net 10.4.16.0 netmask 255.255.252.0 gw 10.4.7.134

#A9
route add -net 10.4.9.0 netmask 255.255.255.0 gw 10.4.7.134

#Linie
#A1
route add -net 10.4.20.0 netmask 255.255.252.0 gw 10.4.7.138

#A2
route add -net 10.4.7.192 netmask 255.255.255.192 gw 10.4.7.138

#A3
route add -net 10.4.7.140 netmask 255.255.255.252 gw 10.4.7.138
```

## CIDR

### Penggabungan

Proses penggabungan subnet-subnet menjadi subnet yang lebih besar:

- Step 1

![CIDR](/images/steps/JARKOM-Step1.jpg)

- Step 2

![CIDR](/images/steps/JARKOM-Step2.jpg)

- Step 3

![CIDR](/images/steps/JARKOM-Step3.jpg)

- Step 4

![CIDR](/images/steps/JARKOM-Step4.jpg)

- Step 5

![CIDR](/images/steps/JARKOM-Step5.jpg)

- Step 6

![CIDR](/images/steps/JARKOM-Step6.jpg)

- Step 7

![CIDR](/images/steps/JARKOM-Step7.jpg)

- Step 8

![CIDR](/images/steps/JARKOM-Step8.jpg)

- Step 9

![CIDR](/images/steps/JARKOM-Step9.jpg)

- Step 10

![CIDR](/images/steps/JARKOM-Step10.jpg)

- Step 11

![CIDR](/images/steps/JARKOM-Step11.jpg)

**HASIL**

![CIDR](/images/gabungan/1.png)

![CIDR](/images/gabungan/2.png)

![CIDR](/images/gabungan/3.png)

### Tree

![Tree cidr](/images/tree/cidr.jpg)

### Pembagian IP

![cidr](/images/cidr-ip.jpg)


