# Firewall – Interview Questions & Answers

This document contains commonly asked interview questions related to firewall configuration and network security, based on the Task.

---

## 1. What is a Firewall?

A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as a protective barrier between a trusted internal network and untrusted external networks, helping to prevent unauthorized access and cyber attacks.

Firewalls can be implemented as software (host-based firewalls) or hardware devices and are a fundamental component of network security.

---

## 2. Stateful vs Stateless Firewall

### Stateless Firewall
A stateless firewall filters packets independently without tracking the state of network connections. Each packet is evaluated based solely on rules such as source IP, destination IP, and port number.

### Stateful Firewall
A stateful firewall tracks the state of active connections and makes filtering decisions based on the context of traffic. It is more secure than stateless firewalls because it understands whether packets belong to a legitimate session.

---

## 3. Why Are Firewalls Needed?

Firewalls are needed to protect systems and networks from unauthorized access, malicious traffic, and cyber threats. They help reduce the attack surface by allowing only necessary services and blocking potentially dangerous connections.

Firewalls also assist in enforcing security policies, monitoring network activity, and preventing data breaches.

---

## 4. What is an Inbound and Outbound Rule?

### Inbound Rule
Inbound rules control incoming network traffic from external sources to the internal system. These rules determine which connections are allowed to reach the system.

### Outbound Rule
Outbound rules control traffic leaving the system. They help prevent unauthorized data transmission and stop malware from communicating with external servers.

---

## 5. Can a Firewall Stop All Attacks?

No, a firewall cannot stop all attacks. While firewalls are an essential security layer, they cannot protect against threats such as malware installed locally, phishing attacks, or vulnerabilities within allowed services.

Firewalls should be used as part of a layered security approach along with antivirus software, intrusion detection systems, regular updates, and secure configurations.

---

## Conclusion

Understanding firewall concepts and being able to explain them clearly is essential for cybersecurity roles. These questions cover the foundational knowledge required to manage and secure network traffic effectively.
