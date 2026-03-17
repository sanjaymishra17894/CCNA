# Access Control Lists (ACLs)

## Introduction
Access Control Lists (ACLs) are a set of rules used to control network traffic and determine whether packets are forwarded or blocked at a network interface.

## Firewall Concepts
Firewalls are security devices that monitor and control incoming and outgoing network traffic based on predetermined security rules. They provide a barrier between trusted and untrusted networks.

## Security Best Practices
1. **Use Strong Passwords**: Always enforce complex passwords for devices.
2. **Regular Updates**: Ensure that firewalls and ACLs are regularly updated to protect against new vulnerabilities.
3. **Minimal Privilege**: Apply the principle of least privilege by only allowing necessary access.

## Real-World Scenarios
- **Corporate Network**: ACLs are used to restrict access to sensitive areas of a corporate network.
- **Data Centers**: Firewalls protect data centers from unauthorized access by filtering traffic.

## Attack Prevention
- **DDoS Attacks**: Implement rate limiting and traffic filtering to mitigate Distributed Denial of Service attacks.
- **Intrusions**: Use intrusion detection/prevention systems along with ACLs for enhanced security.

## Configuration Examples
### Basic ACL Configuration
```bash
# Allow SSH traffic
access-list 100 permit tcp any any eq 22
# Deny all other traffic
access-list 100 deny ip any any
```  

### Advanced Configuration
```bash
# Allow web traffic from a specific subnet
access-list 101 permit ip 192.168.1.0 0.0.0.255 any
# Deny traffic from a specific IP address
access-list 101 deny ip host 10.0.0.5 any
```

---

# Access Control Lists (ACLs) in Hinglish

## Parichay
Access Control Lists (ACLs) ek rules ka set hai jo network traffic ko control karne ke liye istemal hota hai.

## Firewall Concepts
Firewalls aise security devices hain jo network traffic ko monitor karte hain aur predetermined security rules ke aadhaar par control karte hain. Yeh trusted aur untrusted networks ke beech barrier pradan karte hain.

## Security Best Practices
1. **Majboot Passwords istemal karein**: Hamesha complex passwords enforce karein.
2. **Regular Updates**: Firewalls aur ACLs ko regular updates se protect karein.
3. **Minimal Privilege**: Least privilege principle ko lagu karein

## Real-World Situations
- **Corporate Network**: ACLs corporate network ke sensitive areas tak access restrict karte hain.
- **Data Centers**: Firewalls unauthorized access se data centers ko protect karte hain.

## Attack Prevention
- **DDoS Attacks**: Rate limiting aur traffic filtering se DDoS attacks ko mitigate karein.
- **Intrusions**: Enhanced security ke liye intrusion detection/prevention systems ka istemal karein.

## Configuration Examples
### Basic ACL Configuration
```bash
# Allow SSH traffic
access-list 100 permit tcp any any eq 22
# Deny sab traffic
access-list 100 deny ip any any
```

### Advanced Configuration
```bash
# Specific subnet se web traffic allow karein
access-list 101 permit ip 192.168.1.0 0.0.0.255 any
# Specific IP address se traffic deny karein
access-list 101 deny ip host 10.0.0.5 any
```