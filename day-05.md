# Day 5 – Networking and Cloud Basics

## Task 1: Check IP Configuration

**Command used:**
```powershell
ipconfig
```

- IPv4 Address identifies a device on a network.
- Subnet Mask helps identify the network portion of an IP address.
- Default Gateway is usually the router that connects the local network to other networks.

## Task 2: Find DNS Servers

**Command used:**
```powershell
ipconfig /all
```

- DNS stands for Domain Name System.
- DNS converts domain names such as `google.com` into IP addresses.
- DNS makes websites easier to access without remembering their IP addresses.

## Task 3: Trace the Network Route

**Commands used:**
```powershell
tracert google.com
tracert github.com
```

- `tracert` shows the route packets may take to reach a destination.
- Each hop represents a router or network device along the route.
- Some hops may show `Request timed out` because network devices can block or ignore traceroute requests.
- A timeout does not always mean the internet connection is broken.

## Task 4: Explore AWS Regions and Availability Zones

- An AWS Region is a separate geographical area where AWS provides cloud services.
- An Availability Zone (AZ) is an isolated location within an AWS Region.
- A Region can contain multiple Availability Zones.
- AWS Regions and AZs help users choose where to deploy cloud resources.
- I explored the AWS console without creating any resources.

## Task 5: Public IP vs Private IP

### Private IP
- Used inside a local network, such as a home or college network.
- Usually assigned by a router through DHCP.
- Not directly reachable from the public internet.

### Public IP
- Used to identify a network or device on the public internet.
- Assigned by an internet service provider or cloud provider.
- Allows internet communication when network and security rules permit it.

### How a private-IP device accesses the internet
A router commonly uses NAT (Network Address Translation) to allow devices with private IP addresses to communicate with the internet.

## Day 5 Summary

Today I practised basic networking commands, learned about IP configuration and DNS, explored network routes using `tracert`, and studied AWS Regions, Availability Zones, public IPs, private IPs, and NAT.
