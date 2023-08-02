Operates on layer 3 (IP)

Uses the GENEVE protocol (port 6081)

Useful for very strict traffic monitoring (Firewall, Intrusion detection, Prevention)

How it works:
- The Gateway Load Balancer redirects the traffic to a target group containing security measures
- The Target Group inspects the content of the traffic
- The Target groups then forwards traffic to the GLB
- The GLB forwards the traffic to the destination application if everything is OK