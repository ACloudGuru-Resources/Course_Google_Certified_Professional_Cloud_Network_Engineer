# FW rules lab
acme.yaml
deploy 3 networks, two custom, one automode, 4 vm instances, 

config.yaml
deploy 3 networks, two custom, one automode, 4 vm instances,  and firewall rules

acme-prod-fw.yaml
deploys firewall rules to allow tcp ports (80,443) to the us-prod and eur-prod created with acme.yaml

acme-dev-fw.yaml
deploys firewall rules to allow tcp ports (22,80) + icmp to the auto-dev-network created with acme.yaml
