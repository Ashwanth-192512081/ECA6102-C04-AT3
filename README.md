Design and implement firewall rules to secure a web server by permitting
legitimate client requests, restricting unauthorized access, controlling
service-specific traffic, and evaluate the effectiveness of the rules through
different access and connectivity scenarios.

Done By Ashwanth S-192512081

Web Server Security Using Firewall Rules

Problem Statement

Design and implement firewall rules to secure a web server by permitting legitimate client requests, restricting unauthorized access, controlling service-specific traffic, and evaluating the effectiveness of the rules through different access and connectivity scenarios.

Project Overview

This project demonstrates the implementation of firewall rules in Cisco Packet Tracer to protect a web server from unauthorized network access. Extended Access Control Lists (ACLs) are configured on the router to control traffic based on source, destination, protocol, and port number.

The configuration allows legitimate users to access required web services while blocking unauthorized and restricted traffic.

Network Components

Client PC

Unauthorized/External PC

Cisco Router

Switch

Web Server


Security Configuration

The firewall rules are configured to:

Allow authorized HTTP traffic.

Allow authorized HTTPS traffic.

Restrict unauthorized clients from accessing the web server.

Control service-specific traffic using TCP port numbers.

Block unwanted network traffic.

Permit only the required communication between clients and the web server.


Testing

Different scenarios are tested to verify the firewall configuration:

Authorized Client

The authorized client accesses the web server through the permitted web service.

Result: Access Successful.

Unauthorized Client

An unauthorized client attempts to access the protected web server.

Result: Access Denied.

Service-Specific Access

Traffic to restricted services and ports is tested.

Result: Restricted traffic is blocked according to the firewall rules.

Connectivity Test

Ping and web-access tests are performed before and after applying the firewall rules.

Result: The connectivity behavior changes according to the configured security policy.

Result

The configured firewall rules successfully control access to the web server. Legitimate requests are permitted, while unauthorized clients and restricted services are blocked.

Conclusion

This project demonstrates how Extended ACL-based firewall rules can be used to secure a web server. By filtering traffic based on IP addresses, protocols, and port numbers, the network can provide legitimate users with required services while preventing unauthorized access.
