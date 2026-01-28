# Kubernetes beszel-agent
<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/98b2edad-6dd6-419f-89ad-beb22d1637cd" />

A [Kubernetes DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/) that deploys beszel-agent with automatic system naming. Just apply this daemonset and your nodes with automatically add themselves as systems to your Beszel hub.

You can access the universal token by going to the Beszel hub settings, Tokens & Fingerprints. Set the persistence to "Permanent" if you want the token to last indefinitely

## Enviornment Variables
All the enviornment variables can be accessed on the Beszel hub.
- `KEY`: the SSH key of your node
- `HUB_URL`: https://your.beszel.hub
