# Kubernetes Beszel-Agent
<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/b0967867-58d3-4f99-a92c-987518fc669b" />

A [Kubernetes daemon-set](https://github.com/nataliegreer/kubernetes-beszel-agent/blob/main/beszel-agent.yaml) that deploys beszel-agent with automatic system naming.

## Universal Token
The unviversal token should be set as a Kubernetes secret for best practice.
- You can access the universal token by going to the Beszel Hub settings, Tokens & Fingerprints
  - Set the persistence to "Permanent" if you never want the universal token to expire
## Enviornment Variables
All the enviornment variables can be accessed on the Beszel Hub.
- The "KEY" enviornment variable can be accessed by clicking "Add System"
- The "HUB_URL" enviornment variable is the location of the Beszel Hub
- The universal token enviornment variable is set by getting it's value from the Kubernetes secret
