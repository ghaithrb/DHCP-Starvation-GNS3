## DHCP Configuration

File: /etc/dhcp/dhcpd.conf

```
subnet 192.168.10.0 netmask 255.255.255.0 {
  range 192.168.10.50 192.168.10.100;
  option routers 192.168.10.1;
  option domain-name-servers 8.8.8.8;
  default-lease-time 600;
  max-lease-time 7200;
}
```
