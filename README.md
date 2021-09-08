# 關閉IPv6

## **for Ubuntu**
```
sudo nano
```

## **for Alpine**

```
sudo nano /etc/sysctl.conf
  net.ipv6.conf.all.disable_ipv6 = 1
```