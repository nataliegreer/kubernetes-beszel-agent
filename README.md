# Kubernetes beszel-agent
<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/98b2edad-6dd6-419f-89ad-beb22d1637cd" />

A [Kubernetes daemon-set](https://github.com/nataliegreer/kubernetes-beszel-agent/blob/main/beszel-agent.yaml) that deploys beszel-agent with automatic system naming. Just apply this daemonset and your nodes with automatically add themselves as systems to your Beszel hub.

# Secret
## Universal Token
The unviversal token is set as a Kubernetes secret for best practice.
- You can access the universal token by going to the Beszel hub settings, Tokens & Fingerprints
  - Set the persistence to "Permanent" if you want the token to last indefinitely
 
# DaemonSet
## Enviornment Variables
All the enviornment variables can be accessed on the Beszel hub.
- The "KEY" enviornment variable can be accessed by clicking "Add System"
- The "HUB_URL" enviornment variable is the location of your Beszel hub
