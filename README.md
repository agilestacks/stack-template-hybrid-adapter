# Hybrid bare-metal Kubernetes Adapter Stack


This stack is for a bare-metal deployment which relies on the cloud for DNS. It also establishes TCP tunnels from the on-prem location in order to provide access for API and ingress. 

This stack uniquely directs api.${domain.name} to point to the NLB/ELB of the ingress tunnel. 
