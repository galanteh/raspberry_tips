# Find Raspberry Pi on the Local LAN

```sh
$ sudo nmap -sP 192.168.1.0/24 | awk '/^Nmap/{ip=$NF}/B8:27:EB/{print ip}'
```

# MacOs install nmap

```sh
$ sudo brew install nmap
```

