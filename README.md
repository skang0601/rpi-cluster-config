# Raspberry Pi Cluster Config
This holds my current configuration for managing my home raspberry pi k3s cluster and experimenting on various things.

Use it as you will, point out any dumb mistakes I may be making as I don't really know what I'm doing. 

# Requirements
- [Helmfile](https://github.com/roboll/helmfile)

# TODOS
- [] Setup Prometheus Node Exporter
- [] Setup a daemon for controlling fanspeed based off of CPU metrics
- [] Determine tooling for managing packages on the actual host (SALT, Shell scripting, Chef, Terraform?)
- [] Should I set up port forwading on my router and expose my cluster to the public internet or use a solution like Cloudflare connect?
