# Kubernetes Beszel-Agent
## A [Kubernetes daemon-set](https://github.com/nataliegreer/kubernetes-beszel-agent/blob/main/beszel-agent.yaml) that deploys one beszel-agent per node with automatic host name system naming.

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/b0967867-58d3-4f99-a92c-987518fc669b" />

## Universal Token
The unviversal token should be set as a Kubernetes secret for best practice.
- Access the universal token by going to the Beszel Hub settings, Tokens & Fingerprints
  - Set the persistence to "Permanent" if you never want the universal token to expire
## Enviornment Variables
All the enviornment variables can be accessed on the Beszel Hub.
- The "KEY" enviornment variable can be accessed by clicking "Add System"
- The "HUB_URL" enviornment variable is the location of the Beszel Hub
- The universal token enviornment variable is set by getting it's value from a Kubernetes secret
