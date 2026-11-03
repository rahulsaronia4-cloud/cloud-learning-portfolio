# Day 6 – Cloud Computing Practice

## 1. Network Connectivity – Ping

**Command used:**
```powershell
ping google.com
```

**Observation:**
- Sent packets: 4
- Received packets: 4
- Packet loss: 0%
- Minimum time: 62 ms
- Maximum time: 156 ms
- Average time: 111 ms

**Learning:** The ping command checks network connectivity between my computer and another host.

## 2. DNS Lookup

**Command used:**
```powershell
nslookup google.com
```

**Learning:**
- DNS stands for Domain Name System.
- It converts domain names into IP addresses.
- The command helps identify the DNS server and the IP addresses returned for a domain.

## 3. Common Network Ports

I learned about the following commonly used network ports:

| Service | Port Number |
|---|---:|
| HTTP | 80 |
| HTTPS | 443 |
| SSH | 22 |
| DNS | 53 |

**Learning:** Ports help computers identify different network services and applications.

## 4. AWS VPC Exploration

**AWS Service:** Amazon Virtual Private Cloud (VPC)

**Region:** Asia Pacific (Sydney) – ap-southeast-2

### VPC Details

| Property | Value |
|---|---|
| VPC ID | vpc-0b70b70aac52b2b6f |
| State | Available |
| CIDR Block | 172.31.0.0/16 |
| Default VPC | Yes |
| Tenancy | Default |

### Subnet Details

| Subnet ID | Availability Zone | CIDR Block |
|---|---|---|
| subnet-03e31461aef91478b | ap-southeast-2a | 172.31.0.0/20 |
| subnet-0f6ec1f0d7b130bae | ap-southeast-2c | 172.31.16.0/20 |
| subnet-046bc3d77c9dc86a9 | ap-southeast-2b | 172.31.32.0/20 |

**Observation:**
- My AWS account has one default VPC.
- The VPC contains three subnets.
- All three subnets are in different Availability Zones.
- All three subnets are in Available state.

**Learning:** A VPC provides an isolated virtual network environment in AWS. Subnets divide the VPC network into smaller networks.

## 5. Cloud Networking – Theory

### What is an IP Address?

An IP (Internet Protocol) address is a unique numerical address assigned to a device on a network. It helps identify devices and allows them to communicate.

Example: 192.168.1.10

### What is DNS?

DNS (Domain Name System) converts human-readable domain names into IP addresses. It helps computers locate websites using their domain names.

Example: google.com

### What is a Port?

A port is a logical communication endpoint used by a computer to identify different network services or applications.

Examples:
- HTTP – 80
- HTTPS – 443
- SSH – 22
- DNS – 53

### What is a VPC?

VPC (Virtual Private Cloud) is a logically isolated virtual network in AWS where users can launch and manage cloud resources.

Example: An AWS VPC with CIDR block 172.31.0.0/16.

### Why do we use VPC in AWS?

1. To create an isolated network environment.
2. To control network access and security.
3. To divide networks into smaller subnets.
4. To manage IP address ranges.
5. To connect cloud resources securely.

## Day 6 – Key Takeaways

Today I practised basic network troubleshooting commands, learned about DNS and common network ports, and explored the AWS VPC dashboard.

**Skills
